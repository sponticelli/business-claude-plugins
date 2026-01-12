# Plugin Creation Guide

This guide walks you through creating a Claude Code plugin for the Business Claude Plugins marketplace.

## Understanding Plugin Structure

A plugin consists of:

```
your-plugin/
├── .claude-plugin/
│   └── plugin.json       # Plugin manifest (required)
├── agents/
│   └── your-agent.md     # Agent definitions (at least one)
└── commands/
    └── your-command.md   # Command definitions (at least one)
```

### Agents vs Commands

| Component | Purpose | Invocation |
|-----------|---------|------------|
| **Agents** | Specialized AI personas with domain expertise | Automatic (Claude selects based on context) |
| **Commands** | Quick actions with defined inputs/outputs | Manual (`/command-name`) |

## Step 1: Create the Manifest

The `plugin.json` file describes your plugin to the marketplace.

```json
{
  "name": "my-plugin",
  "displayName": "My Business Plugin",
  "description": "Helps with X by doing Y",
  "version": "1.0.0",
  "author": {
    "name": "Your Name",
    "github": "your-username"
  },
  "category": "entrepreneurship",
  "tags": ["startup", "validation"],
  "agents": ["./agents/my-agent.md"],
  "commands": ["./commands/my-command.md"]
}
```

### Required Fields

| Field | Description |
|-------|-------------|
| `name` | URL-safe identifier (kebab-case) |
| `displayName` | Human-readable name |
| `description` | Brief description (under 200 chars) |
| `version` | Semantic version (e.g., `1.0.0`) |
| `author.name` | Your name |
| `author.github` | Your GitHub username |
| `category` | One of the marketplace categories |
| `tags` | 3-5 searchable keywords |
| `agents` | Array of agent file paths |
| `commands` | Array of command file paths |

## Step 2: Create an Agent

Agents are specialized AI personas that Claude can invoke when appropriate.

### Agent File Structure

```markdown
---
name: market-researcher
description: Analyzes markets and competitive landscapes. Use when evaluating market opportunities or analyzing competition.
---

# Market Researcher

You are a market research specialist who helps entrepreneurs understand their target markets.

## Core Philosophy

- Data-driven analysis over assumptions
- Focus on actionable insights
- Consider both qualitative and quantitative factors

## Capabilities

- Market size estimation (TAM/SAM/SOM)
- Competitive analysis
- Trend identification
- Customer segment analysis

## Process

1. Gather context about the market/industry
2. Identify key players and trends
3. Analyze market dynamics
4. Provide actionable insights

## Output Format

```markdown
## Market Analysis: [Market Name]

### Market Size
- TAM: $X
- SAM: $Y
- SOM: $Z

### Key Players
[List with market share]

### Trends
[Current and emerging trends]

### Opportunities
[Identified opportunities]

### Risks
[Market risks to consider]
```

## Verification Checklist

- [ ] Used current market data
- [ ] Cited sources where possible
- [ ] Considered multiple perspectives
- [ ] Provided actionable recommendations
```

### Agent Best Practices

1. **Clear trigger conditions**: The description should tell Claude when to use this agent
2. **Defined expertise**: What does this agent know? What methodology does it use?
3. **Structured output**: Define the expected output format
4. **Verification checklist**: How to validate the output quality

## Step 3: Create a Command

Commands are quick actions with defined inputs and outputs.

### Command File Structure

```markdown
---
name: market-size
description: Calculate TAM/SAM/SOM for a business idea
---

# Market Size Calculator

Quickly estimate the Total Addressable Market (TAM), Serviceable Addressable Market (SAM), and Serviceable Obtainable Market (SOM) for a business idea.

## Usage

```
/market-size [business idea or industry]
```

## Process

1. Identify the target industry
2. Research market size data
3. Calculate TAM (total market)
4. Calculate SAM (reachable segment)
5. Calculate SOM (realistic capture)

## Output Format

```markdown
## Market Size Analysis: [Idea]

### TAM (Total Addressable Market)
**$X billion**
[Explanation of calculation]

### SAM (Serviceable Addressable Market)
**$Y billion**
[Explanation of segment focus]

### SOM (Serviceable Obtainable Market)
**$Z million**
[Realistic market capture estimate]

### Assumptions
- [Assumption 1]
- [Assumption 2]

### Data Sources
- [Source 1]
- [Source 2]
```

## Example

**Input**: `/market-size B2B invoicing software for freelancers`

**Output**:
```markdown
## Market Size Analysis: B2B Invoicing for Freelancers

### TAM
**$12.8 billion** - Global invoicing software market

### SAM
**$3.2 billion** - SMB and freelancer segment

### SOM
**$32 million** - Realistic Year 1-3 capture (1% of SAM)

### Assumptions
- Focus on English-speaking markets
- Target freelancers with $50K+ annual revenue
```

---

Apply immediately to user's input.
```

### Command Best Practices

1. **Clear usage**: Show exactly how to invoke the command
2. **Defined process**: Step-by-step what happens
3. **Output template**: Exact format of the result
4. **Example**: Real-world example showing input/output
5. **"Apply immediately"**: Tells Claude to execute without confirmation

## Step 4: Test Your Plugin

Before submitting, test your plugin locally:

1. Add the marketplace to Claude Code:
   ```bash
   claude marketplace add /path/to/business-claude-plugins
   ```

2. Test agents by asking relevant questions:
   ```
   > Help me analyze the market for my SaaS idea
   ```

3. Test commands directly:
   ```
   > /market-size project management software
   ```

4. Verify output matches your expected format

## Step 5: Submit Your Plugin

1. Complete the [Submission Checklist](../templates/CHECKLIST.md)
2. Update `.claude-plugin/marketplace.json` with your plugin entry
3. Submit a Pull Request

## Tips for Great Plugins

### Focus on Specific Problems

Bad: "General business helper"
Good: "Startup idea validator using lean methodology"

### Use Established Frameworks

Reference known methodologies:
- Lean Startup
- Business Model Canvas
- Porter's Five Forces
- SWOT Analysis

### Provide Actionable Output

Bad: "The market looks promising"
Good: "TAM: $5B, SAM: $500M. Recommended entry strategy: [specific steps]"

### Include Verification

Help users validate the output:
- Checklists
- Questions to consider
- Red flags to watch for

## Examples

Look at existing plugins in the marketplace for inspiration:
- `plugins/entrepreneurship/idea-validation/` - Startup validation framework

# Usage Guide

This guide shows you how to effectively use Business Claude Plugins in your workflow.

## Installation

### Add the Marketplace

```bash
claude marketplace add https://github.com/sponticelli/business-claude-plugins
```

### Install a Plugin

```bash
claude plugin install idea-validation
```

### List Installed Plugins

```bash
claude plugin list
```

## Using Plugins

### Method 1: Direct Commands

Use slash commands for quick, specific tasks:

```
> /validate-idea A mobile app for tracking plant watering schedules
```

```
> /market-size meal kit delivery service
```

```
> /customer-persona B2B accounting software
```

### Method 2: Natural Conversation

Simply describe what you need, and Claude will use the appropriate agent:

```
> I have a startup idea for a subscription box service for pet owners.
> Can you help me validate if it's worth pursuing?
```

Claude will automatically invoke the idea-validator agent and provide structured analysis.

### Method 3: Specific Agent Request

Ask for a specific type of analysis:

```
> As a market researcher, analyze the competitive landscape for
> project management tools targeting remote teams.
```

## Workflow Examples

### Example 1: "I have a startup idea"

**Your goal**: Validate whether to pursue an idea

**Workflow**:
1. Start with idea validation
   ```
   > /validate-idea [your idea]
   ```

2. If promising, analyze the market
   ```
   > /market-size [your market]
   ```

3. Define your target customer
   ```
   > /customer-persona [your target]
   ```

4. Review recommendations and next steps

### Example 2: "I'm analyzing competition"

**Your goal**: Understand the competitive landscape

**Workflow**:
1. Ask for competitive analysis
   ```
   > Analyze the competitive landscape for [industry/product]
   ```

2. The market-researcher agent will provide:
   - Key players and market share
   - Competitive advantages
   - Market gaps and opportunities
   - Recommended positioning

### Example 3: "I need to pitch investors"

**Your goal**: Prepare investor materials

**Workflow**:
1. Validate your idea (if not done)
2. Get market size data
3. Define customer personas
4. Use outputs as foundation for pitch deck

## Understanding Output

### Confidence Levels

Agents may indicate confidence in their analysis:

| Level | Meaning |
|-------|---------|
| **High** | Based on solid data and established patterns |
| **Medium** | Reasonable analysis with some assumptions |
| **Low** | Significant assumptions or limited data |

### Verdicts

Validation results often include a verdict:

| Verdict | Meaning |
|---------|---------|
| **Strong** | Clear opportunity, proceed with confidence |
| **Promising** | Good potential, address identified concerns |
| **Needs Work** | Significant issues to resolve before proceeding |
| **Pivot** | Core idea has problems, consider alternatives |
| **Pass** | Fundamental challenges, reconsider entirely |

## Tips for Best Results

### Be Specific

Bad: "Validate my app idea"
Good: "Validate my idea for a mobile app that helps remote workers track their productivity and suggests break times based on focus patterns"

### Provide Context

Include relevant details:
- Target market/geography
- Your background/expertise
- Stage of development
- Specific concerns

### Iterate

Use outputs to refine your approach:
1. Get initial validation
2. Address concerns raised
3. Re-validate with improvements

### Combine Outputs

Multiple plugin outputs can inform each other:
- Market size → validates opportunity scale
- Customer persona → informs product features
- Competitive analysis → shapes positioning

## Troubleshooting

### "Command not found"

Ensure the plugin is installed:
```bash
claude plugin list
```

If not listed, install it:
```bash
claude plugin install [plugin-name]
```

### "Agent not responding correctly"

Try being more specific in your request, or use the direct command instead of natural language.

### "Output doesn't match my needs"

Provide feedback in your follow-up:
```
> That's helpful, but can you focus more on [specific aspect]?
```

## Getting Help

- Check the [Plugin Guide](PLUGIN_GUIDE.md) for plugin details
- Open an [Issue](https://github.com/sponticelli/business-claude-plugins/issues) for bugs
- Contribute improvements via [Pull Request](CONTRIBUTING.md)

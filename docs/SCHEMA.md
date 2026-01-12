# Schema Reference

Technical documentation for the Business Claude Plugins schema.

## Marketplace Schema

File: `.claude-plugin/marketplace.json`

```json
{
  "name": "string",
  "description": "string",
  "version": "string (semver)",
  "author": {
    "name": "string",
    "github": "string",
    "email": "string (optional)"
  },
  "repository": "string (URL)",
  "license": "string",
  "categories": [Category],
  "plugins": [PluginEntry],
  "stats": {
    "totalPlugins": "number",
    "totalAgents": "number",
    "totalCommands": "number"
  }
}
```

### Category Object

```json
{
  "id": "string (kebab-case)",
  "name": "string (display name)",
  "description": "string",
  "icon": "string (optional, icon identifier)",
  "plugins": ["string (plugin IDs)"]
}
```

### PluginEntry Object

```json
{
  "id": "string (kebab-case, matches folder name)",
  "name": "string (display name)",
  "path": "string (relative path from root)",
  "category": "string (category ID)",
  "description": "string (max 200 chars)",
  "version": "string (semver)",
  "author": {
    "name": "string",
    "github": "string"
  },
  "agents": "number (count)",
  "commands": "number (count)",
  "tags": ["string"]
}
```

## Plugin Manifest Schema

File: `plugins/[category]/[plugin]/.claude-plugin/plugin.json`

```json
{
  "name": "string (kebab-case, required)",
  "displayName": "string (required)",
  "description": "string (max 200 chars, required)",
  "version": "string (semver, required)",
  "author": {
    "name": "string (required)",
    "github": "string (required)",
    "email": "string (optional)"
  },
  "repository": "string (URL, optional)",
  "license": "string (default: MIT)",
  "category": "string (category ID, required)",
  "tags": ["string (3-5 recommended)"],
  "agents": ["string (relative paths, required)"],
  "commands": ["string (relative paths, required)"],
  "dependencies": ["string (plugin IDs, optional)"],
  "changelog": [ChangelogEntry]
}
```

### ChangelogEntry Object

```json
{
  "version": "string (semver)",
  "date": "string (YYYY-MM-DD)",
  "changes": ["string"]
}
```

## Agent File Schema

File: `plugins/[category]/[plugin]/agents/[agent-name].md`

### YAML Frontmatter (Required)

```yaml
---
name: agent-name
description: What this agent does. Use when [trigger conditions].
---
```

| Field | Required | Description |
|-------|----------|-------------|
| `name` | Yes | Kebab-case identifier, must match filename |
| `description` | Yes | Description including "Use when" trigger |

### Content Structure (Recommended)

```markdown
# Agent Display Name

[Introduction paragraph]

## Core Philosophy
[Principles and approach]

## Capabilities
[Bulleted list of what the agent can do]

## Process
[Numbered steps the agent follows]

## Output Format
[Expected output template]

## Verification Checklist
[Checklist for output validation]

## Related Agents
[Cross-references to other agents]

## Examples
[Usage examples]
```

## Command File Schema

File: `plugins/[category]/[plugin]/commands/[command-name].md`

### YAML Frontmatter (Required)

```yaml
---
name: command-name
description: Brief description of what this command does
---
```

| Field | Required | Description |
|-------|----------|-------------|
| `name` | Ye | Kebab-case identifier, must match filename |
| `description` | Yes | Brief description of the command |

### Content Structure (Recommended)

```markdown
# Command Display Name

[One-line description]

## Usage
[How to invoke the command]

## Arguments
[Table of arguments if applicable]

## Process
[Numbered steps]

## Output Format
[Expected output template]

## Examples
[Input/output examples]

---

Apply immediately to user's input.
```

## Naming Conventions

| Element | Convention | Example |
|---------|------------|---------|
| Plugin folder | kebab-case | `idea-validation` |
| Plugin ID | kebab-case | `idea-validation` |
| Agent file | kebab-case.md | `market-researcher.md` |
| Command file | kebab-case.md | `validate-idea.md` |
| Category ID | kebab-case | `entrepreneurship` |

## Version Format

Use [Semantic Versioning](https://semver.org/):

- **MAJOR.MINOR.PATCH** (e.g., `1.2.3`)
- **MAJOR**: Breaking changes
- **MINOR**: New features (backwards compatible)
- **PATCH**: Bug fixes (backwards compatible)

## Category IDs

Valid category IDs for this marketplace:

| ID | Name |
|----|------|
| `entrepreneurship` | Entrepreneurship |
| `sales` | Sales & Revenue |
| `marketing` | Marketing & Growth |
| `operations` | Operations |
| `finance` | Finance & Accounting |
| `strategy` | Business Strategy |
| `leadership` | Leadership & Management |
| `legal` | Legal & Compliance |

## Validation Rules

### plugin.json

- `name` must match the plugin folder name
- `name` must be kebab-case (lowercase, hyphens only)
- `version` must be valid semver
- `description` must be under 200 characters
- `category` must be a valid category ID
- `agents` array must have at least one entry
- `commands` array must have at least one entry
- All paths in `agents` and `commands` must exist

### Agent Files

- Filename must match `name` in frontmatter
- `description` should include "Use when" trigger phrase
- Must have YAML frontmatter with `---` delimiters

### Command Files

- Filename must match `name` in frontmatter
- Should end with "Apply immediately" instruction
- Must have YAML frontmatter with `---` delimiters

## Example: Complete Plugin

```
plugins/entrepreneurship/idea-validation/
├── .claude-plugin/
│   └── plugin.json
├── agents/
│   ├── idea-validator.md
│   ├── market-researcher.md
│   └── customer-interviewer.md
└── commands/
    ├── validate-idea.md
    ├── market-size.md
    └── customer-persona.md
```

**plugin.json**:
```json
{
  "name": "idea-validation",
  "displayName": "Startup Idea Validation Framework",
  "description": "Validate startup ideas with market research, customer discovery, and competitive analysis",
  "version": "1.0.0",
  "author": {
    "name": "Sandro Ponticelli",
    "github": "sponticelli"
  },
  "category": "entrepreneurship",
  "tags": ["startup", "validation", "market-research", "lean-startup"],
  "agents": [
    "./agents/idea-validator.md",
    "./agents/market-researcher.md",
    "./agents/customer-interviewer.md"
  ],
  "commands": [
    "./commands/validate-idea.md",
    "./commands/market-size.md",
    "./commands/customer-persona.md"
  ]
}
```

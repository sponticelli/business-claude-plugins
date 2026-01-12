# Plugin Submission Checklist

Use this checklist before submitting your plugin to ensure it meets all requirements.

## Structure Validation

- [ ] Plugin folder exists in correct category (`plugins/[category]/[plugin-name]/`)
- [ ] `.claude-plugin/plugin.json` exists and contains valid JSON
- [ ] `agents/` folder contains at least one agent file
- [ ] `commands/` folder contains at least one command file
- [ ] All file names use kebab-case (e.g., `my-agent.md`, not `myAgent.md`)

## Manifest Validation (`plugin.json`)

- [ ] `name` matches folder name (kebab-case)
- [ ] `displayName` is human-readable
- [ ] `version` follows semver (e.g., `1.0.0`)
- [ ] `description` is clear and under 200 characters
- [ ] `author.name` is your name
- [ ] `author.github` is your GitHub username
- [ ] `category` matches parent folder name
- [ ] `tags` array includes 3-5 relevant search tags
- [ ] `agents` array lists all agent files with correct paths
- [ ] `commands` array lists all command files with correct paths

## Agent File Validation

For each agent file:

- [ ] YAML frontmatter includes `name` and `description`
- [ ] `name` matches filename (without `.md` extension)
- [ ] `description` starts with action verb and includes "Use when" trigger
- [ ] Content has clear section headers
- [ ] Includes verification checklist
- [ ] References related agents (if applicable)

## Command File Validation

For each command file:

- [ ] YAML frontmatter includes `name` and `description`
- [ ] `name` matches filename (without `.md` extension)
- [ ] Includes clear process steps
- [ ] Defines expected output format
- [ ] Includes at least one example
- [ ] Ends with "Apply immediately" instruction

## Documentation Quality

- [ ] All placeholder text (e.g., `{{}}`) has been replaced
- [ ] Grammar and spelling are correct
- [ ] Instructions are clear and actionable
- [ ] Examples are realistic and helpful

## Testing

- [ ] Tested locally with Claude Code
- [ ] All agents can be invoked correctly
- [ ] All commands produce expected output
- [ ] No errors or warnings during execution

## Registry Update

- [ ] Added plugin entry to `.claude-plugin/marketplace.json`
- [ ] Plugin entry includes all required fields
- [ ] Category's `plugins` array includes the plugin ID

---

## Quick Commands

Validate JSON syntax:
```bash
cat plugins/[category]/[plugin-name]/.claude-plugin/plugin.json | python -m json.tool
```

Check file structure:
```bash
ls -la plugins/[category]/[plugin-name]/
ls -la plugins/[category]/[plugin-name]/agents/
ls -la plugins/[category]/[plugin-name]/commands/
```

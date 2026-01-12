# Contributing to Business Claude Plugins

Thank you for your interest in contributing! This guide will help you add your own plugins to the marketplace.

## Types of Contributions

- **New Plugin**: Add a completely new plugin to a category
- **Plugin Enhancement**: Improve an existing plugin with new agents or commands
- **Bug Fix**: Fix issues in existing plugins
- **Documentation**: Improve docs or add examples

## Quick Start

1. **Fork** this repository
2. **Clone** your fork locally
3. **Create a branch**: `git checkout -b plugin/my-new-plugin`
4. **Copy the template**: `cp -r templates/plugin-template plugins/[category]/[plugin-name]`
5. **Build your plugin** (see [Plugin Guide](PLUGIN_GUIDE.md))
6. **Test locally** with Claude Code
7. **Submit a Pull Request**

## Plugin Submission Process

### Step 1: Choose a Category

Pick the most appropriate category for your plugin:

| Category | Focus Area |
|----------|------------|
| `entrepreneurship` | Starting businesses, validation, planning |
| `sales` | Revenue generation, lead management, closing |
| `marketing` | Growth, branding, content, campaigns |
| `operations` | Processes, systems, efficiency |
| `finance` | Budgeting, accounting, fundraising |
| `strategy` | Planning, competitive analysis |
| `leadership` | Management, culture, hiring |
| `legal` | Compliance, contracts, IP |

### Step 2: Create Your Plugin

1. Copy the template:
   ```bash
   cp -r templates/plugin-template plugins/[category]/[your-plugin-name]
   ```

2. Rename the template files:
   ```bash
   mv .claude-plugin/plugin.json.template .claude-plugin/plugin.json
   mv agents/agent-template.md agents/your-agent.md
   mv commands/command-template.md commands/your-command.md
   ```

3. Fill in your content following the [Plugin Guide](PLUGIN_GUIDE.md)

### Step 3: Update the Registry

Add your plugin to `.claude-plugin/marketplace.json`:

```json
{
  "plugins": [
    {
      "id": "your-plugin-name",
      "name": "Your Plugin Display Name",
      "path": "plugins/[category]/your-plugin-name",
      "category": "[category]",
      "description": "Brief description",
      "version": "1.0.0",
      "author": {
        "name": "Your Name",
        "github": "your-username"
      },
      "agents": 1,
      "commands": 1,
      "tags": ["tag1", "tag2"]
    }
  ]
}
```

Also add your plugin ID to the category's `plugins` array.

### Step 4: Validate Your Plugin

Run through the [Submission Checklist](../templates/CHECKLIST.md) to ensure everything is correct.

### Step 5: Submit Your PR

1. Commit your changes:
   ```bash
   git add .
   git commit -m "feat: add [plugin-name] plugin"
   ```

2. Push to your fork:
   ```bash
   git push origin plugin/my-new-plugin
   ```

3. Open a Pull Request against `main`

4. Fill out the PR template completely

## Review Process

1. **Automated checks** validate JSON syntax and structure
2. **Maintainer review** checks quality and usefulness
3. **Feedback** may be provided for improvements
4. **Merge** once approved

### Review Criteria

- Does the plugin serve a clear business purpose?
- Is the documentation clear and complete?
- Are examples helpful and realistic?
- Does it follow the schema correctly?
- Has it been tested with Claude Code?

## Code of Conduct

- Be respectful and constructive
- Focus on quality over quantity
- Help others learn and improve
- Give credit where due

## Getting Help

- Open an [Issue](https://github.com/sponticelli/business-claude-plugins/issues) for questions
- Check existing plugins for examples
- Review the [Plugin Guide](PLUGIN_GUIDE.md) for detailed instructions

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

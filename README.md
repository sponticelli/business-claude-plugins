# Business Claude Plugins

A community-driven marketplace of Claude Code plugins for business development and entrepreneurship.

**13 plugins** | **13 specialized agents** | **60 slash commands**

## Installation

Add this marketplace to Claude Code:

```bash
claude marketplace add sponticelli/business-claude-plugins
```

Install a specific plugin:

```bash
claude plugin install idea-validation
```

## Available Plugins

### Entrepreneurship

| Plugin | Description | Commands |
|--------|-------------|----------|
| idea-validation | 33-metric startup validation framework | 6 |
| pitch-deck-builder | Investor pitch deck creation | 3 |
| business-model-canvas | Business Model Canvas framework | 4 |

### Sales & Revenue

| Plugin | Description | Commands |
|--------|-------------|----------|
| sales-playbook | Sales processes and scripts | 4 |
| pricing-strategy | Value-based pricing analysis | 3 |

### Marketing & Growth

| Plugin | Description | Commands |
|--------|-------------|----------|
| content-strategy | Content marketing with SEO | 4 |
| landing-page-copy | High-converting copy | 3 |

### Finance & Accounting

| Plugin | Description | Commands |
|--------|-------------|----------|
| financial-model | Financial projections & unit economics | 5 |
| fundraising-prep | Due diligence & cap tables | 4 |

### Operations

| Plugin | Description | Commands |
|--------|-------------|----------|
| operations-management | Process optimization, project management, productivity | 6 |

### Business Strategy

| Plugin | Description | Commands |
|--------|-------------|----------|
| strategic-planning | Competitive analysis, growth strategy, OKRs | 6 |

### Leadership & Management

| Plugin | Description | Commands |
|--------|-------------|----------|
| leadership-management | Hiring, performance reviews, executive communication | 6 |

### Legal & Compliance

| Plugin | Description | Commands |
|--------|-------------|----------|
| legal-compliance | Startup legal, compliance, contracts, risk management | 6 |

## Quick Start

After installing a plugin, use its commands directly in Claude Code:

```
> /validate-idea My SaaS idea for project management
```

```
> /create-pitch-deck B2B marketplace for freelance developers
```

```
> /competitive-analysis Our product vs main competitors
```

```
> /hiring-scorecard Senior Product Manager role
```

```
> /compliance-assessment SOC 2 readiness for our SaaS
```

Or let Claude automatically use the appropriate agent based on your request:

```
> I want to validate my startup idea for a B2B invoicing platform
```

## Documentation

- [Usage Guide](docs/USAGE_GUIDE.md) - How to use plugins effectively
- [Contributing](docs/CONTRIBUTING.md) - How to contribute plugins
- [Plugin Guide](docs/PLUGIN_GUIDE.md) - How to create your own plugins
- [Schema Reference](docs/SCHEMA.md) - Technical schema documentation

## Contributing

We welcome community contributions! See our [Contributing Guide](docs/CONTRIBUTING.md) to get started.

Quick steps:
1. Fork this repository
2. Copy `templates/plugin-template/` to `plugins/[category]/[your-plugin]/`
3. Fill in your plugin content
4. Submit a Pull Request

## License

MIT License - see [LICENSE](LICENSE) for details.

## Author

Created by [Sandro Ponticelli](https://github.com/sponticelli)

---
name: analyze-market-strategy
description: Analyze market positioning and competitive landscape for a startup idea (6 metrics)
---

# Analyze Market Strategy

Quick analysis of market positioning, competitive landscape, and go-to-market approach using 6 key metrics from the Market Strategy dimension.

## Usage

```
/analyze-market-strategy [your startup idea]
```

## Metrics Evaluated

| # | Metric | Question |
|---|--------|----------|
| 1.1 | Marketing Research | How much effort to define product/price the market will accept? |
| 1.2 | Promotion Cost | Are promotion costs in line with expected returns? |
| 1.3 | Distribution | How difficult to access distribution channels? |
| 1.4 | Legality | Does it meet legal requirements and avoid liability? |
| 1.5 | Existing Competition | Will competition make entry difficult? |
| 1.6 | New Competition | Is it likely to face new competition threats? |

## Output Format

```markdown
# Market Strategy Analysis

## Idea Summary
[Brief description]

## Dimension Score
**[XX.X]%** (X/30 points)

## Metric Breakdown

### 1.1 Marketing Research
**Score**: X/5
**Assessment**: [Explanation]
**Improve**: [Suggestions]

[Repeat for all 6 metrics]

## Key Insights

### Strengths
- [Top strength]
- [Second strength]

### Concerns
- [Top concern]
- [Second concern]

### Priority Actions
1. [Most important action]
2. [Second action]
3. [Third action]

## Next Steps
For complete validation, run `/validate-idea` to evaluate all 33 metrics.
```

## Example

**Input**: `/analyze-market-strategy B2B SaaS for automated invoice processing`

**Output**: Analysis of market positioning including:
- Existing market data availability
- Customer acquisition cost projections
- Distribution channel options
- Regulatory considerations
- Competitive landscape assessment
- Barriers to entry evaluation

---

Apply immediately to user's input.

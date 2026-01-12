---
name: analyze-market-viability
description: Analyze market size, growth potential, and demand dynamics for a startup idea (5 metrics)
---

# Analyze Market Viability

Quick analysis of market opportunity, size, and demand dynamics using 5 key metrics from the Market Viability dimension.

## Usage

```
/analyze-market-viability [your startup idea]
```

## Metrics Evaluated

| # | Metric | Question |
|---|--------|----------|
| 2.1 | Need | Does it solve a problem or satisfy a desire? |
| 2.2 | Potential Market | How large is the total addressable market? |
| 2.3 | Trend of Demand | Is demand increasing, stable, or decreasing? |
| 2.4 | Duration of Demand | Is demand expected to be long-term? |
| 2.5 | Demand Predictability | How accurately can sales be predicted? |

## Output Format

```markdown
# Market Viability Analysis

## Idea Summary
[Brief description]

## Dimension Score
**[XX.X]%** (X/25 points)

## Metric Breakdown

### 2.1 Need
**Score**: X/5
**Assessment**: [Explanation]
**Improve**: [Suggestions]

[Repeat for all 5 metrics]

## Market Sizing

### TAM (Total Addressable Market)
[Estimate with reasoning]

### SAM (Serviceable Addressable Market)
[Estimate with reasoning]

### SOM (Serviceable Obtainable Market)
[Estimate with reasoning]

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

**Input**: `/analyze-market-viability Plant-based meal kit delivery service`

**Output**: Analysis of market opportunity including:
- Problem severity and customer need
- Market size estimates (TAM/SAM/SOM)
- Growth trends in plant-based and meal kit markets
- Demand longevity assessment
- Sales predictability evaluation

---

Apply immediately to user's input.

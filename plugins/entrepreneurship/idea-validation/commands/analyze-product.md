---
name: analyze-product
description: Analyze product-market fit and value proposition for a startup idea (8 metrics)
---

# Analyze Product Viability

Quick analysis of product-market fit, feature relevance, and user value proposition using 8 key metrics from the Product Viability dimension.

## Usage

```
/analyze-product [your startup idea]
```

## Metrics Evaluated

| # | Metric | Question |
|---|--------|----------|
| 3.1 | Product Line Potential | Can it lead to other profitable products? |
| 3.2 | Social Benefits | Will it benefit society overall? |
| 3.3 | Compatibility | Is it aligned with current behaviors? |
| 3.4 | Learning | How easy is it to learn to use? |
| 3.5 | Visibility | How obvious are the advantages? |
| 3.6 | Function | Does it work better than alternatives? |
| 3.7 | Durability | Will users return? Usage frequency? |
| 3.8 | Price | Does it have a price advantage? |

## Output Format

```markdown
# Product Viability Analysis

## Idea Summary
[Brief description]

## Dimension Score
**[XX.X]%** (X/40 points)

## Metric Breakdown

### 3.1 Product Line Potential
**Score**: X/5
**Assessment**: [Explanation]
**Improve**: [Suggestions]

[Repeat for all 8 metrics]

## Product-Market Fit Assessment

### Value Proposition
[Clear statement of value]

### User Experience
[Ease of adoption and use]

### Competitive Position
[How it compares to alternatives]

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

**Input**: `/analyze-product AI-powered personal finance app for Gen Z`

**Output**: Analysis of product viability including:
- Platform and expansion potential
- Social impact assessment
- Behavioral compatibility with target users
- Learning curve evaluation
- Value proposition clarity
- Functional advantages over alternatives
- Expected engagement and retention
- Pricing strategy assessment

---

Apply immediately to user's input.

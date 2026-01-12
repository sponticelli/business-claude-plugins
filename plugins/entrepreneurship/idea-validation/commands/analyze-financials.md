---
name: analyze-financials
description: Analyze risk and financial viability for a startup idea (8 metrics)
---

# Analyze Risk & Financial Viability

Quick analysis of financial sustainability, risk factors, and economic feasibility using 8 key metrics from the Risk and Financial Viability dimension.

## Usage

```
/analyze-financials [your startup idea]
```

## Metrics Evaluated

| # | Metric | Question |
|---|--------|----------|
| 4.1 | Development Risk | What uncertainty exists to market readiness? |
| 4.2 | Dependence | How much depends on external parties? |
| 4.3 | Protection | Can you protect the innovation (IP, patents)? |
| 4.4 | Size of Investment | Is the required investment achievable? |
| 4.5 | Cost of Production | Can you produce at reasonable cost? |
| 4.6 | Potential Sales | Can sales volume justify the project? |
| 4.7 | Payback Period | How quickly will investment pay off? |
| 4.8 | Profitability | Will returns exceed other opportunities? |

## Output Format

```markdown
# Risk & Financial Viability Analysis

## Idea Summary
[Brief description]

## Dimension Score
**[XX.X]%** (X/40 points)

## Metric Breakdown

### 4.1 Development Risk
**Score**: X/5
**Assessment**: [Explanation]
**Improve**: [Suggestions]

[Repeat for all 8 metrics]

## Financial Summary

### Investment Required
[Estimated range with breakdown]

### Unit Economics
- Customer Acquisition Cost (CAC): [Estimate]
- Lifetime Value (LTV): [Estimate]
- LTV:CAC Ratio: [Calculation]

### Path to Profitability
[Timeline and milestones]

## Risk Assessment

### Key Dependencies
[External parties and platform risks]

### Defensibility
[IP protection and competitive moats]

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

**Input**: `/analyze-financials Marketplace for freelance legal services`

**Output**: Analysis of financial viability including:
- Development stage and remaining risks
- Platform dependencies (payment, identity, etc.)
- IP protection opportunities
- Funding requirements and sources
- Cost structure analysis
- Revenue potential assessment
- Payback timeline
- Profitability projections

---

Apply immediately to user's input.

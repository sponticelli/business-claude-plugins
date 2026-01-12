---
name: scenario-analysis
description: Model best/base/worst case projections
---

# Scenario Analysis

Create best case, base case, and worst case financial projections to understand the range of outcomes.

## Usage

```
/scenario-analysis [describe your business, current metrics, and key uncertainties]
```

## Output Format

```markdown
# Scenario Analysis: [Company]

## Scenario Summary

| Metric (Month 12) | Worst | Base | Best |
|-------------------|-------|------|------|
| MRR | $[X] | $[X] | $[X] |
| Customers | [X] | [X] | [X] |
| Burn Rate | $[X] | $[X] | $[X] |
| Runway | [X] mo | [X] mo | [X] mo |
| Cash Position | $[X] | $[X] | $[X] |

---

## Scenario Assumptions

### Base Case: "Things Go as Planned"

**Probability**: ~50%
**Description**: Current trajectory continues with modest improvements

| Assumption | Base Value | Rationale |
|------------|------------|-----------|
| Customer Growth | [X]% MoM | Historical average |
| Churn Rate | [X]%/month | Current rate |
| ARPU | $[X] | Current pricing |
| Expense Growth | [X]%/month | Planned hiring |
| CAC | $[X] | Current efficiency |

### Best Case: "Things Go Better Than Expected"

**Probability**: ~25%
**Description**: Key wins accelerate growth

| Assumption | Best Value | What Drives This |
|------------|------------|------------------|
| Customer Growth | [X]% MoM | [Specific catalyst] |
| Churn Rate | [X]%/month | [Product improvement] |
| ARPU | $[X] | [Upsell success] |
| Expense Growth | [X]%/month | [Efficiency gains] |
| CAC | $[X] | [Channel optimization] |

**Key Catalysts**:
1. [Specific event/win that could trigger best case]
2. [Specific event/win]
3. [Specific event/win]

### Worst Case: "Things Go Wrong"

**Probability**: ~25%
**Description**: Key risks materialize

| Assumption | Worst Value | What Causes This |
|------------|-------------|------------------|
| Customer Growth | [X]% MoM | [Risk factor] |
| Churn Rate | [X]%/month | [Risk factor] |
| ARPU | $[X] | [Risk factor] |
| Expense Growth | [X]%/month | [Requirement] |
| CAC | $[X] | [Risk factor] |

**Key Risks**:
1. [Specific risk that could trigger worst case]
2. [Specific risk]
3. [Specific risk]

---

## Detailed Projections

### Revenue Projections

| Month | Worst MRR | Base MRR | Best MRR |
|-------|-----------|----------|----------|
| 1 | $[X] | $[X] | $[X] |
| 3 | $[X] | $[X] | $[X] |
| 6 | $[X] | $[X] | $[X] |
| 9 | $[X] | $[X] | $[X] |
| 12 | $[X] | $[X] | $[X] |

### Customer Projections

| Month | Worst | Base | Best |
|-------|-------|------|------|
| 1 | [X] | [X] | [X] |
| 3 | [X] | [X] | [X] |
| 6 | [X] | [X] | [X] |
| 9 | [X] | [X] | [X] |
| 12 | [X] | [X] | [X] |

### Expense Projections

| Month | Worst | Base | Best |
|-------|-------|------|------|
| 1 | $[X] | $[X] | $[X] |
| 3 | $[X] | $[X] | $[X] |
| 6 | $[X] | $[X] | $[X] |
| 9 | $[X] | $[X] | $[X] |
| 12 | $[X] | $[X] | $[X] |

### Cash Position

| Month | Worst Cash | Base Cash | Best Cash |
|-------|------------|-----------|-----------|
| 1 | $[X] | $[X] | $[X] |
| 3 | $[X] | $[X] | $[X] |
| 6 | $[X] | $[X] | $[X] |
| 9 | $[X] | $[X] | $[X] |
| 12 | $[X] | $[X] | $[X] |

---

## Key Metrics by Scenario

### Month 12 Unit Economics

| Metric | Worst | Base | Best |
|--------|-------|------|------|
| LTV | $[X] | $[X] | $[X] |
| CAC | $[X] | $[X] | $[X] |
| LTV:CAC | [X]:1 | [X]:1 | [X]:1 |
| Payback | [X] mo | [X] mo | [X] mo |
| Gross Margin | [X]% | [X]% | [X]% |

### Growth Metrics

| Metric | Worst | Base | Best |
|--------|-------|------|------|
| YoY Revenue Growth | [X]% | [X]% | [X]% |
| Net Revenue Retention | [X]% | [X]% | [X]% |
| Quick Ratio | [X] | [X] | [X] |

---

## Milestone Timeline

### When Do We Hit Key Milestones?

| Milestone | Worst | Base | Best |
|-----------|-------|------|------|
| $50K MRR | Month [X] | Month [X] | Month [X] |
| $100K MRR | Month [X] | Month [X] | Month [X] |
| Profitability | Month [X] | Month [X] | Month [X] |
| 100 customers | Month [X] | Month [X] | Month [X] |
| 500 customers | Month [X] | Month [X] | Month [X] |

---

## Funding Implications

### Runway by Scenario

| Scenario | Runway (No Raise) | Additional Funding Needed |
|----------|-------------------|---------------------------|
| Worst | [X] months | $[X] to reach [milestone] |
| Base | [X] months | $[X] to reach [milestone] |
| Best | [X] months | $[X] or self-sustaining |

### When to Raise

| Scenario | Start Raising | Close By | Amount Needed |
|----------|--------------|----------|---------------|
| Worst | Month [X] | Month [X] | $[X] |
| Base | Month [X] | Month [X] | $[X] |
| Best | Month [X] | Month [X] | $[X] |

---

## Scenario Visualization

### Revenue Range
```
Month 12 MRR Range:

Worst  ├────────────────────┤ $[X]
Base   ├───────────────────────────────────┤ $[X]
Best   ├──────────────────────────────────────────────────┤ $[X]
```

### Customer Range
```
Month 12 Customers:

Worst  ├────────────────────┤ [X]
Base   ├───────────────────────────────────┤ [X]
Best   ├──────────────────────────────────────────────────┤ [X]
```

---

## Contingency Plans

### If Worst Case Materializes

**Early Warning Signs**:
1. [Metric] drops below [threshold]
2. [Metric] drops below [threshold]
3. [Metric] drops below [threshold]

**Actions to Take**:
1. [Cost reduction measure]
2. [Revenue acceleration tactic]
3. [Strategic pivot option]

### If Best Case Materializes

**Signals We're on Track**:
1. [Metric] exceeds [threshold]
2. [Metric] exceeds [threshold]

**Actions to Take**:
1. [Investment acceleration]
2. [Hiring ramp-up]
3. [Market expansion]

---

## Probability-Weighted Outcome

### Expected Value Calculation

| Outcome | Probability | MRR (M12) | Weighted |
|---------|-------------|-----------|----------|
| Worst | 25% | $[X] | $[X] |
| Base | 50% | $[X] | $[X] |
| Best | 25% | $[X] | $[X] |
| **Expected** | 100% | — | **$[X]** |

---

## Decision Framework

### Key Questions Answered

**What's our downside?**
[Worst case summary and impact]

**What's our likely outcome?**
[Base case summary and path]

**What's our upside?**
[Best case summary and requirements]

**What would change our trajectory?**
1. [Factor that would move us toward best]
2. [Factor that would move us toward worst]
```

---

Apply immediately to user's input.

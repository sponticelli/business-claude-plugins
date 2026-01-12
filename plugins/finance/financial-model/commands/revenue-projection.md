---
name: revenue-projection
description: Create a bottom-up revenue forecast model
---

# Revenue Projection

Create a bottom-up revenue projection based on customer acquisition and retention assumptions.

## Usage

```
/revenue-projection [describe your business model, pricing, current metrics if any]
```

## Output Format

```markdown
# Revenue Projection: [Company/Product]

## Model Overview

**Business Model**: [SaaS/Transactional/Marketplace/etc.]
**Pricing Model**: [Per seat/Usage/Flat/etc.]
**Projection Period**: [12/24/36 months]
**Model Type**: Bottom-up

---

## Key Assumptions

### Customer Acquisition
| Assumption | Value | Rationale |
|------------|-------|-----------|
| Starting customers | [X] | Current base |
| Month 1 new customers | [X] | [Based on...] |
| New customer growth rate | [X]% MoM | [Based on...] |

### Pricing
| Assumption | Value | Rationale |
|------------|-------|-----------|
| Average Revenue Per User | $[X]/mo | [Tier mix] |
| Price increase (annual) | [X]% | [If any] |

### Retention & Expansion
| Assumption | Value | Rationale |
|------------|-------|-----------|
| Monthly churn rate | [X]% | [Industry/historical] |
| Monthly expansion rate | [X]% | [Upsell/upgrade] |
| Net Revenue Retention | [X]% | [Calculated] |

---

## 12-Month Revenue Projection

| Month | New Cust | Churned | Ending Cust | MRR | ARR |
|-------|----------|---------|-------------|-----|-----|
| 1 | [X] | [X] | [X] | $[X] | $[X] |
| 2 | [X] | [X] | [X] | $[X] | $[X] |
| 3 | [X] | [X] | [X] | $[X] | $[X] |
| 4 | [X] | [X] | [X] | $[X] | $[X] |
| 5 | [X] | [X] | [X] | $[X] | $[X] |
| 6 | [X] | [X] | [X] | $[X] | $[X] |
| 7 | [X] | [X] | [X] | $[X] | $[X] |
| 8 | [X] | [X] | [X] | $[X] | $[X] |
| 9 | [X] | [X] | [X] | $[X] | $[X] |
| 10 | [X] | [X] | [X] | $[X] | $[X] |
| 11 | [X] | [X] | [X] | $[X] | $[X] |
| 12 | [X] | [X] | [X] | $[X] | $[X] |

---

## MRR Waterfall

### Monthly MRR Components

| Month | New MRR | Expansion | Contraction | Churned | Net New | Ending MRR |
|-------|---------|-----------|-------------|---------|---------|------------|
| 1 | $[X] | $[X] | $[X] | $[X] | $[X] | $[X] |
| 3 | $[X] | $[X] | $[X] | $[X] | $[X] | $[X] |
| 6 | $[X] | $[X] | $[X] | $[X] | $[X] | $[X] |
| 12 | $[X] | $[X] | $[X] | $[X] | $[X] | $[X] |

---

## Growth Summary

### Year 1 Totals
- **Ending MRR**: $[X]
- **Ending ARR**: $[X]
- **Total Customers**: [X]
- **Total Revenue**: $[X]

### Growth Rates
- **MRR Growth (12 months)**: [X]%
- **Customer Growth (12 months)**: [X]%
- **Average MoM Growth**: [X]%

---

## Revenue by Segment (If Applicable)

| Segment | Customers | ARPU | MRR | % of Total |
|---------|-----------|------|-----|------------|
| [Tier 1] | [X] | $[X] | $[X] | [X]% |
| [Tier 2] | [X] | $[X] | $[X] | [X]% |
| [Tier 3] | [X] | $[X] | $[X] | [X]% |

---

## Cohort Analysis

### Retention by Cohort
| Cohort | M1 | M3 | M6 | M12 |
|--------|-----|-----|-----|------|
| Jan | 100% | [X]% | [X]% | [X]% |
| Apr | 100% | [X]% | [X]% | — |
| Jul | 100% | [X]% | — | — |
| Oct | 100% | — | — | — |

---

## Sensitivity Analysis

### Revenue at Different Churn Rates
| Churn Rate | Month 12 MRR | Difference |
|------------|--------------|------------|
| [X]% (base) | $[X] | — |
| [X-2]% | $[X] | +$[X] |
| [X+2]% | $[X] | -$[X] |

### Revenue at Different Growth Rates
| Growth Rate | Month 12 MRR | Difference |
|-------------|--------------|------------|
| [X]% (base) | $[X] | — |
| [X-5]% | $[X] | -$[X] |
| [X+5]% | $[X] | +$[X] |

---

## Key Milestones

| Milestone | Target | Expected Date |
|-----------|--------|---------------|
| $10K MRR | — | Month [X] |
| $50K MRR | — | Month [X] |
| $100K MRR | — | Month [X] |
| 100 customers | — | Month [X] |
| 500 customers | — | Month [X] |

---

## Risks to Projection

| Risk | Impact | Likelihood | Mitigation |
|------|--------|------------|------------|
| Churn higher than expected | [High/Med/Low] | [H/M/L] | [Action] |
| Acquisition slows | [High/Med/Low] | [H/M/L] | [Action] |
| ARPU compression | [High/Med/Low] | [H/M/L] | [Action] |

---

## Data Needed to Refine

- [ ] Historical churn data (if available)
- [ ] Channel-specific conversion rates
- [ ] Actual sales capacity/productivity
- [ ] Seasonal patterns
```

---

Apply immediately to user's input.

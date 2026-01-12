---
name: runway-calculator
description: Calculate burn rate and runway based on current financials
---

# Runway Calculator

Calculate your burn rate and runway based on current cash position and expenses.

## Usage

```
/runway-calculator [provide cash balance, monthly revenue, and monthly expenses]
```

## Output Format

```markdown
# Runway Calculator: [Company]

## Summary

| Metric | Value |
|--------|-------|
| Current Cash | $[X] |
| Monthly Burn | $[X] |
| Runway | [X] months |
| Zero Cash Date | [Month Year] |

---

## Cash Position

### Current State
| Item | Amount |
|------|--------|
| Cash in Bank | $[X] |
| Receivables (expected) | $[X] |
| **Available Cash** | **$[X]** |

### Committed Obligations
| Item | Amount |
|------|--------|
| Payables Due | $[X] |
| Upcoming Large Expenses | $[X] |
| **Net Available** | **$[X]** |

---

## Monthly Burn Analysis

### Revenue
| Source | Monthly Amount |
|--------|---------------|
| Recurring Revenue | $[X] |
| One-time Revenue | $[X] |
| Other Income | $[X] |
| **Total Revenue** | **$[X]** |

### Expenses
| Category | Monthly Amount | % of Total |
|----------|---------------|------------|
| Salaries & Benefits | $[X] | [X]% |
| Contractors | $[X] | [X]% |
| Software & Tools | $[X] | [X]% |
| Hosting/Infrastructure | $[X] | [X]% |
| Office/Rent | $[X] | [X]% |
| Marketing/Ads | $[X] | [X]% |
| Legal/Accounting | $[X] | [X]% |
| Insurance | $[X] | [X]% |
| Travel | $[X] | [X]% |
| Other | $[X] | [X]% |
| **Total Expenses** | **$[X]** | 100% |

### Burn Calculation
| Metric | Calculation | Amount |
|--------|-------------|--------|
| Gross Burn | Total Expenses | $[X] |
| Net Burn | Expenses - Revenue | $[X] |

---

## Runway Calculation

### Standard Runway
```
Runway = Cash Balance / Monthly Net Burn
Runway = $[X] / $[X] = [X] months
```

### With Growth Adjustment
Assuming [X]% MoM revenue growth and [X]% expense growth:

| Month | Revenue | Expenses | Net Burn | Cash Balance |
|-------|---------|----------|----------|--------------|
| Current | $[X] | $[X] | $[X] | $[X] |
| +3 | $[X] | $[X] | $[X] | $[X] |
| +6 | $[X] | $[X] | $[X] | $[X] |
| +9 | $[X] | $[X] | $[X] | $[X] |
| +12 | $[X] | $[X] | $[X] | $[X] |

**Adjusted Runway**: [X] months

---

## Runway Scenarios

### Scenario 1: No Changes (Current Path)
- Runway: **[X] months**
- Zero cash: **[Month Year]**

### Scenario 2: Cut 20% Expenses
| Change | Before | After |
|--------|--------|-------|
| Monthly Expenses | $[X] | $[X] |
| Net Burn | $[X] | $[X] |
| Runway | [X] mo | [X] mo |
| **Extension** | — | **+[X] months** |

### Scenario 3: Grow Revenue 50% Faster
| Change | Before | After |
|--------|--------|-------|
| Revenue Growth | [X]% | [X]% |
| Month 6 Revenue | $[X] | $[X] |
| Runway | [X] mo | [X] mo |
| **Extension** | — | **+[X] months** |

### Scenario 4: Bridge Funding ($[X])
| Change | Before | After |
|--------|--------|-------|
| Cash | $[X] | $[X] |
| Runway | [X] mo | [X] mo |
| **Extension** | — | **+[X] months** |

---

## Critical Dates

| Milestone | Date | Cash Remaining |
|-----------|------|----------------|
| Today | [Date] | $[X] |
| 6 months runway left | [Date] | $[X] |
| 3 months runway left | [Date] | $[X] |
| Start fundraising | [Date] | $[X] |
| Zero cash | [Date] | $0 |

**Recommendation**: Start fundraising when you have [X] months runway to allow [X] months for the process.

---

## Expense Breakdown Visualization

```
Salaries     ████████████████████░░░░ 60%
Software     ██████░░░░░░░░░░░░░░░░░░ 15%
Marketing    ████░░░░░░░░░░░░░░░░░░░░ 10%
Office       ██░░░░░░░░░░░░░░░░░░░░░░  5%
Other        ████░░░░░░░░░░░░░░░░░░░░ 10%
```

---

## Cost Reduction Opportunities

### Quick Wins (Implement this week)
| Item | Current | Reduced | Monthly Savings |
|------|---------|---------|-----------------|
| [Software tool] | $[X] | $[Y] | $[Z] |
| [Service] | $[X] | $[Y] | $[Z] |
| **Total** | — | — | **$[X]** |

### Medium-Term (Implement this month)
| Item | Current | Reduced | Monthly Savings |
|------|---------|---------|-----------------|
| [Expense category] | $[X] | $[Y] | $[Z] |
| [Expense category] | $[X] | $[Y] | $[Z] |
| **Total** | — | — | **$[X]** |

### Runway Impact of Reductions
| Reduction Level | New Burn | New Runway | Extension |
|-----------------|----------|------------|-----------|
| Quick wins only | $[X] | [X] mo | +[X] mo |
| + Medium-term | $[X] | [X] mo | +[X] mo |
| Emergency cuts | $[X] | [X] mo | +[X] mo |

---

## Key Metrics to Track

### Weekly
- [ ] Cash balance
- [ ] Accounts receivable
- [ ] Large upcoming expenses

### Monthly
- [ ] Actual vs. projected burn
- [ ] Revenue trend
- [ ] Updated runway calculation

---

## Alerts & Thresholds

| Alert Level | Runway | Action |
|-------------|--------|--------|
| 🟢 Green | >12 months | Continue as planned |
| 🟡 Yellow | 6-12 months | Start fundraising prep |
| 🟠 Orange | 3-6 months | Active fundraising or cuts |
| 🔴 Red | <3 months | Emergency measures |

**Current Status**: [Status with color]
```

---

Apply immediately to user's input.

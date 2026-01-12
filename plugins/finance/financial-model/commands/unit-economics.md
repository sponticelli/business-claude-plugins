---
name: unit-economics
description: Calculate CAC, LTV, margins, and payback period
---

# Unit Economics

Calculate and analyze unit economics including CAC, LTV, margins, and payback period.

## Usage

```
/unit-economics [provide pricing, costs, acquisition spend, and retention data]
```

## Output Format

```markdown
# Unit Economics Analysis: [Company/Product]

## Summary Metrics

| Metric | Value | Benchmark | Status |
|--------|-------|-----------|--------|
| LTV | $[X] | — | — |
| CAC | $[X] | — | — |
| LTV:CAC | [X]:1 | >3:1 | 🟢/🟡/🔴 |
| CAC Payback | [X] months | <12 mo | 🟢/🟡/🔴 |
| Gross Margin | [X]% | >70% | 🟢/🟡/🔴 |

---

## Customer Acquisition Cost (CAC)

### CAC Calculation

**Time Period**: [Month/Quarter]

| Cost Component | Amount |
|----------------|--------|
| Paid Advertising | $[X] |
| Sales Salaries | $[X] |
| Sales Commissions | $[X] |
| Marketing Salaries | $[X] |
| Marketing Tools | $[X] |
| Events/Conferences | $[X] |
| Content/Creative | $[X] |
| **Total S&M Spend** | **$[X]** |

| Acquisition Metric | Value |
|-------------------|-------|
| New Customers | [X] |
| **CAC** | **$[X]** |

### CAC by Channel (If Known)
| Channel | Spend | Customers | CAC |
|---------|-------|-----------|-----|
| Paid Search | $[X] | [X] | $[X] |
| Paid Social | $[X] | [X] | $[X] |
| Content/SEO | $[X] | [X] | $[X] |
| Sales Team | $[X] | [X] | $[X] |
| Referrals | $[X] | [X] | $[X] |

### Blended vs. Paid CAC
- **Blended CAC**: $[X] (all channels)
- **Paid CAC**: $[X] (paid only)
- **Organic %**: [X]% of new customers

---

## Lifetime Value (LTV)

### LTV Calculation Method 1: Churn-Based

```
LTV = (ARPU × Gross Margin) / Monthly Churn Rate
```

| Input | Value |
|-------|-------|
| ARPU (Monthly) | $[X] |
| Gross Margin | [X]% |
| Monthly Churn Rate | [X]% |
| **LTV** | **$[X]** |

### LTV Calculation Method 2: Lifetime-Based

```
LTV = ARPU × Gross Margin × Average Customer Lifetime
```

| Input | Value |
|-------|-------|
| ARPU (Monthly) | $[X] |
| Gross Margin | [X]% |
| Avg. Lifetime (months) | [X] |
| **LTV** | **$[X]** |

### LTV by Segment
| Segment | ARPU | Churn | Lifetime | LTV |
|---------|------|-------|----------|-----|
| [Segment 1] | $[X] | [X]% | [X] mo | $[X] |
| [Segment 2] | $[X] | [X]% | [X] mo | $[X] |
| [Segment 3] | $[X] | [X]% | [X] mo | $[X] |

---

## Gross Margin

### Gross Margin Calculation

| Revenue | Amount | % of Revenue |
|---------|--------|--------------|
| Total Revenue | $[X] | 100% |

| COGS Component | Amount | % of Revenue |
|----------------|--------|--------------|
| Hosting/Infrastructure | $[X] | [X]% |
| Payment Processing | $[X] | [X]% |
| Customer Support | $[X] | [X]% |
| Third-Party Services | $[X] | [X]% |
| **Total COGS** | **$[X]** | **[X]%** |

| Result | Value |
|--------|-------|
| **Gross Profit** | **$[X]** |
| **Gross Margin** | **[X]%** |

---

## LTV:CAC Ratio

### Calculation

```
LTV:CAC = $[LTV] / $[CAC] = [X]:1
```

### Interpretation

| Ratio | Meaning |
|-------|---------|
| <1:1 | 🔴 Losing money on each customer |
| 1-2:1 | 🔴 Unsustainable, need improvement |
| 2-3:1 | 🟡 Acceptable, room for improvement |
| 3-5:1 | 🟢 Healthy, good balance |
| >5:1 | 🟢 Excellent, may be underinvesting in growth |

**Your Status**: [Interpretation]

---

## CAC Payback Period

### Calculation

```
CAC Payback = CAC / (ARPU × Gross Margin)
CAC Payback = $[X] / ($[X] × [X]%) = [X] months
```

### Interpretation

| Payback | Meaning |
|---------|---------|
| <6 months | 🟢 Excellent |
| 6-12 months | 🟢 Healthy |
| 12-18 months | 🟡 Acceptable |
| 18-24 months | 🟡 Needs improvement |
| >24 months | 🔴 Capital intensive |

**Your Status**: [Interpretation]

---

## Unit Economics Summary

### Per Customer Breakdown

| Stage | Metric | Value |
|-------|--------|-------|
| Acquisition | CAC | $[X] |
| Month 1 | Revenue | $[X] |
| Month 1 | COGS | $[X] |
| Month 1 | Gross Profit | $[X] |
| Breakeven | Month | [X] |
| Lifetime | Total Revenue | $[X] |
| Lifetime | Total Gross Profit | $[X] |
| Lifetime | Net Profit (after CAC) | $[X] |

---

## Improvement Opportunities

### Improve LTV
- [ ] Reduce churn: [X]% → [Y]% = $[Z] more LTV
- [ ] Increase ARPU: $[X] → $[Y] = $[Z] more LTV
- [ ] Improve expansion: [X]% → [Y]% = $[Z] more LTV

### Reduce CAC
- [ ] Improve conversion: [X]% → [Y]% = $[Z] less CAC
- [ ] Increase organic %: [X]% → [Y]% = $[Z] less CAC
- [ ] Optimize channels: Focus on [channel] = $[Z] less CAC

### Impact Modeling
| Improvement | New LTV:CAC | New Payback |
|-------------|-------------|-------------|
| Churn -1% | [X]:1 | [X] months |
| ARPU +10% | [X]:1 | [X] months |
| CAC -20% | [X]:1 | [X] months |

---

## Benchmarks Comparison

### SaaS Benchmarks
| Metric | Your Value | SMB SaaS | Mid-Market | Enterprise |
|--------|------------|----------|------------|------------|
| LTV:CAC | [X]:1 | 3:1 | 4:1 | 5:1 |
| CAC Payback | [X] mo | 12 mo | 18 mo | 24 mo |
| Gross Margin | [X]% | 70%+ | 75%+ | 80%+ |
| Churn | [X]% | 5%/mo | 3%/mo | 1%/mo |

---

## Health Check

- [X] LTV:CAC ratio above 3:1
- [X] CAC payback under 12 months
- [X] Gross margin above 70%
- [X] Churn at or below industry benchmark
- [X] Clear path to improve metrics
```

---

Apply immediately to user's input.

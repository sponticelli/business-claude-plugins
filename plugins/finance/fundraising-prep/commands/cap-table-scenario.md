---
name: cap-table-scenario
description: Model cap table with dilution scenarios for different funding rounds
---

# Cap Table Scenario

Model your cap table through multiple funding rounds to understand dilution and ownership.

## Usage

```
/cap-table-scenario [describe current cap table and planned funding rounds]
```

## Output Format

```markdown
# Cap Table Scenario Analysis: [Company]

## Current Cap Table

### Summary
| Stakeholder | Shares | % Ownership |
|-------------|--------|-------------|
| Founder 1 | [X] | [X]% |
| Founder 2 | [X] | [X]% |
| Employee Pool (allocated) | [X] | [X]% |
| Employee Pool (unallocated) | [X] | [X]% |
| Angel Investors | [X] | [X]% |
| **Total** | **[X]** | **100%** |

### Fully Diluted Shares
- Common shares: [X]
- Options outstanding: [X]
- Options available: [X]
- SAFE/Notes to convert: [X] (est. shares at $[X] cap)
- **Fully diluted**: [X]

---

## Planned Round Parameters

### [Round Name] (e.g., Seed)

| Parameter | Value |
|-----------|-------|
| Raise Amount | $[X] |
| Pre-money Valuation | $[X] |
| Post-money Valuation | $[X] |
| New Option Pool | [X]% post-money |
| SAFE/Note Conversion | $[X] at [cap/discount] |

---

## Round Modeling

### Step 1: SAFE/Note Conversion (if applicable)

**Outstanding Instruments**:
| Instrument | Amount | Cap | Discount | Conversion Price | Shares |
|------------|--------|-----|----------|------------------|--------|
| SAFE 1 | $[X] | $[X]M | — | $[X] | [X] |
| SAFE 2 | $[X] | $[X]M | — | $[X] | [X] |
| Note | $[X] | $[X]M | [X]% | $[X] | [X] |
| **Total** | **$[X]** | — | — | — | **[X]** |

### Step 2: Option Pool Expansion

```
Post-money target: [X]% unallocated
Current unallocated: [X]%
New shares needed: [X]
```

**Pool Expansion Source**: Created pre-money (dilutes existing holders)

### Step 3: New Investment

```
Investment: $[X]
Post-money: $[X]
Price per share: $[X]
New shares: [X]
Investor ownership: [X]%
```

---

## Post-Round Cap Table

### [Round Name] Cap Table

| Stakeholder | Pre-Round % | Post-Round % | Dilution |
|-------------|-------------|--------------|----------|
| Founder 1 | [X]% | [X]% | -[X]% |
| Founder 2 | [X]% | [X]% | -[X]% |
| Employees (allocated) | [X]% | [X]% | -[X]% |
| Employees (available) | [X]% | [X]% | +[X]% |
| SAFE Holders | [X]% | [X]% | [+/-X]% |
| New Investors | 0% | [X]% | — |
| **Total** | 100% | 100% | — |

### Detailed Shareholding

| Stakeholder | Shares | % Ownership | Value @ Post |
|-------------|--------|-------------|--------------|
| Founder 1 | [X] | [X]% | $[X] |
| Founder 2 | [X] | [X]% | $[X] |
| Employee Pool | [X] | [X]% | $[X] |
| SAFE Investor A | [X] | [X]% | $[X] |
| Lead Investor | [X] | [X]% | $[X] |
| Other Investors | [X] | [X]% | $[X] |
| **Total** | **[X]** | **100%** | **$[X]** |

---

## Multi-Round Projection

### Scenario: [Base/Aggressive/Conservative]

**Assumptions**:
| Round | Timing | Raise | Pre-money | Dilution |
|-------|--------|-------|-----------|----------|
| Seed | [Date] | $[X] | $[X]M | [X]% |
| Series A | [Date] | $[X] | $[X]M | [X]% |
| Series B | [Date] | $[X] | $[X]M | [X]% |

### Ownership Over Time

| Stakeholder | Current | Post-Seed | Post-A | Post-B |
|-------------|---------|-----------|--------|--------|
| Founder 1 | [X]% | [X]% | [X]% | [X]% |
| Founder 2 | [X]% | [X]% | [X]% | [X]% |
| Employees | [X]% | [X]% | [X]% | [X]% |
| Seed Investors | — | [X]% | [X]% | [X]% |
| Series A | — | — | [X]% | [X]% |
| Series B | — | — | — | [X]% |

### Founder Ownership Trajectory

```
Start       ████████████████████████████████ [X]%
Post-Seed   ██████████████████████████░░░░░░ [X]%
Post-A      ████████████████████░░░░░░░░░░░░ [X]%
Post-B      ████████████████░░░░░░░░░░░░░░░░ [X]%
```

---

## Exit Scenario Analysis

### Exit at $[X]M

**Liquidation Preference Stack**:
| Investor | Preference | Pref Amount | Participating? |
|----------|------------|-------------|----------------|
| Series B | [X]x | $[X] | [Y/N] |
| Series A | [X]x | $[X] | [Y/N] |
| Seed | [X]x | $[X] | [Y/N] |
| **Total Prefs** | — | **$[X]** | — |

**Distribution Waterfall**:

| Exit Value | $50M | $100M | $200M | $500M |
|------------|------|-------|-------|-------|
| Liquidation Prefs | $[X] | $[X] | $[X] | $[X] |
| Remaining | $[X] | $[X] | $[X] | $[X] |
| Founder 1 | $[X] | $[X] | $[X] | $[X] |
| Founder 2 | $[X] | $[X] | $[X] | $[X] |
| Employees | $[X] | $[X] | $[X] | $[X] |
| Seed Investors | $[X] | $[X] | $[X] | $[X] |
| Series A | $[X] | $[X] | $[X] | $[X] |
| Series B | $[X] | $[X] | $[X] | $[X] |

---

## Option Pool Analysis

### Current Option Pool Status

| Category | Shares | % of Pool |
|----------|--------|-----------|
| Granted & vested | [X] | [X]% |
| Granted & unvested | [X] | [X]% |
| Available for grant | [X] | [X]% |
| **Total Pool** | **[X]** | **100%** |

### Pool Adequacy Check

**Hiring Plan**:
| Role | Equity Range | Shares | Status |
|------|--------------|--------|--------|
| VP Engineering | [X]% | [X] | [ ] |
| VP Sales | [X]% | [X] | [ ] |
| Senior Engineers (5) | [X]% each | [X] | [ ] |
| Other hires | [X]% | [X] | [ ] |
| **Total Needed** | — | **[X]** | — |

**Pool Status**: [Adequate / Need expansion]

---

## Key Insights

### Dilution Summary
- Total dilution through Series B: [X]%
- Founder 1 from [X]% → [X]% (diluted [X]%)
- Founder 2 from [X]% → [X]% (diluted [X]%)

### Critical Thresholds
| Threshold | When Crossed | Impact |
|-----------|--------------|--------|
| Founder <50% | [Round] | Loss of voting control |
| Founder <25% | [Round] | Minority shareholder |
| Employee pool <[X]% | [Round] | Hiring constraints |

### Recommendations
1. [Recommendation about pool sizing]
2. [Recommendation about valuation targets]
3. [Recommendation about preference structure]

---

## Sensitivity Analysis

### Impact of Valuation Changes

| Pre-money | Founder Post-Round | Investor Ownership |
|-----------|-------------------|-------------------|
| $[X-2]M | [X]% | [X]% |
| $[X]M (base) | [X]% | [X]% |
| $[X+2]M | [X]% | [X]% |

### Impact of Option Pool Changes

| Pool Size | Founder Post-Round | Effective Dilution |
|-----------|-------------------|-------------------|
| 10% | [X]% | [X]% |
| 15% (base) | [X]% | [X]% |
| 20% | [X]% | [X]% |
```

---

Apply immediately to user's input.

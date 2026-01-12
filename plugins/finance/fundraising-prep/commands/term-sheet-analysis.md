---
name: term-sheet-analysis
description: Analyze and explain term sheet terms with founder-friendly guidance
---

# Term Sheet Analysis

Analyze term sheet terms and provide founder-friendly explanations and negotiation guidance.

## Usage

```
/term-sheet-analysis [paste term sheet terms or describe the key terms you've received]
```

## Output Format

```markdown
# Term Sheet Analysis: [Company] [Round]

## Deal Summary

| Term | Value | Assessment |
|------|-------|------------|
| Valuation (Pre) | $[X]M | [Standard/Above/Below market] |
| Investment Amount | $[X]M | — |
| Valuation (Post) | $[X]M | — |
| Investor Ownership | [X]% | [Standard/High/Low] |
| Option Pool | [X]% | [Standard/High/Low] |

**Overall Assessment**: [Founder-friendly / Market / Investor-friendly]

---

## Economic Terms Analysis

### Valuation

**Pre-money**: $[X]M
**Post-money**: $[X]M (pre + investment)
**Effective Pre** (after option pool): $[X]M

| Metric | Value | Market Range |
|--------|-------|--------------|
| Pre-money | $[X]M | $[X-Y]M for [stage] |
| Revenue multiple | [X]x | [X-Y]x typical |
| ARR at raise | $[X] | — |

**Assessment**: [Analysis of whether valuation is fair]

**Negotiation Points**:
- [Potential negotiation point]
- [Potential negotiation point]

---

### Option Pool

**Size**: [X]% post-money
**Created**: [Pre/Post]-money
**Current Pool**: [X]%

**Impact Analysis**:
```
Headline pre-money:     $[X]M
- Option pool shuffle:  $[Y]M (X% × post-money)
= Effective pre-money:  $[Z]M

Founder dilution: [X]% (headline) → [Y]% (actual)
```

**Assessment**: [Standard is 10-15% post-money, created pre-money]

**Negotiation Points**:
- [ ] Negotiate smaller pool if hiring plan doesn't require it
- [ ] Push for post-money pool creation
- [ ] Tie to specific hiring plan

---

### Liquidation Preference

**Type**: [1x Non-participating / 1x Participating / Multiple]
**Seniority**: [Pari passu / Senior to prior rounds]

**What This Means**:
| Exit Scenario | Investor Gets | Founders Get |
|---------------|--------------|--------------|
| $[Low exit] | $[X] | $[Y] |
| $[Medium exit] | $[X] | $[Y] |
| $[High exit] | $[X] | $[Y] |

**Assessment**:
- 1x Non-participating: 🟢 Founder-friendly (standard)
- 1x Participating: 🟡 Investor-friendly
- 2x+ Participating: 🔴 Very investor-friendly

**Negotiation Points**:
- [ ] Push for non-participating if participating offered
- [ ] Negotiate cap on participation
- [ ] Resist multiple liquidation preferences

---

### Anti-dilution Protection

**Type**: [Weighted Average - Broad Based / Weighted Average - Narrow Based / Full Ratchet]

**Impact in Down Round**:
| Down Round Price | Adjustment | New Investor % |
|------------------|------------|----------------|
| $[X] (50% down) | [X] shares | [Y]% |
| $[X] (75% down) | [X] shares | [Y]% |

**Assessment**:
- Broad-based weighted average: 🟢 Standard, acceptable
- Narrow-based weighted average: 🟡 More dilutive to founders
- Full ratchet: 🔴 Avoid - very harsh

**Negotiation Points**:
- [ ] Insist on broad-based weighted average
- [ ] Negotiate carve-outs for small raises

---

### Dividends

**Type**: [Non-cumulative / Cumulative / None]
**Rate**: [X]% annually (if applicable)

**Assessment**:
- None: 🟢 Standard for early-stage
- Non-cumulative: 🟢 Acceptable
- Cumulative: 🔴 Avoid - increases liquidation amount over time

---

## Control Terms Analysis

### Board Composition

**Proposed Structure**:
| Seat | Holder |
|------|--------|
| 1 | [Founder 1] |
| 2 | [Founder 2 / Common] |
| 3 | [Lead Investor] |
| 4 | [Independent / Other] |
| 5 | [Independent / Other] |

**Control Analysis**:
- Founder seats: [X]
- Investor seats: [X]
- Independent: [X]
- **Majority**: [Founders / Investors / Neither]

**Assessment**: [Standard is founder-control through Series A]

**Negotiation Points**:
- [ ] Maintain founder majority through Series A
- [ ] Require mutual approval for independents
- [ ] Define independent director criteria

---

### Protective Provisions

**Standard Provisions** (typically acceptable):
- [ ] Change to charter/bylaws
- [ ] Authorization of new stock classes
- [ ] Sale/merger of company
- [ ] Significant asset sales
- [ ] Material indebtedness

**Concerning Provisions** (negotiate carefully):
- [ ] Approval of annual budget
- [ ] Any expenditure over $[X]
- [ ] New hires over $[X] salary
- [ ] Entering new markets

**Assessment**: [Standard / Overly restrictive]

**Negotiation Points**:
- [ ] Remove operational veto rights
- [ ] Increase thresholds for required approval
- [ ] Sunset provisions after certain milestones

---

### Information Rights

**Required Reporting**:
| Report | Frequency | Recipient |
|--------|-----------|-----------|
| Financial statements | [Monthly/Quarterly] | [Major investors] |
| Board package | [Quarterly] | Board |
| Cap table | [On request] | [Investors] |
| Annual budget | Annually | Board |

**Assessment**: [Standard / Excessive]

**Negotiation Points**:
- [ ] Limit to major investors (>X% ownership)
- [ ] Set reasonable preparation timelines
- [ ] Protect competitively sensitive info

---

## Founder Terms Analysis

### Vesting

**Current Vesting**: [Describe]
**Proposed Changes**: [If any]

**Assessment**:
- Acceleration maintained: [Yes/No]
- Vesting restart: [Yes/No - 🔴 if yes]

**Negotiation Points**:
- [ ] Resist vesting reset for existing founders
- [ ] Negotiate double-trigger acceleration
- [ ] Ensure consistent treatment for co-founders

---

### Founder Restrictions

| Restriction | Term | Assessment |
|-------------|------|------------|
| Non-compete | [X] years | [Standard/Long] |
| Non-solicit | [X] years | [Standard/Long] |
| ROFR on shares | [Yes/No] | [Standard] |

---

## Other Terms

### Pro-rata Rights

**Threshold**: [X]% ownership to qualify
**Assessment**: Standard for significant investors

---

### Drag-Along

**Threshold**: [X]% to trigger
**Assessment**: [Standard is majority of preferred + majority of common]

---

### No-Shop/Exclusivity

**Period**: [X] days
**Assessment**: [Standard is 30-45 days; >60 days is long]

**Negotiation Points**:
- [ ] Limit to 30-45 days
- [ ] Include fiduciary out
- [ ] Automatic termination if investor delays

---

## Red Flags Summary

### 🔴 Major Concerns
| Term | Issue | Recommendation |
|------|-------|----------------|
| [Term] | [Why it's concerning] | [Push back] |

### 🟡 Minor Concerns
| Term | Issue | Recommendation |
|------|-------|----------------|
| [Term] | [Why it's worth noting] | [Consider negotiating] |

### 🟢 Founder-Friendly Terms
| Term | Why It's Good |
|------|---------------|
| [Term] | [Explanation] |

---

## Negotiation Priority

### Must Change
1. [Term] - [Why critical]
2. [Term] - [Why critical]

### Should Negotiate
1. [Term] - [Potential improvement]
2. [Term] - [Potential improvement]

### Accept As-Is
1. [Term] - [Why acceptable]
2. [Term] - [Why acceptable]

---

## Comparable Deals

| Term | This Deal | Market Standard | Founder-Friendly |
|------|-----------|-----------------|------------------|
| Valuation | $[X]M | $[X-Y]M | Higher |
| Option Pool | [X]% | 10-15% | Lower |
| Liquidation | [Type] | 1x Non-part | Non-participating |
| Board | [Structure] | Founder majority | Founder control |
| Anti-dilution | [Type] | Broad WA | Broad WA |

---

## Recommended Response

### Summary Statement
[Brief overall assessment and recommended approach]

### Specific Counter-Proposals
1. **[Term]**: Change from [X] to [Y] because [reason]
2. **[Term]**: Change from [X] to [Y] because [reason]
3. **[Term]**: Change from [X] to [Y] because [reason]
```

---

Apply immediately to user's input.

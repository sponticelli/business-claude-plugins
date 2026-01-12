---
name: supply-chain-analysis
description: Analyze supply chain, vendor relationships, and make-vs-buy decisions
---

# Supply Chain Analysis

Comprehensive analysis of supply chain operations, vendor relationships, inventory management, and strategic sourcing decisions.

## Usage

```
/supply-chain-analysis [area or decision to analyze]
```

Provide details about:
1. What aspect of supply chain are you analyzing?
2. Who are your current vendors/suppliers?
3. What are current pain points?
4. What are your volume requirements?
5. What are your quality and timing requirements?

## Process

1. **Map Current Supply Chain**
   - Identify all suppliers and their roles
   - Document lead times and costs
   - Assess reliability and quality
   - Identify dependencies and risks

2. **Analyze Vendor Performance**
   - Quality metrics
   - Delivery performance
   - Cost competitiveness
   - Responsiveness and support
   - Strategic alignment

3. **Evaluate Make vs. Buy**
   - Core competency assessment
   - Total cost of ownership
   - Control and flexibility needs
   - Risk considerations

4. **Optimize Inventory**
   - Demand forecasting
   - Safety stock requirements
   - Reorder point optimization
   - Carrying cost analysis

5. **Develop Recommendations**
   - Vendor consolidation/diversification
   - Process improvements
   - Risk mitigation strategies
   - Cost reduction opportunities

## Output Format

```markdown
# Supply Chain Analysis: [Focus Area]

## Executive Summary
[2-3 sentence overview of current state and key recommendations]

## Current State Assessment

### Supply Chain Map
```
[Raw Materials] → [Supplier A] → [Your Operations] → [Distribution] → [Customer]
                  [Supplier B] ↗
                  [Supplier C] ↗ (backup)
```

### Vendor Overview
| Vendor | Category | Spend/Year | % of Supply | Contract End |
|--------|----------|------------|-------------|--------------|
| [Vendor A] | [Category] | $[X] | [X]% | [Date] |
| [Vendor B] | [Category] | $[X] | [X]% | [Date] |

## Vendor Performance Scorecard

### Scoring Criteria
| Criteria | Weight | Description |
|----------|--------|-------------|
| Quality | 30% | Defect rate, consistency |
| Delivery | 25% | On-time, lead time accuracy |
| Cost | 20% | Price competitiveness, total cost |
| Service | 15% | Responsiveness, issue resolution |
| Strategic | 10% | Innovation, partnership |

### Vendor Scores
| Vendor | Quality | Delivery | Cost | Service | Strategic | Overall |
|--------|---------|----------|------|---------|-----------|---------|
| [A] | [X]/5 | [X]/5 | [X]/5 | [X]/5 | [X]/5 | [X.X] |
| [B] | [X]/5 | [X]/5 | [X]/5 | [X]/5 | [X]/5 | [X.X] |

### Performance Issues
| Vendor | Issue | Frequency | Impact | Status |
|--------|-------|-----------|--------|--------|
| [Vendor] | [Issue] | [X/month] | [High/Med/Low] | [Open/Resolved] |

## Risk Assessment

### Supply Chain Risks
| Risk | Probability | Impact | Current Mitigation | Gap |
|------|-------------|--------|-------------------|-----|
| Single source dependency | High | Critical | None | Needs backup |
| Lead time variability | Medium | High | Safety stock | Insufficient |
| Quality issues | Low | High | Inspection | Adequate |

### Concentration Risk
| Category | # Vendors | Top Vendor % | Risk Level |
|----------|-----------|--------------|------------|
| [Category] | [X] | [X]% | [High/Med/Low] |

## Make vs. Buy Analysis

### Decision Framework
| Factor | Make | Buy | Score |
|--------|------|-----|-------|
| Core competency | [Assessment] | [Assessment] | [Make/Buy] |
| Cost (5-year TCO) | $[X] | $[X] | [Make/Buy] |
| Quality control | [Assessment] | [Assessment] | [Make/Buy] |
| Flexibility | [Assessment] | [Assessment] | [Make/Buy] |
| Capacity | [Assessment] | [Assessment] | [Make/Buy] |
| Risk | [Assessment] | [Assessment] | [Make/Buy] |

**Recommendation**: [Make/Buy] because [rationale]

## Inventory Optimization

### Current State
| Item | Avg Inventory | Turnover | Carrying Cost | Stockout Rate |
|------|---------------|----------|---------------|---------------|
| [Item] | [X units] | [X/year] | $[X]/year | [X]% |

### Recommendations
| Item | Current Reorder | Recommended | Safety Stock | Annual Savings |
|------|-----------------|-------------|--------------|----------------|
| [Item] | [X units] | [X units] | [X units] | $[X] |

## Recommendations

### Immediate Actions (0-30 days)
1. **[Action]**: [Description and rationale]
   - Owner: [Role]
   - Expected Impact: [Quantified benefit]

### Medium-term (1-3 months)
1. **[Action]**: [Description and rationale]

### Strategic (3-12 months)
1. **[Action]**: [Description and rationale]

### Vendor Strategy
| Vendor | Action | Rationale | Timeline |
|--------|--------|-----------|----------|
| [A] | Expand relationship | Strong performer, capacity available | Q1 |
| [B] | Renegotiate or replace | Below performance targets | 60 days |

## Implementation Roadmap

| Phase | Actions | Timeline | Expected Outcome |
|-------|---------|----------|------------------|
| 1 | [Actions] | [Dates] | [Outcome] |
| 2 | [Actions] | [Dates] | [Outcome] |

## Success Metrics
| Metric | Current | Target | Timeline |
|--------|---------|--------|----------|
| On-time delivery | [X]% | [X]% | [Date] |
| Cost per unit | $[X] | $[X] | [Date] |
| Stockout rate | [X]% | [X]% | [Date] |
```

## Example

**Input**: `/supply-chain-analysis We're evaluating whether to bring our customer support tools in-house vs continuing with our current SaaS vendors`

**Output**: Complete analysis including:
- Current vendor landscape and costs
- Total cost of ownership comparison
- Build vs. buy decision matrix
- Risk assessment for each approach
- Implementation roadmap for recommended approach

---

Apply immediately to user's input. Ask clarifying questions about current vendors, volumes, or specific pain points if needed for meaningful analysis.

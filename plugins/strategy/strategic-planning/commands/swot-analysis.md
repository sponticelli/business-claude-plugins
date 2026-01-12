---
name: swot-analysis
description: Structured SWOT analysis with strategic implications and action planning
---

# SWOT Analysis

Comprehensive Strengths, Weaknesses, Opportunities, and Threats analysis with strategic cross-analysis and action planning.

## Usage

```
/swot-analysis [company, product, or initiative]
```

Provide details about:
1. What are you analyzing (company, product, project)?
2. What context or market are you operating in?
3. What decision or strategy is this informing?
4. Any known strengths, weaknesses, opportunities, or threats?

## Process

1. **Internal Analysis (Strengths & Weaknesses)**
   - Resources and capabilities
   - Competitive advantages
   - Operational efficiency
   - Financial position
   - Team and culture
   - Technology and IP

2. **External Analysis (Opportunities & Threats)**
   - Market trends
   - Competitive dynamics
   - Regulatory environment
   - Technology changes
   - Economic factors
   - Customer behavior shifts

3. **Cross-Analysis (TOWS Matrix)**
   - SO: Use strengths to capture opportunities
   - WO: Address weaknesses to capture opportunities
   - ST: Use strengths to mitigate threats
   - WT: Address weaknesses to avoid threats

4. **Strategic Prioritization**
   - Most critical factors
   - Strategic imperatives
   - Action planning

## Output Format

```markdown
# SWOT Analysis: [Subject]

## Executive Summary
[2-3 sentence overview of strategic position and key takeaways]

## Context
- **Subject**: [What is being analyzed]
- **Market/Industry**: [Context]
- **Time Horizon**: [Strategic planning period]
- **Key Question**: [What decision this informs]

---

## SWOT Matrix

### Strengths (Internal, Positive)
*What advantages do you have? What do you do well?*

| Strength | Impact | Sustainability |
|----------|--------|----------------|
| **S1: [Strength]** | [High/Med/Low] | [High/Med/Low] |
| [Detailed description] |||
| **S2: [Strength]** | [High/Med/Low] | [High/Med/Low] |
| [Detailed description] |||
| **S3: [Strength]** | [High/Med/Low] | [High/Med/Low] |
| [Detailed description] |||

### Weaknesses (Internal, Negative)
*What could you improve? What are you doing poorly?*

| Weakness | Impact | Addressability |
|----------|--------|----------------|
| **W1: [Weakness]** | [High/Med/Low] | [High/Med/Low] |
| [Detailed description] |||
| **W2: [Weakness]** | [High/Med/Low] | [High/Med/Low] |
| [Detailed description] |||
| **W3: [Weakness]** | [High/Med/Low] | [High/Med/Low] |
| [Detailed description] |||

### Opportunities (External, Positive)
*What trends could you take advantage of? What openings exist?*

| Opportunity | Size | Timing |
|-------------|------|--------|
| **O1: [Opportunity]** | [High/Med/Low] | [Immediate/Near/Long-term] |
| [Detailed description] |||
| **O2: [Opportunity]** | [High/Med/Low] | [Immediate/Near/Long-term] |
| [Detailed description] |||
| **O3: [Opportunity]** | [High/Med/Low] | [Immediate/Near/Long-term] |
| [Detailed description] |||

### Threats (External, Negative)
*What obstacles do you face? What are competitors doing?*

| Threat | Severity | Likelihood |
|--------|----------|------------|
| **T1: [Threat]** | [High/Med/Low] | [High/Med/Low] |
| [Detailed description] |||
| **T2: [Threat]** | [High/Med/Low] | [High/Med/Low] |
| [Detailed description] |||
| **T3: [Threat]** | [High/Med/Low] | [High/Med/Low] |
| [Detailed description] |||

---

## Visual SWOT Matrix

```
              HELPFUL                    HARMFUL
           (to objective)            (to objective)
         ┌─────────────────────┬─────────────────────┐
         │                     │                     │
         │  STRENGTHS          │  WEAKNESSES         │
INTERNAL │                     │                     │
(origin) │  • [S1]             │  • [W1]             │
         │  • [S2]             │  • [W2]             │
         │  • [S3]             │  • [W3]             │
         │                     │                     │
         ├─────────────────────┼─────────────────────┤
         │                     │                     │
         │  OPPORTUNITIES      │  THREATS            │
EXTERNAL │                     │                     │
(origin) │  • [O1]             │  • [T1]             │
         │  • [O2]             │  • [T2]             │
         │  • [O3]             │  • [T3]             │
         │                     │                     │
         └─────────────────────┴─────────────────────┘
```

---

## TOWS Strategic Analysis

*Cross-analysis to develop strategic options*

### SO Strategies (Strengths → Opportunities)
*How can we use our strengths to take advantage of opportunities?*

| Strategy | Strengths Used | Opportunities Addressed |
|----------|---------------|------------------------|
| **SO1: [Strategy]** | S1, S2 | O1 |
| [Description and rationale] |||
| **SO2: [Strategy]** | S3 | O2, O3 |
| [Description and rationale] |||

### WO Strategies (Weaknesses → Opportunities)
*How can we overcome weaknesses by pursuing opportunities?*

| Strategy | Weaknesses Addressed | Opportunities Pursued |
|----------|---------------------|----------------------|
| **WO1: [Strategy]** | W1 | O1 |
| [Description and rationale] |||
| **WO2: [Strategy]** | W2, W3 | O2 |
| [Description and rationale] |||

### ST Strategies (Strengths → Threats)
*How can we use our strengths to reduce threats?*

| Strategy | Strengths Used | Threats Mitigated |
|----------|---------------|-------------------|
| **ST1: [Strategy]** | S1, S2 | T1 |
| [Description and rationale] |||
| **ST2: [Strategy]** | S3 | T2, T3 |
| [Description and rationale] |||

### WT Strategies (Weaknesses → Threats)
*How can we minimize weaknesses and avoid threats?*

| Strategy | Weaknesses Addressed | Threats Avoided |
|----------|---------------------|-----------------|
| **WT1: [Strategy]** | W1 | T1 |
| [Description and rationale] |||
| **WT2: [Strategy]** | W2 | T2 |
| [Description and rationale] |||

---

## Strategic Priorities

### Critical Success Factors
Based on this analysis, success depends on:
1. [Most important factor]
2. [Second most important]
3. [Third most important]

### Strategic Imperatives
| Priority | Action | SWOT Link | Timeline |
|----------|--------|-----------|----------|
| 1 | [Action] | SO1 | [Timeline] |
| 2 | [Action] | ST1 | [Timeline] |
| 3 | [Action] | WO1 | [Timeline] |

### Risk Mitigation
| Risk (from WT analysis) | Mitigation Strategy | Owner |
|------------------------|---------------------|-------|
| [Risk] | [Strategy] | [Role] |

---

## Action Plan

### Immediate (0-30 days)
- [ ] [Action item]
- [ ] [Action item]

### Short-term (1-3 months)
- [ ] [Action item]
- [ ] [Action item]

### Medium-term (3-12 months)
- [ ] [Action item]
- [ ] [Action item]

---

## Review Triggers
Reassess this SWOT when:
- [Condition 1]
- [Condition 2]
- [Scheduled: X months from now]
```

## Example

**Input**: `/swot-analysis Our B2B SaaS startup entering the enterprise market`

**Output**: Complete SWOT analysis with:
- Internal assessment (agile culture strength, limited resources weakness)
- External assessment (enterprise digital transformation opportunity, incumbent threat)
- TOWS strategies for enterprise go-to-market
- Prioritized action plan for market entry

---

Apply immediately to user's input. Ask clarifying questions if the subject or context is unclear.

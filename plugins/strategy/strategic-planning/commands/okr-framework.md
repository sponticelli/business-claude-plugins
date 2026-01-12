---
name: okr-framework
description: Create OKRs (Objectives and Key Results) for company, team, or individual goals
---

# OKR Framework

Create well-structured Objectives and Key Results (OKRs) that align teams and drive measurable outcomes.

## Usage

```
/okr-framework [context and goals]
```

Provide details about:
1. What level are these OKRs for (company, team, individual)?
2. What time period (quarter, year)?
3. What are the strategic priorities or goals?
4. What is the current situation/baseline?
5. Any constraints or dependencies?

## Process

1. **Clarify Strategic Context**
   - Mission and vision alignment
   - Strategic priorities
   - Key challenges to address

2. **Define Objectives**
   - Qualitative, inspiring goals
   - Clear direction and intent
   - Ambitious but achievable

3. **Develop Key Results**
   - Measurable outcomes
   - Specific and time-bound
   - 3-5 per objective

4. **Validate Quality**
   - SMART criteria check
   - Alignment verification
   - Stretch vs. commit balance

5. **Plan Implementation**
   - Initiatives to achieve KRs
   - Tracking cadence
   - Review process

## Output Format

```markdown
# OKR Plan: [Entity] - [Time Period]

## Strategic Context

### Mission/Vision Alignment
[How these OKRs support the broader mission]

### Strategic Priorities for [Period]
1. [Priority 1]
2. [Priority 2]
3. [Priority 3]

### Current State
- [Relevant baseline metric 1]: [Value]
- [Relevant baseline metric 2]: [Value]

---

## OKRs

### Objective 1: [Inspiring, Qualitative Goal]
*[Why this matters - 1 sentence]*

| Key Result | Baseline | Target | Confidence |
|------------|----------|--------|------------|
| **KR1.1**: [Measurable outcome] | [Current] | [Target] | [50-70%] |
| **KR1.2**: [Measurable outcome] | [Current] | [Target] | [50-70%] |
| **KR1.3**: [Measurable outcome] | [Current] | [Target] | [50-70%] |

**Owner**: [Name/Role]

**Key Initiatives**:
- [Initiative that will drive KR1.1]
- [Initiative that will drive KR1.2]
- [Initiative that will drive KR1.3]

---

### Objective 2: [Inspiring, Qualitative Goal]
*[Why this matters - 1 sentence]*

| Key Result | Baseline | Target | Confidence |
|------------|----------|--------|------------|
| **KR2.1**: [Measurable outcome] | [Current] | [Target] | [50-70%] |
| **KR2.2**: [Measurable outcome] | [Current] | [Target] | [50-70%] |
| **KR2.3**: [Measurable outcome] | [Current] | [Target] | [50-70%] |

**Owner**: [Name/Role]

**Key Initiatives**:
- [Initiative that will drive KR2.1]
- [Initiative that will drive KR2.2]
- [Initiative that will drive KR2.3]

---

### Objective 3: [Inspiring, Qualitative Goal]
*[Why this matters - 1 sentence]*

| Key Result | Baseline | Target | Confidence |
|------------|----------|--------|------------|
| **KR3.1**: [Measurable outcome] | [Current] | [Target] | [50-70%] |
| **KR3.2**: [Measurable outcome] | [Current] | [Target] | [50-70%] |
| **KR3.3**: [Measurable outcome] | [Current] | [Target] | [50-70%] |

**Owner**: [Name/Role]

**Key Initiatives**:
- [Initiative that will drive KR3.1]
- [Initiative that will drive KR3.2]
- [Initiative that will drive KR3.3]

---

## OKR Summary View

```
OBJECTIVE 1: [Short name]
├── KR1.1: [Metric] [Baseline] → [Target]
├── KR1.2: [Metric] [Baseline] → [Target]
└── KR1.3: [Metric] [Baseline] → [Target]

OBJECTIVE 2: [Short name]
├── KR2.1: [Metric] [Baseline] → [Target]
├── KR2.2: [Metric] [Baseline] → [Target]
└── KR2.3: [Metric] [Baseline] → [Target]

OBJECTIVE 3: [Short name]
├── KR3.1: [Metric] [Baseline] → [Target]
├── KR3.2: [Metric] [Baseline] → [Target]
└── KR3.3: [Metric] [Baseline] → [Target]
```

## Alignment Check

### Vertical Alignment (if applicable)
| This OKR | Supports Company/Team OKR |
|----------|--------------------------|
| Objective 1 | [Parent objective it supports] |
| Objective 2 | [Parent objective it supports] |

### Horizontal Alignment
| This OKR | Dependencies |
|----------|-------------|
| KR1.2 | Depends on [Team X] delivering [Y] |
| KR2.1 | Shared with [Team Y] |

## Quality Checklist

### Objectives Quality
- [ ] Qualitative and inspiring (not a metric)
- [ ] Clear direction and intent
- [ ] Ambitious but not impossible
- [ ] Within sphere of influence
- [ ] Timeframe appropriate (3-5 for quarter, 3-4 for year)

### Key Results Quality
- [ ] Measurable with specific number
- [ ] Outcome-focused (not activity/output)
- [ ] Has clear baseline and target
- [ ] Achievable with ~70% confidence
- [ ] 3-5 KRs per objective
- [ ] No "increase by X%" without baseline
- [ ] Verifiable - could be audited

### Common Anti-patterns Avoided
- [ ] No "Continue to..." or "Maintain..." (should show change)
- [ ] No vanity metrics (measures value, not activity)
- [ ] No sandbagging (targets are stretch goals)
- [ ] No binary KRs unless truly binary outcomes
- [ ] No tasks disguised as key results

## Scoring Guide

### At End of Period
| Score | Meaning |
|-------|---------|
| 0.0-0.3 | Significant miss - investigate why |
| 0.4-0.6 | Progress but fell short |
| 0.7-0.8 | Strong delivery - sweet spot |
| 0.9-1.0 | Either exceptional or target too easy |

### Confidence Rating Guide
| Confidence | Meaning | Appropriate For |
|------------|---------|-----------------|
| 50% | Ambitious stretch | Most KRs should be here |
| 70% | Confident stretch | Important commitments |
| 90% | Near-certain | Critical dependencies |

## Tracking Plan

### Weekly Check-in
- Update confidence levels
- Note blockers
- Identify at-risk KRs

### Monthly Review
- Score progress (0-1.0)
- Discuss what's working/not
- Adjust initiatives if needed

### End of Period
- Final scoring
- Retrospective on process
- Inputs for next cycle

## Template for Check-in

```markdown
## OKR Check-in: [Date]

### Objective 1: [Name]
| KR | Progress | Confidence | Status | Notes |
|----|----------|------------|--------|-------|
| KR1.1 | [X]/[Target] | [%] | [On track/At risk/Off track] | [Notes] |
| KR1.2 | [X]/[Target] | [%] | [Status] | [Notes] |

### Blockers
- [Blocker and needed support]

### Wins
- [Recent progress to celebrate]
```
```

## Example

**Input**: `/okr-framework Q1 OKRs for our product team, focused on improving user engagement and launching mobile app`

**Output**: Complete OKR set including:
- Objective 1: "Delight users with an engaging product experience"
  - KR: DAU/MAU from 25% to 40%
  - KR: Session duration from 4min to 7min
  - KR: Feature adoption score from 30 to 50
- Objective 2: "Successfully launch mobile app"
  - KR: Ship iOS app with 4.5+ star rating
  - KR: 10K downloads in first month
  - KR: Mobile DAU reaches 20% of web DAU
- Quality checklist validation
- Weekly tracking template

---

Apply immediately to user's input. Ask clarifying questions about strategic priorities, current baselines, or scope if needed.

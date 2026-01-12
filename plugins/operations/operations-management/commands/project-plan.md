---
name: project-plan
description: Create a comprehensive project plan with timeline, resources, milestones, and risk management
---

# Project Plan

Create detailed project plans with work breakdown, resource allocation, timeline, dependencies, and risk management.

## Usage

```
/project-plan [project name and objectives]
```

Provide details about:
1. What is the project goal?
2. What is the deadline or timeframe?
3. What resources are available?
4. Who are the key stakeholders?
5. What are known constraints or risks?

## Process

1. **Define Project Scope**
   - Clear objectives and success criteria
   - Deliverables and out-of-scope items
   - Key assumptions and constraints

2. **Create Work Breakdown Structure**
   - Major phases/workstreams
   - Tasks within each phase
   - Estimated effort for each task

3. **Identify Dependencies**
   - Task dependencies (finish-to-start, etc.)
   - External dependencies
   - Critical path identification

4. **Allocate Resources**
   - Required skills per task
   - Resource assignments
   - Capacity constraints

5. **Build Timeline**
   - Milestone dates
   - Phase durations
   - Buffer time allocation

6. **Assess Risks**
   - Risk identification
   - Impact and probability scoring
   - Mitigation strategies

## Output Format

```markdown
# Project Plan: [Project Name]

## Executive Summary
- **Objective**: [Clear goal statement]
- **Timeline**: [Start] to [End]
- **Budget**: [If applicable]
- **Project Lead**: [Name/Role]

## Success Criteria
1. [Measurable outcome 1]
2. [Measurable outcome 2]
3. [Measurable outcome 3]

## Scope

### In Scope
- [Deliverable 1]
- [Deliverable 2]

### Out of Scope
- [Explicitly excluded item 1]
- [Explicitly excluded item 2]

### Assumptions
- [Assumption 1]
- [Assumption 2]

## Work Breakdown Structure

### Phase 1: [Phase Name] ([Duration])
| ID | Task | Owner | Effort | Dependencies |
|----|------|-------|--------|--------------|
| 1.1 | [Task] | [Role] | [X days] | - |
| 1.2 | [Task] | [Role] | [X days] | 1.1 |
| 1.3 | [Task] | [Role] | [X days] | 1.1, 1.2 |

**Phase Deliverable**: [What's complete at phase end]
**Milestone**: [Milestone name] - [Date]

### Phase 2: [Phase Name] ([Duration])
...

## Timeline

### Gantt Overview
```
Week 1   Week 2   Week 3   Week 4   Week 5   Week 6
|--------|--------|--------|--------|--------|--------|
[Phase 1: Planning    ]
         [Phase 2: Development           ]
                           [Phase 3: Testing    ]
                                    [Phase 4: Launch]
```

### Key Milestones
| Milestone | Date | Criteria |
|-----------|------|----------|
| [Milestone 1] | [Date] | [What must be true] |
| [Milestone 2] | [Date] | [What must be true] |

## Resource Plan

### Team Allocation
| Role | Name | Allocation | Phase(s) |
|------|------|------------|----------|
| [Role] | [Name] | [X]% | Phase 1-2 |
| [Role] | [Name] | [X]% | Phase 2-3 |

### Capacity Analysis
- Total effort: [X] person-days
- Available capacity: [X] person-days
- Buffer: [X]% ([X] days)

## Risk Register

| Risk | Probability | Impact | Score | Mitigation | Owner |
|------|-------------|--------|-------|------------|-------|
| [Risk 1] | High/Med/Low | High/Med/Low | [1-9] | [Strategy] | [Role] |
| [Risk 2] | High/Med/Low | High/Med/Low | [1-9] | [Strategy] | [Role] |

### Risk Scoring
- **High (3)**: Likely to occur / Major impact on timeline/budget/quality
- **Medium (2)**: Possible / Moderate impact
- **Low (1)**: Unlikely / Minor impact
- **Score**: Probability x Impact (1-9)

## Communication Plan

| Audience | Frequency | Format | Owner |
|----------|-----------|--------|-------|
| Stakeholders | Weekly | Status email | PM |
| Team | Daily | Standup | PM |
| Executives | Bi-weekly | Dashboard | PM |

## Decision Log
| ID | Decision | Date | Rationale | Decided By |
|----|----------|------|-----------|------------|
| D1 | [Decision] | [Date] | [Why] | [Who] |

## Next Steps
1. [Immediate action 1]
2. [Immediate action 2]
3. [Immediate action 3]
```

## Example

**Input**: `/project-plan Launch new mobile app feature - social sharing - in 6 weeks with 2 developers and 1 designer`

**Output**: Complete project plan with:
- 4-phase breakdown (Design, Development, Testing, Launch)
- Week-by-week timeline with dependencies
- Resource allocation across phases
- Risk register including technical debt, scope creep
- Milestone checkpoints and success criteria

---

Apply immediately to user's input. Ask clarifying questions about timeline, resources, or scope if critical information is missing.

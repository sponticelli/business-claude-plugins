---
name: resource-allocation
description: Analyze team capacity and optimize resource allocation across projects and initiatives
---

# Resource Allocation

Analyze team capacity, identify allocation conflicts, and optimize resource distribution across projects and initiatives.

## Usage

```
/resource-allocation [team/projects to analyze]
```

Provide details about:
1. What team or resources are you managing?
2. What projects/initiatives need resources?
3. What are the priorities?
4. What constraints exist (budget, skills, availability)?
5. What is the time horizon?

## Process

1. **Inventory Resources**
   - Team members and roles
   - Skills and competencies
   - Available capacity (FTE or hours)
   - Constraints (PTO, meetings, operational work)

2. **Map Demand**
   - Active projects and their resource needs
   - Upcoming initiatives
   - Ongoing operational requirements
   - Skill requirements per project

3. **Identify Gaps and Conflicts**
   - Over-allocated resources
   - Under-utilized capacity
   - Skill gaps
   - Critical dependencies on individuals

4. **Optimize Allocation**
   - Priority-based assignment
   - Load balancing
   - Cross-training opportunities
   - Hiring/contracting recommendations

5. **Create Allocation Plan**
   - Resource assignments by project
   - Timeline view of allocation
   - Contingency planning

## Output Format

```markdown
# Resource Allocation Analysis

## Executive Summary
[2-3 sentence overview of capacity situation and key recommendations]

## Resource Inventory

### Team Capacity
| Name | Role | FTE | Available Hrs/Week | Key Skills |
|------|------|-----|-------------------|------------|
| [Name] | [Role] | [1.0] | [32] | [Skills] |
| [Name] | [Role] | [0.8] | [25] | [Skills] |

**Total Capacity**: [X] FTE / [X] hours per week

### Capacity Adjustments
| Factor | Impact | Notes |
|--------|--------|-------|
| Meetings overhead | -[X]% | Standing meetings, 1:1s |
| Operational work | -[X]% | Support, maintenance |
| PTO/Holidays | -[X]% | Next quarter average |
| **Net Available** | [X]% | Actual project capacity |

## Demand Analysis

### Active Projects
| Project | Priority | Required FTE | Timeline | Skills Needed |
|---------|----------|--------------|----------|---------------|
| [Project A] | P1 | [1.5] | [8 weeks] | [Skills] |
| [Project B] | P2 | [0.5] | [Ongoing] | [Skills] |

**Total Demand**: [X] FTE

### Capacity vs. Demand
```
Capacity:  ████████████████████ 100%
Demand:    ██████████████████████████ 130%
Gap:       ██████ -30%
```

## Allocation Conflicts

### Over-Allocated Resources
| Resource | Current Load | Projects | Risk |
|----------|-------------|----------|------|
| [Name] | [150]% | [Project A, B, C] | High - burnout, delays |

### Under-Utilized Resources
| Resource | Current Load | Available For |
|----------|-------------|---------------|
| [Name] | [40]% | [X] hours/week |

### Skill Gaps
| Skill Needed | Projects | Current Coverage | Gap |
|--------------|----------|------------------|-----|
| [Skill] | [Projects] | [X] people | Need [Y] more |

### Single Points of Failure
| Area | Person | Risk | Mitigation |
|------|--------|------|------------|
| [Area] | [Name] | [Description] | [Strategy] |

## Recommended Allocation

### Project Assignments
| Project | Resource | Allocation | Period |
|---------|----------|------------|--------|
| [Project A] | [Name 1] | [60]% | Weeks 1-8 |
| [Project A] | [Name 2] | [40]% | Weeks 1-4 |
| [Project B] | [Name 3] | [50]% | Ongoing |

### Timeline View
```
         Week 1-2    Week 3-4    Week 5-6    Week 7-8
Name 1   [Proj A 60%][Proj A 60%][Proj A 60%][Proj A 60%]
Name 2   [Proj A 40%][Proj A 40%][Proj B 50%][Proj B 50%]
Name 3   [Proj B 50%][Proj B 50%][Proj B 50%][Proj B 50%]
```

## Recommendations

### Immediate Actions
1. **[Action]**: [Specific recommendation with rationale]
2. **[Action]**: [Specific recommendation with rationale]

### Capacity Solutions
| Option | Pros | Cons | Recommendation |
|--------|------|------|----------------|
| Hire contractor | Fast, flexible | Cost, ramp-up | [Yes/No] |
| Delay Project X | Reduces load | Business impact | [Yes/No] |
| Reduce scope | Keeps timeline | Feature cuts | [Yes/No] |

### Cross-Training Opportunities
| Skill Gap | Train | Trainer | Timeline |
|-----------|-------|---------|----------|
| [Skill] | [Name] | [Name] | [X weeks] |

## Risk Mitigation
| Risk | Likelihood | Impact | Mitigation |
|------|------------|--------|------------|
| Key person unavailable | Medium | High | Cross-train backup |
| Scope creep | High | Medium | Strict change control |

## Next Review
- **Date**: [2 weeks from now]
- **Trigger for earlier review**: [Conditions that would require reassessment]
```

## Example

**Input**: `/resource-allocation Engineering team of 5 across 3 active projects, one launching in 4 weeks`

**Output**: Full allocation analysis with:
- Individual capacity breakdown with overhead
- Project demand vs. available capacity
- Identification of over-allocated engineers
- Rebalanced allocation recommendations
- Risk mitigation for the critical launch

---

Apply immediately to user's input. Ask clarifying questions about team composition, project priorities, or timeline if critical information is missing.

---
name: productivity-assessment
description: Assess team productivity, identify time drains, and recommend improvements to workflows and tools
---

# Productivity Assessment

Comprehensive analysis of team productivity including time allocation, meeting efficiency, tool utilization, and collaboration patterns.

## Usage

```
/productivity-assessment [team or area to assess]
```

Provide details about:
1. What team or function are you assessing?
2. What does a typical workday/week look like?
3. What tools and systems do you use?
4. What are the biggest perceived time drains?
5. What outcomes are you trying to improve?

## Process

1. **Analyze Time Allocation**
   - How time is currently spent
   - Balance of deep work vs. shallow work
   - Meeting load analysis
   - Context switching frequency

2. **Evaluate Meeting Efficiency**
   - Meeting frequency and duration
   - Attendance patterns
   - Decision velocity
   - Meeting-free time availability

3. **Assess Tool Stack**
   - Current tools and their purposes
   - Tool overlap and redundancy
   - Adoption and utilization rates
   - Integration opportunities

4. **Review Collaboration Patterns**
   - Communication channels and norms
   - Async vs. sync balance
   - Information accessibility
   - Knowledge management

5. **Develop Recommendations**
   - Quick wins for immediate impact
   - Behavioral changes
   - Tool optimizations
   - Structural changes

## Output Format

```markdown
# Productivity Assessment: [Team/Area]

## Executive Summary
**Productivity Score**: [X]/100
[2-3 sentence overview of findings and top recommendations]

## Time Allocation Analysis

### Current Time Distribution
| Category | Hours/Week | % of Time | Benchmark | Gap |
|----------|------------|-----------|-----------|-----|
| Deep Work | [X] | [X]% | 40% | [+/-X]% |
| Meetings | [X] | [X]% | 20% | [+/-X]% |
| Communication | [X] | [X]% | 15% | [+/-X]% |
| Admin/Overhead | [X] | [X]% | 10% | [+/-X]% |
| Breaks/Personal | [X] | [X]% | 15% | [+/-X]% |

### Time Distribution Visualization
```
Ideal:    [████Deep Work████][██Meet██][Comm][Ad][Break]
Current:  [██Deep██][████Meetings████][█Comm█][Admin][Br]
```

### Context Switching Analysis
- Average context switches per day: [X]
- Average time to refocus: [X] minutes
- **Daily productivity loss**: [X] hours

### Deep Work Opportunities
| Time Block | Current Use | Opportunity |
|------------|-------------|-------------|
| Morning (9-12) | [Description] | [Recommendation] |
| Afternoon (1-5) | [Description] | [Recommendation] |

## Meeting Efficiency Analysis

### Meeting Load
| Metric | Current | Benchmark | Status |
|--------|---------|-----------|--------|
| Hours in meetings/week | [X] | <10 | [Good/Concern/Critical] |
| Meetings per day | [X] | <4 | [Good/Concern/Critical] |
| Back-to-back meetings | [X]% | <20% | [Good/Concern/Critical] |
| Meeting-free days | [X]/week | 2+ | [Good/Concern/Critical] |

### Meeting Audit
| Meeting | Frequency | Duration | Attendees | Value Score | Recommendation |
|---------|-----------|----------|-----------|-------------|----------------|
| [Meeting] | [X/week] | [X min] | [X] | [1-5] | [Keep/Modify/Cancel] |

### Meeting Cost Calculator
- Average hourly cost per attendee: $[X]
- Weekly meeting hours: [X]
- **Weekly meeting cost**: $[X]
- Potential savings with optimization: $[X]/week

## Tool Stack Analysis

### Current Tools
| Tool | Purpose | Users | Utilization | Monthly Cost |
|------|---------|-------|-------------|--------------|
| [Tool] | [Purpose] | [X] | [X]% | $[X] |

### Tool Health Score
| Dimension | Score | Notes |
|-----------|-------|-------|
| Adoption | [X]/5 | [Assessment] |
| Integration | [X]/5 | [Assessment] |
| Redundancy | [X]/5 | [Lower is better] |
| Cost Efficiency | [X]/5 | [Assessment] |

### Consolidation Opportunities
| Current Tools | Replace With | Annual Savings | Migration Effort |
|---------------|--------------|----------------|------------------|
| [Tool A, B] | [Tool C] | $[X] | [Low/Med/High] |

### Missing Capabilities
| Gap | Impact | Recommended Solution | Cost |
|-----|--------|---------------------|------|
| [Gap] | [Impact] | [Tool/Process] | $[X]/month |

## Collaboration Patterns

### Communication Channel Usage
| Channel | Volume/Day | Response Time | Best For |
|---------|------------|---------------|----------|
| Slack/Chat | [X] messages | [X] minutes | Quick questions |
| Email | [X] emails | [X] hours | External, formal |
| Meetings | [X] hours | Immediate | Complex decisions |

### Async vs. Sync Balance
```
Current:  [████████Sync████████][██Async██]  (70/30)
Optimal:  [████Sync████][██████████Async██████████]  (40/60)
```

### Knowledge Management
| Aspect | Current State | Target | Gap |
|--------|---------------|--------|-----|
| Documentation coverage | [X]% | 80% | [Gap] |
| Findability score | [X]/5 | 4/5 | [Gap] |
| Update frequency | [Frequency] | Weekly | [Gap] |

## Recommendations

### Quick Wins (This Week)
1. **[Recommendation]**
   - Time saved: [X] hours/week
   - Implementation: [Steps]

2. **[Recommendation]**
   - Time saved: [X] hours/week
   - Implementation: [Steps]

### Behavioral Changes (This Month)
1. **[Change]**
   - Rationale: [Why]
   - How to implement: [Steps]
   - Expected impact: [Benefit]

### Structural Changes (This Quarter)
1. **[Change]**
   - Investment required: [Time/Cost]
   - Expected ROI: [Benefit]
   - Implementation plan: [Overview]

## Implementation Roadmap

| Week | Focus | Actions | Expected Outcome |
|------|-------|---------|------------------|
| 1 | Meeting audit | Cancel/reduce low-value meetings | +[X] hours |
| 2 | Tool cleanup | Remove redundant tools | $[X] saved |
| 3-4 | New habits | Implement focus blocks | +[X]% deep work |

## Success Metrics

| Metric | Current | 30-Day Target | 90-Day Target |
|--------|---------|---------------|---------------|
| Deep work hours/week | [X] | [X] | [X] |
| Meeting hours/week | [X] | [X] | [X] |
| Team satisfaction | [X]/10 | [X]/10 | [X]/10 |
| Output per person | [Baseline] | +[X]% | +[X]% |

## Monitoring Plan
- Weekly: [What to track]
- Monthly: [What to review]
- Quarterly: [Full reassessment trigger]
```

## Example

**Input**: `/productivity-assessment Our product team of 8 feels like they're in meetings all day and can't get coding done`

**Output**: Complete assessment with:
- Time distribution showing 60% in meetings (vs. 20% benchmark)
- Audit of all recurring meetings with value scores
- Identification of redundant standups and status meetings
- Recommendation to implement maker schedules
- 90-day plan to recover 15 hours/week of deep work

---

Apply immediately to user's input. Ask clarifying questions about team size, current meeting load, or specific pain points if needed.

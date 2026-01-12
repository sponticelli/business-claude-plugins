---
name: process-audit
description: Analyze a business process to identify bottlenecks, inefficiencies, and optimization opportunities
---

# Process Audit

Comprehensive analysis of a business process to identify bottlenecks, waste, and improvement opportunities using lean methodology.

## Usage

```
/process-audit [process name or description]
```

Provide details about:
1. What process are you analyzing?
2. What are the main steps involved?
3. Who is involved at each step?
4. What tools/systems are used?
5. What are the current pain points?

## Process

1. **Document Current State**
   - Map all process steps sequentially
   - Identify inputs, outputs, and handoffs
   - Note tools and systems involved
   - Record approximate timing for each step

2. **Identify Waste Categories**
   - **Waiting**: Time spent idle between steps
   - **Overprocessing**: Unnecessary steps or approvals
   - **Rework**: Corrections and error handling
   - **Motion**: Unnecessary switching between tools/contexts
   - **Inventory**: Work-in-progress backlogs
   - **Defects**: Quality issues requiring fixes
   - **Transportation**: Unnecessary data/document movement

3. **Analyze Bottlenecks**
   - Calculate cycle time vs. wait time ratio
   - Identify steps with highest queue times
   - Find single points of failure
   - Map dependency chains

4. **Prioritize Improvements**
   - Score by impact (time saved, quality improved)
   - Score by effort (complexity, cost, change management)
   - Identify quick wins vs. strategic initiatives

5. **Create Recommendations**
   - Specific, actionable improvements
   - Expected impact quantification
   - Implementation approach

## Output Format

```markdown
# Process Audit: [Process Name]

## Executive Summary
[2-3 sentence overview of findings and top recommendation]

## Current State Analysis

### Process Map
| Step | Owner | Duration | Wait Time | Tools |
|------|-------|----------|-----------|-------|
| 1. [Step] | [Role] | [Time] | [Wait] | [Tools] |
| ... | ... | ... | ... | ... |

### Key Metrics
- **Total Cycle Time**: [X hours/days]
- **Value-Add Time**: [X hours/days] ([X]%)
- **Wait Time**: [X hours/days] ([X]%)
- **Handoffs**: [X]
- **Decision Points**: [X]

## Waste Identification

### Critical Issues
| Issue | Type | Impact | Location |
|-------|------|--------|----------|
| [Issue] | [Waste Type] | [High/Med/Low] | Step [X] |

### Bottleneck Analysis
[Description of primary bottleneck and its downstream effects]

## Recommendations

### Quick Wins (Low effort, High impact)
1. **[Recommendation]**
   - Impact: [Quantified benefit]
   - Effort: [Low/Med/High]
   - Implementation: [Specific steps]

### Strategic Improvements (Higher effort, High impact)
1. **[Recommendation]**
   - Impact: [Quantified benefit]
   - Effort: [Low/Med/High]
   - Implementation: [Specific steps]

## Implementation Roadmap

| Phase | Actions | Timeline | Owner |
|-------|---------|----------|-------|
| 1 | [Quick wins] | Week 1-2 | [Role] |
| 2 | [Medium-term] | Week 3-6 | [Role] |
| 3 | [Strategic] | Month 2-3 | [Role] |

## Success Metrics
- [Metric 1]: Current [X] → Target [Y]
- [Metric 2]: Current [X] → Target [Y]
```

## Example

**Input**: `/process-audit Our customer onboarding process takes 2 weeks and involves sales, success, and engineering teams`

**Output**: Full process audit with:
- Step-by-step process map with timing
- Identification of wait times and handoff delays
- Bottleneck analysis (e.g., engineering setup queue)
- Prioritized recommendations to reduce to 3-5 days
- Implementation roadmap with quick wins

---

Apply immediately to user's input. Ask clarifying questions if the process description lacks sufficient detail for meaningful analysis.

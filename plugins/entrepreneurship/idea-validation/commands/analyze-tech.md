---
name: analyze-tech
description: Analyze technical feasibility and implementation complexity for a startup idea (6 metrics)
---

# Analyze Technical Viability

Quick analysis of technical feasibility, implementation complexity, and technology requirements using 6 key metrics from the Technical Viability dimension.

## Usage

```
/analyze-tech [your startup idea]
```

## Metrics Evaluated

| # | Metric | Question |
|---|--------|----------|
| 5.1 | Technical Feasibility | Is the technical solution solid and complete? |
| 5.2 | Functional Performance | Does it work better than alternatives technically? |
| 5.3 | Research & Development | How heavy is the remaining R&D burden? |
| 5.4 | Technology Significance | How significant is the tech contribution? |
| 5.5 | Technology of Production | Are required tech and skills available? |
| 5.6 | Tooling Cost | What's the production tooling burden? |

## Output Format

```markdown
# Technical Viability Analysis

## Idea Summary
[Brief description]

## Dimension Score
**[XX.X]%** (X/30 points)

## Metric Breakdown

### 5.1 Technical Feasibility
**Score**: X/5
**Assessment**: [Explanation]
**Improve**: [Suggestions]

[Repeat for all 6 metrics]

## Technical Assessment

### Architecture Overview
[High-level technical approach]

### Technology Stack
[Recommended technologies]

### Key Technical Challenges
1. [Challenge and mitigation]
2. [Challenge and mitigation]
3. [Challenge and mitigation]

### Build vs Buy Decisions
[Key components to build vs integrate]

## Team Requirements

### Core Skills Needed
- [Skill 1]
- [Skill 2]
- [Skill 3]

### Hiring Difficulty
[Assessment of talent availability]

## Key Insights

### Strengths
- [Top strength]
- [Second strength]

### Concerns
- [Top concern]
- [Second concern]

### Priority Actions
1. [Most important action]
2. [Second action]
3. [Third action]

## Next Steps
For complete validation, run `/validate-idea` to evaluate all 33 metrics.
```

## Example

**Input**: `/analyze-tech Real-time language translation earbuds`

**Output**: Analysis of technical viability including:
- Technical feasibility assessment
- Performance comparison to existing solutions
- R&D requirements and timeline
- Innovation significance
- Talent and skill availability
- Hardware and software tooling costs

---

Apply immediately to user's input.

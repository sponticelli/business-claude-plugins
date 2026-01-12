---
name: validate-idea
description: Run a comprehensive 33-metric validation analysis on a startup idea
---

# Validate Startup Idea

Comprehensive startup idea validation using a 33-metric framework across 5 key dimensions: Market Strategy, Market Viability, Product Viability, Risk & Financial Viability, and Technical Viability.

## Usage

```
/validate-idea [description of your startup idea]
```

Or provide detailed answers to:
1. What are you building?
2. Who is it for?
3. What problem does it solve?
4. How does it work?
5. How will you make money?
6. Who are your competitors?
7. What makes you different?

## Process

1. **Extract Idea Components**
   - Problem statement
   - Target segments
   - Value proposition
   - Solution outline
   - Market angle
   - Monetization model
   - Key assumptions
   - Potential risks

2. **Present General Overview**
   - Summarize the idea in 2-3 paragraphs

3. **Evaluate All 33 Metrics**
   - Score each metric 1-5
   - Provide meaning, explanation, suggestions

4. **Calculate Scores**
   - Overall score: (Sum of all scores / 165) x 100
   - Dimension scores for each of 5 groups

5. **Generate Executive Summary**
   - Clear go/no-go recommendation
   - Top strengths and risks
   - Immediate next steps

## Output Format

```markdown
# Startup Idea Validation Report

## 1. Idea Overview
[2-3 paragraph summary]

## 2. Overall Score
**[XX.X]%** - [Interpretation: Exceptional/Promising/Moderate/Weak/Not Recommended]

## 3. Dimension Scores

| Dimension | Score | Status |
|-----------|-------|--------|
| Market Strategy (6 metrics) | XX.X% | [Status] |
| Market Viability (5 metrics) | XX.X% | [Status] |
| Product Viability (8 metrics) | XX.X% | [Status] |
| Risk & Financial (8 metrics) | XX.X% | [Status] |
| Technical Viability (6 metrics) | XX.X% | [Status] |

## 4. Detailed Analysis
[For each of 33 metrics: Score, Meaning, Explanation, Suggestions]

## 5. Executive Summary

### Recommendation
**[Yes / With Conditions / No]**

### Top 3 Strengths
1. [Strength]
2. [Strength]
3. [Strength]

### Top 3 Risks
1. [Risk]
2. [Risk]
3. [Risk]

### Immediate Next Steps
1. [Action]
2. [Action]
3. [Action]
```

## Interpretation Guide

| Score | Meaning |
|-------|---------|
| 85-100% | Exceptional - Strong candidate for success |
| 70-84% | Promising - Good potential with areas to strengthen |
| 55-69% | Moderate - Significant work needed |
| 40-54% | Weak - Major concerns |
| <40% | Not Recommended - Fundamental issues |

## Example

**Input**: `/validate-idea A mobile app that uses AI to match remote workers with quiet cafes to work from, based on noise levels, WiFi speed, and available seating`

**Output**: Full 33-metric analysis with:
- Overall score and interpretation
- Breakdown by all 5 dimensions
- Detailed analysis of each metric
- Executive summary with recommendation
- Specific next steps to improve weak areas

## Related Commands

- `/analyze-market-strategy` - Deep dive on market positioning (6 metrics)
- `/analyze-market-viability` - Focus on market size and demand (5 metrics)
- `/analyze-product` - Product-market fit analysis (8 metrics)
- `/analyze-financials` - Risk and financial viability (8 metrics)
- `/analyze-tech` - Technical feasibility assessment (6 metrics)

---

Apply immediately to user's input. If the idea description is incomplete, ask clarifying questions before proceeding with the full analysis.

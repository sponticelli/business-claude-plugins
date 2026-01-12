---
name: create-pitch-deck
description: Generate a complete 10-12 slide investor pitch deck outline
---

# Create Pitch Deck

Generate a comprehensive pitch deck outline with content for each slide, tailored to your startup and funding stage.

## Usage

```
/create-pitch-deck [describe your startup and funding goals]
```

## Information Needed

- Company/product description
- Target funding stage (pre-seed, seed, Series A)
- Key metrics/traction
- Team background
- Funding amount sought

## Process

1. Extract startup details and context
2. Identify the strongest narrative angle
3. Structure the 10-12 slide flow
4. Write compelling content for each slide
5. Add speaker notes and key talking points

## Output Format

```markdown
# [Company Name] Pitch Deck

## Funding Stage: [Stage]
## Target Raise: $[Amount]

---

## Slide 1: Title
**Headline**: [Compelling one-liner]
**Subheadline**: [What you do]
**Visual**: [Suggested visual element]
**Speaker Notes**: [What to say]

---

## Slide 2: Problem
**Headline**: [Problem statement]
**Key Points**:
- [Pain point 1]
- [Pain point 2]
- [Pain point 3]
**Data Point**: [Supporting statistic]
**Speaker Notes**: [What to say]

[Continue for all 10-12 slides...]

---

## Appendix Slides (if needed)
- Detailed financials
- Technical architecture
- Customer case studies
- Market research sources
```

## Example

**Input**: `/create-pitch-deck B2B SaaS for automated expense management. Pre-seed, raising $500K. Have 10 paying customers, $5K MRR, 2 technical co-founders from Google.`

**Output**: Complete 10-slide deck with:
- Title: "Killing expense reports forever"
- Problem: Manual expense processes cost enterprises $58 per report
- Solution: AI-powered receipt scanning and auto-categorization
- Market: $10B expense management market
- Traction: 10 customers, $5K MRR, 40% MoM growth
- etc.

---

Apply immediately to user's input.

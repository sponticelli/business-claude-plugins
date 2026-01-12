---
name: sop-generator
description: Create a detailed Standard Operating Procedure document for any business process
---

# SOP Generator

Create comprehensive Standard Operating Procedures (SOPs) that are clear, actionable, and maintainable.

## Usage

```
/sop-generator [process name and description]
```

Provide details about:
1. What process needs documentation?
2. Who performs this process?
3. When/how often is it performed?
4. What triggers the process?
5. What is the desired outcome?

## Process

1. **Define Scope and Purpose**
   - Clear objective statement
   - Who this SOP is for
   - When to use this SOP
   - What success looks like

2. **Identify Prerequisites**
   - Required access/permissions
   - Necessary tools and systems
   - Required knowledge/training
   - Dependencies on other processes

3. **Document Step-by-Step Procedure**
   - Sequential numbered steps
   - Decision points with clear criteria
   - Expected outcomes at each step
   - Screenshots/examples where helpful

4. **Define Exception Handling**
   - Common error scenarios
   - Escalation procedures
   - Workarounds for known issues

5. **Establish Governance**
   - Owner and reviewers
   - Update frequency
   - Version control

## Output Format

```markdown
# SOP: [Process Name]

| Field | Value |
|-------|-------|
| **Document ID** | SOP-[XXX]-[YYY] |
| **Version** | 1.0 |
| **Effective Date** | [Date] |
| **Owner** | [Role/Name] |
| **Last Review** | [Date] |
| **Next Review** | [Date + 6 months] |

## 1. Purpose
[Clear statement of why this SOP exists and what it achieves]

## 2. Scope
- **Applies to**: [Roles/teams this applies to]
- **Frequency**: [How often this process runs]
- **Triggers**: [What initiates this process]

## 3. Prerequisites

### Required Access
- [ ] [System/Tool 1]
- [ ] [System/Tool 2]

### Required Knowledge
- [Skill/training requirement]

### Dependencies
- [Other processes that must complete first]

## 4. Definitions
| Term | Definition |
|------|------------|
| [Term] | [Definition] |

## 5. Procedure

### Step 1: [Step Name]
**Owner**: [Role]
**Time**: [Expected duration]

1. [Detailed action]
2. [Detailed action]

**Expected Result**: [What success looks like]

> **Note**: [Any important considerations]

### Step 2: [Step Name]
...

### Decision Point: [Decision Name]
**Criteria**:
- If [condition A] → Go to Step [X]
- If [condition B] → Go to Step [Y]
- If [unclear] → Escalate to [Role]

## 6. Exception Handling

### Error: [Error Type 1]
**Symptoms**: [How to recognize this error]
**Resolution**:
1. [Step to resolve]
2. [Step to resolve]
**Escalation**: If unresolved after [time], contact [Role]

### Error: [Error Type 2]
...

## 7. RACI Matrix

| Step | Responsible | Accountable | Consulted | Informed |
|------|-------------|-------------|-----------|----------|
| Step 1 | [Role] | [Role] | [Role] | [Role] |
| Step 2 | [Role] | [Role] | [Role] | [Role] |

## 8. Related Documents
- [Link to related SOP]
- [Link to system documentation]
- [Link to training materials]

## 9. Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | [Date] | [Name] | Initial release |

## 10. Approval

| Role | Name | Date | Signature |
|------|------|------|-----------|
| Author | | | |
| Reviewer | | | |
| Approver | | | |
```

## Example

**Input**: `/sop-generator Monthly financial close process for our SaaS company`

**Output**: Complete SOP including:
- Revenue recognition steps
- Expense categorization procedures
- Reconciliation checkpoints
- Decision criteria for accruals
- Error handling for discrepancies
- RACI matrix for finance team

---

Apply immediately to user's input. Ask clarifying questions about the specific steps, systems involved, and edge cases if the description is too high-level.

---
name: compliance-assessment
description: Assess compliance requirements and gaps for GDPR, SOC 2, HIPAA, and other frameworks
---

# Compliance Assessment

Assess compliance requirements, identify gaps, and create remediation plans for regulatory frameworks.

## Usage

```
/compliance-assessment [framework and company context]
```

Provide details about:
1. What compliance framework(s) are you assessing (GDPR, SOC 2, HIPAA, etc.)?
2. What type of business/product do you have?
3. What data do you collect and process?
4. What is your current compliance state?
5. What is the driver (customer requirement, regulation, proactive)?

## Process

1. **Determine Applicability**
   - Does this framework apply?
   - What scope/level is required?
   - What is the timeline?

2. **Assess Current State**
   - Existing controls
   - Documentation
   - Gaps

3. **Identify Requirements**
   - Mandatory controls
   - Policies needed
   - Technical requirements
   - Process requirements

4. **Create Remediation Plan**
   - Prioritized actions
   - Resource requirements
   - Timeline

## Output Format

```markdown
# Compliance Assessment: [Framework]

> **Disclaimer**: This assessment is for educational purposes only and does not constitute legal or compliance advice. Please engage qualified compliance professionals for certification readiness.

---

## Assessment Overview

| Field | Value |
|-------|-------|
| **Framework** | [Framework name and version] |
| **Assessment Date** | [Date] |
| **Applicability** | [Applicable/Partially Applicable/Not Applicable] |
| **Current State** | [Compliant/Partially Compliant/Non-Compliant] |
| **Target State** | [Certification/Attestation/Self-Assessment] |
| **Timeline** | [Target date] |

---

## Framework Overview

### What is [Framework]?
[Brief description of the framework and its purpose]

### Why It Matters
- [Business reason 1]
- [Business reason 2]
- [Consequence of non-compliance]

### Applicability Criteria
| Criterion | Your Situation | Applicable? |
|-----------|----------------|-------------|
| [Criterion 1] | [Your situation] | [Yes/No] |
| [Criterion 2] | [Your situation] | [Yes/No] |
| [Criterion 3] | [Your situation] | [Yes/No] |

**Conclusion**: [Framework] [is/is not] applicable because [reasoning]

---

## Scope Definition

### In Scope
| System/Process | Data Types | Users | Notes |
|----------------|------------|-------|-------|
| [System 1] | [Data types] | [User types] | [Notes] |
| [System 2] | [Data types] | [User types] | [Notes] |

### Out of Scope
| System/Process | Reason |
|----------------|--------|
| [System] | [Why excluded] |

### Data Inventory (In Scope)
| Data Category | Source | Storage | Processing | Sensitivity |
|---------------|--------|---------|------------|-------------|
| [Category] | [Where from] | [Where stored] | [How used] | [High/Med/Low] |

---

## Requirements Matrix

### [Domain 1: e.g., Security Policies]

| Requirement ID | Requirement | Current State | Gap | Priority |
|----------------|-------------|---------------|-----|----------|
| [ID] | [Requirement description] | [Met/Partial/Not Met] | [Gap description] | [P1/P2/P3] |
| [ID] | [Requirement description] | [Met/Partial/Not Met] | [Gap description] | [P1/P2/P3] |

**Domain Score**: [X]% compliant

### [Domain 2: e.g., Access Control]

| Requirement ID | Requirement | Current State | Gap | Priority |
|----------------|-------------|---------------|-----|----------|
| [ID] | [Requirement description] | [Met/Partial/Not Met] | [Gap description] | [P1/P2/P3] |

**Domain Score**: [X]% compliant

### [Domain 3: e.g., Data Protection]

| Requirement ID | Requirement | Current State | Gap | Priority |
|----------------|-------------|---------------|-----|----------|
| [ID] | [Requirement description] | [Met/Partial/Not Met] | [Gap description] | [P1/P2/P3] |

**Domain Score**: [X]% compliant

---

## Gap Analysis Summary

### Overall Compliance Score
```
[Framework] Compliance Readiness

Overall: ███████████░░░░░░░░░ 55%

By Domain:
Security Policies:    ██████████████░░░░░░ 70%
Access Control:       ████████████░░░░░░░░ 60%
Data Protection:      ██████░░░░░░░░░░░░░░ 30%
Incident Response:    ████████████████░░░░ 80%
Vendor Management:    ████████░░░░░░░░░░░░ 40%
```

### Critical Gaps
| Gap | Impact | Effort to Close | Priority |
|-----|--------|-----------------|----------|
| [Gap 1] | [Business/compliance impact] | [High/Med/Low] | P1 |
| [Gap 2] | [Business/compliance impact] | [High/Med/Low] | P1 |

### Significant Gaps
| Gap | Impact | Effort to Close | Priority |
|-----|--------|-----------------|----------|
| [Gap 1] | [Impact] | [Effort] | P2 |

### Minor Gaps
| Gap | Impact | Effort to Close | Priority |
|-----|--------|-----------------|----------|
| [Gap 1] | [Impact] | [Effort] | P3 |

---

## Remediation Plan

### Phase 1: Foundation (Weeks 1-4)
*Critical gaps and foundational controls*

| Action | Requirement | Owner | Effort | Deadline |
|--------|-------------|-------|--------|----------|
| [Action 1] | [Req ID] | [Role] | [Hours/Days] | [Date] |
| [Action 2] | [Req ID] | [Role] | [Hours/Days] | [Date] |

**Phase 1 Deliverables**:
- [ ] [Deliverable 1]
- [ ] [Deliverable 2]

### Phase 2: Build (Weeks 5-8)
*Technical controls and processes*

| Action | Requirement | Owner | Effort | Deadline |
|--------|-------------|-------|--------|----------|
| [Action 1] | [Req ID] | [Role] | [Hours/Days] | [Date] |

**Phase 2 Deliverables**:
- [ ] [Deliverable 1]
- [ ] [Deliverable 2]

### Phase 3: Polish (Weeks 9-12)
*Documentation, training, and audit prep*

| Action | Requirement | Owner | Effort | Deadline |
|--------|-------------|-------|--------|----------|
| [Action 1] | [Req ID] | [Role] | [Hours/Days] | [Date] |

**Phase 3 Deliverables**:
- [ ] [Deliverable 1]
- [ ] [Deliverable 2]

---

## Documentation Requirements

### Policies Needed
| Policy | Status | Priority | Template Available |
|--------|--------|----------|-------------------|
| [Policy 1] | [Exists/Draft/Missing] | [P1/P2/P3] | [Yes/No] |
| [Policy 2] | [Exists/Draft/Missing] | [P1/P2/P3] | [Yes/No] |

### Procedures Needed
| Procedure | Status | Priority |
|-----------|--------|----------|
| [Procedure 1] | [Exists/Draft/Missing] | [P1/P2/P3] |

### Evidence/Records Needed
| Record Type | Current State | Required Retention |
|-------------|---------------|-------------------|
| [Record type] | [Capturing/Not Capturing] | [Duration] |

---

## Technical Requirements

### Systems/Tools Needed
| Capability | Current Solution | Gap | Options |
|------------|-----------------|-----|---------|
| [Capability 1] | [Current or None] | [Gap] | [Options] |
| [Capability 2] | [Current or None] | [Gap] | [Options] |

### Infrastructure Changes
| Change | Reason | Effort | Cost Estimate |
|--------|--------|--------|---------------|
| [Change 1] | [Requirement] | [Effort] | $[X] |

---

## Training Requirements

| Audience | Training Topic | Frequency | Status |
|----------|---------------|-----------|--------|
| All employees | [Topic] | [Annual/Onboarding] | [Done/Needed] |
| Technical staff | [Topic] | [Frequency] | [Done/Needed] |
| Management | [Topic] | [Frequency] | [Done/Needed] |

---

## Vendor/Third-Party Assessment

### Critical Vendors (Access to in-scope data)
| Vendor | Service | Data Access | Compliance Status | Gap |
|--------|---------|-------------|-------------------|-----|
| [Vendor] | [Service] | [Data types] | [Their compliance] | [Your gap] |

### Vendor Requirements
- [ ] Data Processing Agreements in place
- [ ] Security questionnaires completed
- [ ] Compliance certifications obtained
- [ ] Right to audit established

---

## Resource Requirements

### Internal Resources
| Role | Time Required | Current Availability |
|------|--------------|---------------------|
| [Role] | [Hours/Weeks] | [Available/Partial/Unavailable] |

### External Resources
| Resource | Purpose | Estimated Cost |
|----------|---------|----------------|
| Compliance consultant | Gap remediation | $[X] |
| Auditor | Certification audit | $[X] |
| Legal counsel | Policy review | $[X] |
| Tools/Software | [Purpose] | $[X]/year |

### Total Budget Estimate
| Category | Estimate |
|----------|----------|
| Consulting | $[X] |
| Tools | $[X] |
| Audit | $[X] |
| Internal time | [X] hours |
| **Total** | $[X] |

---

## Timeline to Compliance

```
Week 1-4    Week 5-8    Week 9-12   Week 13+
|-----------|-----------|-----------|---------|
[Foundation ][Build      ][Polish    ][Audit   ]
 Policies    Tech        Docs        Ready
 Critical    Controls    Training
 Gaps
```

**Target Audit/Certification Date**: [Date]

---

## Risk Assessment

### Risks to Compliance Timeline
| Risk | Likelihood | Impact | Mitigation |
|------|------------|--------|------------|
| [Risk 1] | [H/M/L] | [H/M/L] | [Strategy] |
| [Risk 2] | [H/M/L] | [H/M/L] | [Strategy] |

### Residual Risks (Post-Compliance)
| Risk | Description | Acceptance/Mitigation |
|------|-------------|----------------------|
| [Risk] | [Description] | [Strategy] |

---

## Ongoing Compliance

### Monitoring Requirements
| What to Monitor | Frequency | Tool/Process |
|-----------------|-----------|--------------|
| [Item] | [Continuous/Daily/Weekly] | [How] |

### Review Cadence
| Review | Frequency | Owner |
|--------|-----------|-------|
| Policy review | Annual | [Role] |
| Access review | Quarterly | [Role] |
| Training | Annual | [Role] |
| Full assessment | Annual | [Role] |

---

## Next Steps

1. [ ] [Immediate action 1]
2. [ ] [Immediate action 2]
3. [ ] [Immediate action 3]
```

## Example

**Input**: `/compliance-assessment SOC 2 Type II readiness for our B2B SaaS product, currently have no formal security program`

**Output**: Complete SOC 2 assessment with:
- Trust Services Criteria requirements matrix
- Gap analysis showing ~30% current compliance
- Critical gaps: no security policies, no access reviews, no incident response
- 16-week remediation roadmap
- Budget estimate ~$50-100K for first certification
- Recommended compliance automation tools

---

Apply immediately to user's input. Ask clarifying questions about specific framework, data handling, or current controls if needed.

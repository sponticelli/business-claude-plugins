---
name: contract-review
description: Review contracts to identify key terms, risks, and negotiation points
---

# Contract Review

Systematic contract review to identify key terms, potential risks, and negotiation opportunities.

## Usage

```
/contract-review [contract type and key concerns]
```

Provide details about:
1. What type of contract (SaaS agreement, vendor contract, employment, etc.)?
2. Are you the drafter or reviewer?
3. What are your main concerns?
4. What is the deal value/importance?
5. Any specific terms you want to focus on?

## Process

1. **Identify Contract Type**
   - Categorize the agreement
   - Standard vs. negotiated
   - Relative leverage

2. **Review Key Terms**
   - Essential provisions
   - Risk-bearing clauses
   - Missing provisions

3. **Assess Risks**
   - Liability exposure
   - Operational impact
   - Compliance concerns

4. **Develop Negotiation Strategy**
   - Must-haves
   - Nice-to-haves
   - Trade-offs

## Output Format

```markdown
# Contract Review: [Contract Type]

> **Disclaimer**: This review is for educational purposes only and does not constitute legal advice. Please have significant contracts reviewed by a qualified attorney.

---

## Review Summary

| Field | Assessment |
|-------|------------|
| **Contract Type** | [Type] |
| **Your Position** | [Buyer/Seller/Licensor/Licensee/etc.] |
| **Risk Level** | [Low/Medium/High] |
| **Recommendation** | [Sign/Negotiate/Do Not Sign] |
| **Key Concerns** | [Top 2-3 issues] |

---

## Contract Overview

### Parties
| Party | Role | Notes |
|-------|------|-------|
| [Party A] | [Role] | [Your company or counterparty] |
| [Party B] | [Role] | [Your company or counterparty] |

### Purpose
[Brief description of what this contract is for]

### Key Commercial Terms
| Term | Value | Notes |
|------|-------|-------|
| Contract Value | $[X] | [Total or recurring] |
| Term | [Duration] | [Auto-renew?] |
| Payment Terms | [Terms] | [Net 30, etc.] |

---

## Term-by-Term Analysis

### 1. Scope / Deliverables
**Current Language Summary**: [What the contract says]

**Assessment**: [Good/Concerning/Missing]

**Issues**:
- [Issue 1]
- [Issue 2]

**Recommendation**: [Keep as-is / Modify / Add]

---

### 2. Term & Termination
**Current Language Summary**: [Duration, renewal, termination rights]

**Assessment**: [Good/Concerning/Missing]

| Aspect | Current | Concern Level | Issue |
|--------|---------|---------------|-------|
| Initial Term | [X] | [Low/Med/High] | [Issue if any] |
| Renewal | [Auto/Manual] | [Low/Med/High] | [Issue if any] |
| Termination for Convenience | [Yes/No, notice period] | [Low/Med/High] | [Issue if any] |
| Termination for Cause | [Terms] | [Low/Med/High] | [Issue if any] |

**Recommendation**: [Specific changes]

---

### 3. Fees & Payment
**Current Language Summary**: [Pricing, payment terms, increases]

**Assessment**: [Good/Concerning/Missing]

| Aspect | Current | Concern Level | Issue |
|--------|---------|---------------|-------|
| Pricing | $[X] | [Low/Med/High] | [Issue if any] |
| Payment Terms | [Terms] | [Low/Med/High] | [Issue if any] |
| Price Increases | [Terms] | [Low/Med/High] | [Issue if any] |
| Late Fees | [Terms] | [Low/Med/High] | [Issue if any] |

**Recommendation**: [Specific changes]

---

### 4. Representations & Warranties
**Current Language Summary**: [What each party warrants]

**Assessment**: [Good/Concerning/Missing]

**Your Warranties**:
- [Warranty 1]: [Concern level]
- [Warranty 2]: [Concern level]

**Their Warranties**:
- [Warranty 1]: [Adequate/Need more]
- [Warranty 2]: [Adequate/Need more]

**Missing Warranties**:
- [Warranty that should be included]

**Recommendation**: [Specific changes]

---

### 5. Indemnification
**Current Language Summary**: [Who indemnifies whom for what]

**Assessment**: [Good/Concerning/Missing]

| Indemnity | From | To | Scope | Concern |
|-----------|------|-----|-------|---------|
| [Type] | [Party] | [Party] | [Scope] | [Level] |
| [Type] | [Party] | [Party] | [Scope] | [Level] |

**Red Flags**:
- [ ] Unlimited indemnity obligation
- [ ] Broad scope without carve-outs
- [ ] No mutual indemnification
- [ ] No cap related to contract value

**Recommendation**: [Specific changes]

---

### 6. Limitation of Liability
**Current Language Summary**: [Caps and exclusions]

**Assessment**: [Good/Concerning/Missing]

| Aspect | Current | Market Standard | Gap |
|--------|---------|-----------------|-----|
| Direct Damages Cap | [X] | 12-24 months fees | [Gap] |
| Consequential Damages | [Excluded/Included] | Typically excluded | [Gap] |
| Carve-outs | [What's carved out] | IP, confidentiality, indemnity | [Gap] |

**Red Flags**:
- [ ] No cap on your liability
- [ ] Their liability capped too low
- [ ] Consequential damages not excluded
- [ ] Carve-outs that swallow the cap

**Recommendation**: [Specific changes]

---

### 7. Intellectual Property
**Current Language Summary**: [IP ownership, licenses]

**Assessment**: [Good/Concerning/Missing]

| Aspect | Current | Concern Level | Issue |
|--------|---------|---------------|-------|
| Pre-existing IP | [Treatment] | [Low/Med/High] | [Issue if any] |
| Developed IP | [Ownership] | [Low/Med/High] | [Issue if any] |
| License Grant | [Scope] | [Low/Med/High] | [Issue if any] |
| License Restrictions | [Terms] | [Low/Med/High] | [Issue if any] |

**Recommendation**: [Specific changes]

---

### 8. Confidentiality
**Current Language Summary**: [What's confidential, obligations]

**Assessment**: [Good/Concerning/Missing]

| Aspect | Current | Market Standard | Gap |
|--------|---------|-----------------|-----|
| Definition | [Scope] | Appropriately defined | [Gap] |
| Obligations | [Terms] | Reasonable care | [Gap] |
| Exceptions | [What's excepted] | Standard exceptions | [Gap] |
| Term | [Duration] | 3-5 years typical | [Gap] |

**Recommendation**: [Specific changes]

---

### 9. Data Protection & Security
**Current Language Summary**: [Data handling, security]

**Assessment**: [Good/Concerning/Missing]

| Aspect | Current | Required | Gap |
|--------|---------|----------|-----|
| Data ownership | [Terms] | You own your data | [Gap] |
| Data Processing Agreement | [Included/Missing] | Required for GDPR | [Gap] |
| Security standards | [Terms] | Appropriate for data type | [Gap] |
| Breach notification | [Terms] | 72 hours typical | [Gap] |
| Data portability | [Terms] | Export capability | [Gap] |

**Recommendation**: [Specific changes]

---

### 10. Dispute Resolution
**Current Language Summary**: [How disputes are handled]

**Assessment**: [Good/Concerning/Missing]

| Aspect | Current | Your Preference | Issue |
|--------|---------|-----------------|-------|
| Governing Law | [Jurisdiction] | [Your preference] | [Issue if any] |
| Venue | [Location] | [Your preference] | [Issue if any] |
| Method | [Arbitration/Litigation] | [Your preference] | [Issue if any] |
| Class Action Waiver | [Yes/No] | [Your preference] | [Issue if any] |

**Recommendation**: [Specific changes]

---

## Risk Assessment

### High Risk Items
| Item | Risk | Potential Impact | Mitigation |
|------|------|------------------|------------|
| [Item] | [Description] | [$ or operational] | [How to address] |

### Medium Risk Items
| Item | Risk | Potential Impact | Mitigation |
|------|------|------------------|------------|
| [Item] | [Description] | [$ or operational] | [How to address] |

### Acceptable Risks
| Item | Why Acceptable |
|------|----------------|
| [Item] | [Reasoning] |

---

## Missing Provisions

| Provision | Why Needed | Suggested Language |
|-----------|------------|-------------------|
| [Provision] | [Reason] | [Brief suggestion] |
| [Provision] | [Reason] | [Brief suggestion] |

---

## Negotiation Strategy

### Must-Have Changes
*Do not sign without these*
1. [Change 1]: [Rationale]
2. [Change 2]: [Rationale]

### Should-Have Changes
*Push for these*
1. [Change 1]: [Rationale]
2. [Change 2]: [Rationale]

### Nice-to-Have Changes
*Ask but willing to concede*
1. [Change 1]: [Rationale]

### Potential Trade-offs
| If They Want... | You Could Ask For... |
|-----------------|---------------------|
| [Their ask] | [Your ask] |

---

## Red Flags Checklist

- [ ] Unlimited liability exposure
- [ ] One-sided indemnification
- [ ] Automatic renewal without notice
- [ ] Price increase without cap
- [ ] Broad IP assignment
- [ ] Unfavorable governing law/venue
- [ ] No termination for convenience
- [ ] Audit rights without limits
- [ ] Non-standard confidentiality terms
- [ ] Missing data protection terms

---

## Recommendation

### Overall Assessment
**[Sign As-Is / Negotiate Changes / Do Not Sign / Consult Attorney]**

**Rationale**: [2-3 sentences explaining recommendation]

### Next Steps
1. [Specific action]
2. [Specific action]
3. [Specific action]
```

## Example

**Input**: `/contract-review SaaS vendor agreement, we're the customer, annual contract worth $50K, concerned about data security`

**Output**: Complete contract review with:
- Term-by-term analysis of standard SaaS provisions
- Deep dive on data security and privacy terms
- Risk assessment highlighting liability exposure
- Missing DPA flagged as critical
- Negotiation strategy with must-haves around data handling

---

Apply immediately to user's input. Ask clarifying questions about contract type, value, or specific concerns if needed.

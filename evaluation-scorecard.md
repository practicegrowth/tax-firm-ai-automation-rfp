# AI & Automation Vendor Evaluation Scorecard

> Use this scorecard to evaluate vendor proposals consistently across your evaluation team. Each criterion is scored on a 1–5 scale. Multiply the score by the weight to get the weighted score. The vendor with the highest total weighted score is the strongest candidate.

---

## Scoring Instructions

1. **Review each proposal independently** before discussing as a team
2. **Score each criterion** using the rubric below (1 = Poor, 5 = Excellent)
3. **Document your reasoning** in the Notes column — this is critical for tie-breaking and for explaining the decision to stakeholders
4. **Calculate weighted scores** automatically or manually
5. **Compare scores across evaluators** — large discrepancies indicate areas that need discussion

### Scoring Scale

| Score | Rating | Meaning |
|-------|--------|---------|
| **5** | Excellent | Exceeds requirements significantly. Clear differentiator. |
| **4** | Good | Meets all requirements with some strengths above baseline. |
| **3** | Acceptable | Meets minimum requirements. No significant strengths or weaknesses. |
| **2** | Below Average | Meets some requirements but has notable gaps. |
| **1** | Poor | Does not meet minimum requirements. Significant concerns. |

---

## Evaluation Scorecard

### Vendor: _________________________

### Evaluator: _________________________

### Date: _________________________

| # | Criterion | Weight | Score (1-5) | Weighted Score | Notes |
|---|-----------|--------|-------------|----------------|-------|
| 1 | Domain Expertise | 25% | | | |
| 2 | AI Capability & Accuracy | 20% | | | |
| 3 | Integration Ease | 12% | | | |
| 4 | CRM Integration & Data Flow | 10% | | | |
| 5 | Compliance & Security | 15% | | | |
| 6 | Pricing Model | 8% | | | |
| 7 | Implementation Timeline | 7% | | | |
| 8 | Support Quality | 3% | | | |
| | **TOTAL** | **100%** | | **/5.0** | |

---

## Detailed Evaluation Rubrics

### 1. Domain Expertise (Weight: 25%)

**What we're evaluating:** Does the vendor truly understand how tax practices operate?

| Score | Evidence |
|-------|----------|
| **5** | Vendor has 10+ tax practice clients of similar size. Demonstrates deep knowledge of tax workflows, peak season pressures, professional services regulations, and firm economics. Explicitly understands IRS Circular 230 constraints on AI-assisted tax advice and marketing. Distinguishes between credential types (EA, CPA, JD) and tailors intake/scripts accordingly. Recognizes that tax prospects are often in distress (IRS notices, audit anxiety, deadline pressure) and designs intake around empathy-first, trust-building conversations. Case studies show measurable results in tax contexts. Team includes former tax professionals. |
| **4** | Vendor has 5–10 tax practice clients. Understands core tax workflows and can speak intelligently about tax season challenges. Aware of Circular 230 implications for AI-generated content and client communications. Understands credential distinctions at a high level. Recognizes distress-driven buyer psychology but may not have fully operationalized it in scripts. Case studies from adjacent professional services. Some team members have tax background. |
| **3** | Vendor has 1–5 tax practice clients. Basic understanding of tax workflows but relies on general professional services experience. Limited awareness of Circular 230 or credential-specific practice rights. Treats prospects as standard B2B buyers rather than distressed individuals seeking tax resolution. Case studies from other industries. No tax-specific team members. |
| **2** | Vendor has no tax practice clients. Generic understanding of business workflows. Proposes solutions that don't account for tax-specific requirements (e.g., engagement letters, conflict checks, quality review). No awareness of Circular 230 constraints or credential distinctions. Treats all prospects identically regardless of their emotional state or urgency. |
| **1** | Vendor has no relevant industry experience. Proposes generic AI solutions without understanding of professional services constraints, compliance requirements, or seasonal workflows. No knowledge of Circular 230, credential types, or the distress-driven nature of tax client acquisition. |

**Key evaluation questions:**
- How many tax practice clients does the vendor currently serve?
- Can they describe the typical tax season workflow and where AI fits?
- Do they understand engagement letters, conflict checks, and quality review processes?
- Have they worked with firms of similar size and complexity?
- Do they understand the regulatory environment (IRS Circular 230, state tax board rules, and how those constrain AI-generated tax content and marketing claims)?
- Can they speak to the specific pain points of tax practices (not generic business pain)?
- Does the vendor understand the distinction between Enrolled Agents (EA), CPAs, and Tax Attorneys (JD) — and how that affects who can represent clients before the IRS, what credentials signal to prospects, and how intake scripts should be tailored?
- Does the vendor recognize that most inbound tax prospects are in distress (facing IRS notices, audit anxiety, filing deadline pressure, or unfiled return guilt)? How does their intake flow account for this emotional state — empathy-first language, reassurance before qualification, trust-building before scheduling?
- Can the vendor provide examples of scripts or conversation flows designed specifically for distressed tax prospects rather than generic lead intake?

---

### 2. AI Capability & Accuracy (Weight: 20%)

**What we're evaluating:** How good is the AI? Is it accurate, transparent, and reliable enough for professional services use?

| Score | Evidence |
|-------|----------|
| **5** | Vendor provides documented accuracy benchmarks (95%+ for standard tasks). Transparent about which models are used and why. Robust hallucination safeguards with confidence scoring. Human-in-the-loop controls are configurable and easy to use. Clear process for continuous improvement. Voice agent quality is indistinguishable from human for standard interactions. |
| **4** | Vendor provides accuracy data (90–95%). Transparent about model choices. Good hallucination controls with some limitations. Human override is available but may require technical setup. Voice quality is good with occasional artifacts. |
| **3** | Vendor provides limited accuracy data (85–90%). Some transparency about models. Basic hallucination controls. Human override available but clunky. Voice quality is acceptable but clearly AI-generated. |
| **2** | Vendor provides minimal accuracy data (<85%). Opaque about model choices. Weak hallucination controls — AI sometimes generates plausible-sounding but incorrect information. Human override is difficult or requires developer involvement. |
| **1** | No accuracy data provided. No transparency about models. No meaningful hallucination safeguards. No human override capability. Voice quality is poor with frequent errors. |

**Key evaluation questions:**
- What accuracy rates does the vendor achieve for document processing, voice agents, and chatbot responses?
- How does the vendor measure and report accuracy?
- Which AI models are used? (proprietary, open-source, specific LLMs)
- What happens when the AI doesn't know the answer? (refusal, escalation, guessing?)
- How are hallucination incidents tracked and resolved?
- Can staff override AI decisions without technical expertise?
- What is the voice agent latency? How natural does it sound?
- Does the AI improve over time? How?

---

### 3. Integration Ease (Weight: 12%)

**What we're evaluating:** How easily does the solution connect to the firm's existing technology stack?

| Score | Evidence |
|-------|----------|
| **5** | Pre-built connectors for all required systems (practice management, tax software, CRM, calendar, email). API is well-documented with SDKs. Implementation timeline for integrations is <2 weeks. Data migration support is comprehensive. Ongoing sync is reliable with real-time or near-real-time updates. |
| **4** | Pre-built connectors for most required systems. Some custom configuration needed. API is documented. Implementation timeline is 2–4 weeks. Data migration support is adequate. Sync is reliable with minor delays acceptable. |
| **3** | Pre-built connectors for some systems. Others require Zapier or custom API work. API documentation is basic. Implementation timeline is 4–8 weeks. Data migration requires significant manual effort. Sync is batch-based with daily updates. |
| **2** | Few pre-built connectors. Most integrations require custom development. API documentation is poor or incomplete. Implementation timeline is 8+ weeks. Data migration is largely manual. Sync is unreliable or requires manual triggering. |
| **1** | No pre-built connectors. All integrations are custom. No public API or documentation is inadequate. Implementation timeline is uncertain. No data migration support. No reliable sync mechanism. |

**Key evaluation questions:**
- Which practice management systems have pre-built connectors? (Karbon, Canopy, Jetpack, etc.)
- Which tax software integrations are available? (Drake, CCH Axcess, UltraTax)
- What is the API documentation quality? Are there SDKs?
- How long does integration typically take?
- What data migration support is provided?
- Is sync real-time, near-real-time, or batch?
- What happens when an integration breaks? Who fixes it?
- Are there additional costs for integrations?

---

### 4. CRM Integration & Data Flow (Weight: 10%)

**What we're evaluating:** How well does the AI solution integrate with and leverage the firm's CRM as the central nervous system?

| Score | Evidence |
|-------|----------|
| **5** | AI reads and writes to CRM in real-time. Can access contact records, pipeline stages, engagement history, and custom fields. Can create/update contacts, log interactions, update pipeline stages, create tasks, and trigger workflows. Books appointments directly into calendar. Bi-directional sync with conflict resolution. Complete audit trail of all AI actions. Performance metrics tracked in CRM. |
| **4** | AI integrates with CRM for most operations. Can read contact data and write interaction logs. Books appointments. Syncs in near-real-time. Audit trail available. Some limitations on custom fields or workflow triggers. |
| **3** | Basic CRM integration. Can log interactions and read contact data. Appointment booking requires manual steps. Sync is batch-based (hourly or daily). Limited audit trail. Cannot trigger workflows or access custom fields. |
| **2** | Minimal CRM integration. Can only log basic interaction data. No appointment booking. Sync is manual or very delayed. No audit trail. Cannot read or write most CRM data. |
| **1** | No CRM integration. AI operates in isolation. All data must be manually transferred between systems. No audit trail. Cannot access or update CRM data. |

**Key evaluation questions:**
- Can the AI read contact records, pipeline stages, and engagement history from our CRM?
- Can the AI create/update contacts, log interactions, and update pipeline stages?
- Can the AI book appointments directly into our calendar?
- Can the AI trigger workflows based on conversation outcomes?
- Is the sync real-time, near-real-time, or batch-based?
- How are data conflicts resolved between AI and CRM?
- Is there a complete audit trail of all AI actions in the CRM?
- Can we see AI performance metrics (conversion rates, response times) in the CRM?
- What happens if the CRM is down? Does the AI queue data or lose it?

---

### 5. Compliance & Security (Weight: 15%)

**What we're evaluating:** Does the vendor meet the security and compliance requirements for handling sensitive client data in a tax practice, including IRS Circular 230 constraints on AI-assisted tax advice and marketing?

| Score | Evidence |
|-------|----------|
| **5** | Current SOC 2 Type II report available. AES-256 encryption at rest, TLS 1.3 in transit. MFA and SSO supported. Comprehensive audit trails with tamper detection. Documented incident response plan with <24hr notification. Understands IRS Publication 4557 requirements. Explicitly addresses IRS Circular 230 constraints — understands that AI cannot provide tax advice without practitioner review, that marketing claims must not be misleading, and that credential-specific practice rights (EA/CPA/JD) must be respected in all client-facing communications. TCPA compliance: prior consent management, DNC registry checks, call time restrictions, AI disclosure requirements. Customer-managed encryption keys available. |
| **4** | SOC 2 Type II available. Strong encryption (AES-256, TLS 1.2+). MFA supported. Good audit trails. Documented incident response with <48hr notification. Basic understanding of tax compliance requirements including awareness of Circular 230 implications for AI-generated content. TCPA compliance mechanisms in place but may lack full automation. |
| **3** | SOC 2 Type I or SOC 3 available. Adequate encryption. MFA available. Basic audit trails. Incident response plan exists but timeline is unclear. Limited understanding of tax-specific compliance. Vague awareness of Circular 230 but no operational safeguards. TCPA compliance is manual or incomplete. |
| **2** | No SOC 2 report. Encryption meets minimum standards. MFA is basic or limited. Audit trails are incomplete. Incident response plan is informal or undocumented. No awareness of tax compliance requirements or Circular 230 constraints. No TCPA compliance mechanisms. |
| **1** | No security certifications. Weak encryption. No MFA. No audit trails. No incident response plan. No understanding of professional services compliance requirements. No knowledge of IRS Circular 230 or credential handling. No TCPA compliance. |

**Key evaluation questions:**
- Is a current SOC 2 Type II report available for review?
- What encryption standards are used for data at rest and in transit?
- Is MFA supported? What methods? (TOTP, hardware key, SMS)
- Is SSO supported? (SAML, OAuth)
- How comprehensive are the audit trails? Can they be exported?
- What is the incident response plan? Notification timeline?
- Does the vendor understand IRS Publication 4557?
- Does the vendor understand IRS Circular 230 and how it constrains AI-assisted tax advice and marketing? Specifically: Can the AI generate tax advice without practitioner review? How does the vendor ensure marketing claims comply with Circular 230's prohibition on misleading statements?
- How does the vendor handle credential distinctions (EA, CPA, JD) in client-facing communications? Are scripts and marketing materials reviewed to ensure they don't overstate practice rights or make unauthorized claims?
- **TCPA compliance:** Does the system obtain and document prior express written consent before making automated calls or sending texts? How does it check the National Do Not Call Registry? Does it enforce 8 AM – 9 PM call time restrictions? Does it require AI voice agents to disclose they are automated? Can you provide written TCPA certification and indemnification?
- Is client data used to train AI models? (Must be NO)
- Where is data stored? Can residency be restricted?
- What is the data deletion process?

---

### 6. Pricing Model (Weight: 8%)

**What we're evaluating:** Is the pricing transparent, fair, and aligned with the firm's budget and growth plans?

| Score | Evidence |
|-------|----------|
| **5** | Pricing is fully transparent with no hidden fees. Total cost of ownership is clear and competitive. Pricing scales predictably with firm growth. No long-term lock-in required. ROI projections are realistic and backed by case studies. Payment terms are flexible. |
| **4** | Pricing is mostly transparent with minor hidden fees identified early. TCO is reasonable. Pricing scales reasonably. Contract terms are fair (1–2 years). ROI projections are plausible. |
| **3** | Pricing is somewhat transparent but some fees are unclear until implementation. TCO is average. Pricing scaling is unclear. Contract requires 2–3 year commitment. ROI projections are optimistic but not unreasonable. |
| **2** | Pricing has significant hidden fees or unclear components. TCO is higher than expected after full discovery. Pricing scaling is punitive. Contract requires 3+ year commitment with harsh early termination. ROI projections are unrealistic. |
| **1** | Pricing is opaque or significantly higher than competitors. TCO is prohibitive. No pricing flexibility. Long-term lock-in with punitive terms. No credible ROI justification. |

**Key evaluation questions:**
- What is the total cost of ownership for year 1, year 2, and year 3?
- Are there hidden fees? (setup, training, overages, support, integrations)
- How does pricing scale as the firm grows? (more clients, more staff, more workflows)
- What is the contract term? Early termination provisions?
- Are there price increase commitments? (annual cap?)
- What ROI can the firm realistically expect? Is it backed by case studies?
- What payment terms are available?
- Are there discounts for annual payment?

---

### 7. Implementation Timeline (Weight: 7%)

**What we're evaluating:** Is the implementation plan realistic, well-structured, and low-risk — and does it account for tax season timing?

| Score | Evidence |
|-------|----------|
| **5** | Phased implementation with clear milestones. Pilot period of 30–60 days with defined success criteria. Realistic timeline (8–12 weeks to full deployment). Comprehensive training plan. Data migration is well-planned with validation. Rollback plan exists. Dedicated implementation manager assigned. Explicitly accounts for tax season timing — avoids go-live during peak season (Jan–Apr) unless firm specifically requests it, plans around filing deadlines (Apr 15, Oct 15), and schedules training during slower periods. |
| **4** | Phased approach with milestones. Pilot period included. Timeline is reasonable (10–16 weeks). Training plan is adequate. Data migration plan is solid. Some rollback capability. Acknowledges tax season timing and proposes a go-live window that avoids peak pressure periods. |
| **3** | Basic implementation plan with milestones. Pilot may be included but success criteria are vague. Timeline is 12–20 weeks. Training is limited. Data migration plan is basic. Limited rollback capability. Does not explicitly address tax season timing but does not propose an obviously problematic go-live date. |
| **2** | Implementation plan is vague or overly aggressive. No pilot period. Timeline is unrealistic (<8 weeks or >24 weeks). Minimal training. Data migration is poorly planned. No rollback plan. Proposes go-live during peak tax season without acknowledging the risk or offering mitigation. |
| **1** | No clear implementation plan. No pilot. Timeline is undefined or unachievable. No training plan. No data migration support. No rollback capability. No awareness of tax season timing or filing deadline pressures. |

**Key evaluation questions:**
- Is the implementation phased? What are the phases and milestones?
- Is there a pilot period? How long? What are the success criteria?
- What is the total timeline from kickoff to full deployment?
- What training is provided? For administrators and end users?
- How is data migration handled? Who is responsible?
- Is there a rollback plan if the implementation fails?
- Who is the implementation manager? What is their experience?
- What happens if the timeline slips? Who absorbs the cost?
- Does the vendor account for tax season timing? Will go-live be scheduled outside peak season (Jan–Apr) unless the firm specifically requests otherwise?
- Does the vendor understand key filing deadlines (Apr 15, Oct 15, Sep 15 for extensions) and avoid scheduling disruptive changes around those dates?
- Is training scheduled during slower periods to maximize staff availability and retention?

---

### 8. Support Quality (Weight: 3%)

**What we're evaluating:** Will the vendor provide responsive, knowledgeable support when the firm needs it?

| Score | Evidence |
|-------|----------|
| **5** | 24/7 support with <1hr response time for critical issues. Dedicated account manager with tax industry expertise. Comprehensive knowledge base and training resources. Proactive monitoring and issue prevention. Regular business reviews. Escalation path to engineering when needed. |
| **4** | Extended business hours support with <4hr response time. Account manager assigned (may not be industry-specific). Good knowledge base. Regular check-ins. Clear escalation path. |
| **3** | Business hours support with <8hr response time. No dedicated account manager but consistent support team. Basic knowledge base. Reactive support model. Escalation path exists but is slow. |
| **2** | Limited support hours. Response times are >24hr. No account manager. Minimal documentation. Support quality is inconsistent. Escalation is difficult. |
| **1** | Poor support availability. Response times are days. No account management. No documentation. Support is a significant weakness based on references. |

**Key evaluation questions:**
- What are the support hours? (24/7, extended business, business only)
- What are the response time SLAs by severity level?
- Is a dedicated account manager provided?
- What is the account manager's experience with tax practices?
- What self-service resources are available? (knowledge base, community, training)
- How are issues escalated? What is the path to engineering?
- Are regular business reviews included?
- What do references say about support quality?

---

## Summary & Recommendation

### Total Scores

| Vendor | Domain Expertise | AI Capability | Integration | Compliance | Pricing | Timeline | Support | **Total** |
|--------|-----------------|---------------|-------------|------------|---------|----------|---------|-----------|
| Vendor A | /5 | /5 | /5 | /5 | /5 | /5 | /5 | **/5.0** |
| Vendor B | /5 | /5 | /5 | /5 | /5 | /5 | /5 | **/5.0** |
| Vendor C | /5 | /5 | /5 | /5 | /5 | /5 | /5 | **/5.0** |

### Key Strengths by Vendor

**Vendor A:**
- 
- 
- 

**Vendor B:**
- 
- 
- 

**Vendor C:**
- 
- 
- 

### Key Concerns by Vendor

**Vendor A:**
- 
- 

**Vendor B:**
- 
- 

**Vendor C:**
- 
- 

### Recommendation

**Recommended vendor:** _________________________

**Rationale:**

*[Explain why this vendor scored highest and why they are the best fit for your firm. Address any concerns and explain how they will be mitigated.]*

**Runner-up:** _________________________

**Fallback rationale:**

*[If the recommended vendor falls through during contract negotiation, who is the next choice and why?]*

---

*Evaluator signature: _________________________ Date: ___________*

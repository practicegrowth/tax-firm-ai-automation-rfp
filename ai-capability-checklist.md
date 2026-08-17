# AI Capability Checklist for tax practices

> Use this checklist during vendor demos, technical due diligence, and proof-of-concept evaluations. Each item should be verified with evidence — not just vendor claims. Where possible, test the capability with your own data and workflows.

---

## How to Use This Checklist

- **During vendor demos:** Ask the vendor to demonstrate each capability live
- **During proof of concept:** Test with your actual documents, workflows, and client scenarios
- **During reference checks:** Ask existing clients about their experience with each item
- **Scoring:** Mark each item as ✅ (verified), ⚠️ (partially met / needs clarification), or ❌ (not met / not available)

---

## 1. Model Type & Transparency

| # | Capability | Status | Notes |
|---|-----------|--------|-------|
| 1.1 | Vendor discloses which AI models are used (proprietary, open-source, specific LLMs like GPT-4, Claude, etc.) | | |
| 1.2 | Vendor explains why specific models were chosen for specific tasks | | |
| 1.3 | Model version and update frequency are documented | | |
| 1.4 | Firm can select or switch between models for different use cases | | |
| 1.5 | Vendor is transparent about model limitations and known failure modes | | |
| 1.6 | Product roadmap includes model improvements and is shared with clients | | |
| 1.7 | Vendor discloses if models are fine-tuned on accounting/tax data | | |

**What to ask:** *"Which AI models power your solution? Can you walk me through why you chose each model for each task? What happens when a model is updated — do I get notified?"*

---

## 2. Accuracy Benchmarks & Testing

| # | Capability | Status | Notes |
|---|-----------|--------|-------|
| 2.1 | Vendor provides documented accuracy rates for document processing (by document type) | | |
| 2.2 | Vendor provides accuracy rates for voice agent responses | | |
| 2.3 | Vendor provides accuracy rates for chatbot responses | | |
| 2.4 | Accuracy benchmarks are based on accounting/tax-specific data (not generic benchmarks) | | |
| 2.5 | Vendor can demonstrate accuracy with firm's own sample documents during evaluation | | |
| 2.6 | Accuracy testing methodology is transparent and reproducible | | |
| 2.7 | Vendor tracks accuracy over time and shares trend data with clients | | |
| 2.8 | Accuracy rates meet minimum thresholds: document processing ≥95%, voice ≥90%, chatbot ≥85% | | |

**What to ask:** *"What accuracy rates do you achieve for W-2 extraction, 1099 extraction, and voice appointment scheduling? Can you show me the test methodology? Can we run a proof of concept with our own documents?"*

---

## 3. Hallucination Safeguards

> **Tax-Specific Risk Warning:** In tax practice, a hallucination is not merely an inconvenience — it is a compliance liability. A fabricated IRC section citation, an incorrect filing deadline (e.g., stating April 18 instead of April 15), a wrong depreciation schedule, or a misquoted tax court holding can result in incorrect returns, IRS penalties, malpractice exposure, and Circular 230 sanctions. AI hallucinations in tax must be treated with the same severity as a practitioner signing an erroneous return.

| # | Capability | Status | Notes |
|---|-----------|--------|-------|
| 3.1 | AI provides confidence scores for each response or extraction | | |
| 3.2 | AI refuses to answer when confidence is below a defined threshold (instead of guessing) | | |
| 3.3 | AI escalates to human staff when uncertain | | |
| 3.4 | There is a fact-checking or verification layer for critical outputs | | |
| 3.5 | Hallucination incidents are tracked, logged, and reported to the firm | | |
| 3.6 | There is a clear process for updating the knowledge base when errors are found | | |
| 3.7 | AI responses are grounded in provided context (retrieval-augmented generation) rather than generating from memory alone | | |
| 3.8 | Vendor can demonstrate how the system handles edge cases and ambiguous inputs | | |
| 3.9 | **Tax Code Citation Verification:** AI cross-references all IRC section citations, Treasury Regulation references, and Revenue Ruling/Procedure numbers against authoritative sources before outputting — and flags any citation it cannot verify | | |
| 3.10 | **Filing Deadline Accuracy:** AI uses a maintained calendar of federal and state filing deadlines (including extensions, weekend/holiday shifts, and disaster relief extensions) rather than generating dates from memory — wrong deadlines are among the highest-risk hallucinations in tax | | |
| 3.11 | **State-Specific Rule Guardrails:** AI does not conflate state tax rules (e.g., applying California community property rules to a Texas client, or quoting New York S-corps rules for a Florida engagement) — state-specific outputs are tagged and verified against the correct jurisdiction | | |
| 3.12 | **Penalty & Interest Calculation Controls:** AI-generated penalty abatement arguments, reasonable cause statements, and interest calculations are flagged for human review — these are high-liability outputs where a single wrong number can create malpractice exposure | | |
| 3.13 | **Authoritative Source Anchoring:** AI outputs that cite case law, IRS guidance, or legislative history include verifiable source links (e.g., IRS.gov, CourtListener, Congress.gov) — outputs without source anchoring are blocked or flagged | | |
| 3.14 | **Tax Year Awareness:** AI correctly identifies the applicable tax year for any question and does not apply current-year law retroactively or prior-year law prospectively — year-specific rules (e.g., TCJA provisions, inflation-adjusted brackets) are version-controlled | | |

**What to ask:** *"What happens when the AI doesn't know the answer? Does it guess, refuse, or escalate? How do you prevent the AI from generating plausible-sounding but incorrect tax information — specifically wrong IRC citations, wrong filing deadlines, or wrong state rules? Show me an example of a hallucination safeguard in action. Can you demonstrate what happens when the AI is asked about a tax provision that was repealed or changed?"*

---

## 4. Data Training Practices

| # | Capability | Status | Notes |
|---|-----------|--------|-------|
| 4.1 | Client data is NOT used to train foundation models | | |
| 4.2 | Client data is NOT shared with other clients or used for any purpose beyond serving that client | | |
| 4.3 | Data segregation between clients is technically enforced (not just policy) | | |
| 4.4 | Vendor discloses all sub-processors who may have access to client data | | |
| 4.5 | Firm can opt out of any analytics or usage tracking beyond what's necessary for service delivery | | |
| 4.6 | Vendor provides a Data Processing Agreement (DPA) that addresses training practices | | |

**What to ask:** *"Is my client data used to train your AI models? Is it shared with other clients? Can you show me the technical controls that prevent cross-client data leakage? What sub-processors have access to my data?"*

---

## 5. Human-in-the-Loop Controls

| # | Capability | Status | Notes |
|---|-----------|--------|-------|
| 5.1 | Staff can review AI outputs before they are sent to clients or executed | | |
| 5.2 | Approval workflows are configurable (which actions require human approval) | | |
| 5.3 | Staff can override AI decisions without requiring technical expertise or developer involvement | | |
| 5.4 | Escalation paths are configurable (when AI confidence is low, route to specific staff) | | |
| 5.5 | Staff corrections to AI outputs feed back into system improvement | | |
| 5.6 | Override and correction actions are logged in the audit trail | | |
| 5.7 | Firm can define which AI actions are autonomous vs. requiring approval | | |

**What to ask:** *"Can my staff review and approve AI-generated responses before they go to clients? How easy is it to override an AI decision? Can I configure which actions require human approval? Show me the override workflow."*

---

## 6. Multi-Language Support

| # | Capability | Status | Notes |
|---|-----------|--------|-------|
| 6.1 | AI supports languages relevant to firm's client base | | |
| 6.2 | Language detection is automatic (client doesn't need to select language) | | |
| 6.3 | Quality is consistent across supported languages (not just English) | | |
| 6.4 | Tax terminology is accurately translated (not just general language) | | |
| 6.5 | Voice agents support multiple languages with natural accents | | |
| 6.6 | Firm can add or remove supported languages without technical changes | | |

**What to ask:** *"Which languages do you support? Is the quality consistent across languages or is English significantly better? Can the voice agent handle a client who switches languages mid-conversation?"*

---

## 7. Voice Agent Quality Metrics

| # | Capability | Status | Notes |
|---|-----------|--------|-------|
| 7.1 | Response latency is under 1 second for standard interactions | | |
| 7.2 | Voice quality is natural and indistinguishable from human for standard interactions | | |
| 7.3 | Interruption handling works correctly (AI stops speaking when client interrupts) | | |
| 7.4 | Background noise handling is adequate (client calling from noisy environment) | | |
| 7.5 | Accent and dialect recognition is robust (not limited to standard American English) | | |
| 7.6 | Call transfer to live staff is seamless (no dropped calls, context is preserved) | | |
| 7.7 | Call recording and transcription are available for quality assurance | | |
| 7.8 | Concurrent call capacity meets firm's peak volume requirements | | |
| 7.9 | Voicemail detection works correctly (AI doesn't leave voicemail if not configured to) | | |
| 7.10 | AI can handle common telephony scenarios (hold music, menu systems, transfers) | | |

**What to ask:** *"What is the average response latency? Can you demonstrate interruption handling? How does the voice agent perform with accented English or non-native speakers? What happens when a call needs to be transferred to a live person? Can we test with our actual phone number during evaluation?"*

---

## 8. Document Processing Accuracy

| # | Capability | Status | Notes |
|---|-----------|--------|-------|
| 8.1 | Accuracy rates are provided by document type (W-2, 1099, K-1, bank statements, etc.) | | |
| 8.2 | Handwritten document support is available (if needed) with documented accuracy | | |
| 8.3 | Multi-page documents are handled correctly | | |
| 8.4 | Automatic data validation against known rules (SSN format, date format, math checks) | | |
| 8.5 | Confidence scoring is provided for each extracted field | | |
| 8.6 | Human review queue is available for low-confidence extractions | | |
| 8.7 | Processing speed meets requirements (e.g., <30 seconds per document) | | |
| 8.8 | Bulk processing is supported (upload 100+ documents at once) | | |
| 8.9 | Document classification is accurate (correctly identifies document type) | | |
| 8.10 | Extraction works for both scanned images and digital PDFs | | |

**What to ask:** *"What accuracy do you achieve for each document type we need processed? Can you show me the confidence scoring? How does the human review queue work? Can we process 50 of our actual documents as a test?"*

---

## 9. Continuous Learning & Improvement

| # | Capability | Status | Notes |
|---|-----------|--------|-------|
| 9.1 | System improves over time based on usage patterns and corrections | | |
| 9.2 | Improvement process is transparent (firm can see what changed and why) | | |
| 9.3 | Firm can provide feedback that directly influences improvements | | |
| 9.4 | Model updates don't degrade performance on firm's specific workflows | | |
| 9.5 | Vendor provides release notes explaining model changes | | |
| 9.6 | Firm can test model updates in a sandbox before they go live | | |
| 9.7 | Regression testing is performed before model updates are deployed | | |

**What to ask:** *"How does the system improve over time? When you update your models, how do you ensure it doesn't break my specific workflows? Can I test updates before they go live? How do I provide feedback that influences your roadmap?"*

---

## 10. Failover & Fallback Mechanisms

| # | Capability | Status | Notes |
|---|-----------|--------|-------|
| 10.1 | System has fallback when primary AI model fails (switches to backup model) | | |
| 10.2 | System has fallback when AI is unavailable (routes to human or queues requests) | | |
| 10.3 | Failover is automatic and doesn't require manual intervention | | |
| 10.4 | Failover events are logged and reported to the firm | | |
| 10.5 | System gracefully degrades (partial functionality rather than total failure) | | |
| 10.6 | Disaster recovery plan is documented and tested regularly | | |
| 10.7 | RTO (Recovery Time Objective) and RPO (Recovery Point Objective) are defined and meet firm requirements | | |

**What to ask:** *"What happens when your AI model goes down? Is there automatic failover? How quickly does the system recover? What is your RTO and RPO? Can you show me your disaster recovery plan?"*

---

## 11. CRM Integration & Data Flow

The CRM is the central nervous system of your firm's AI ecosystem. AI agents must read from and write to the CRM to maintain context, track outcomes, and enable intelligent automation.

| # | Capability | Status | Notes |
|---|-----------|--------|-------|
| 11.1 | **Read Capabilities:** AI can access contact records (name, email, phone, firm name, industry, service history) | | |
| 11.2 | AI can retrieve pipeline stage and deal status | | |
| 11.3 | AI can view engagement history (past interactions, notes, attachments) | | |
| 11.4 | AI can check appointment availability and calendar status | | |
| 11.5 | AI can access custom fields and tags for personalization | | |
| 11.6 | **Write Capabilities:** AI can create and update contact records | | |
| 11.7 | AI can log all interactions (calls, chats, emails, tasks completed) | | |
| 11.8 | AI can update pipeline stage based on conversation outcomes | | |
| 11.9 | AI can create tasks and follow-up activities | | |
| 11.10 | AI can add notes and conversation summaries | | |
| 11.11 | AI can trigger workflow automations based on actions | | |
| 11.12 | **Calendar Integration:** AI can check real-time availability across team members | | |
| 11.13 | AI can book appointments directly into calendar | | |
| 11.14 | AI can send calendar invites with meeting details | | |
| 11.15 | AI can handle rescheduling and cancellations | | |
| 11.16 | AI can sync with multiple calendar systems (Google, Outlook) | | |
| 11.17 | **Workflow Triggers:** AI can initiate follow-up sequences based on conversation outcomes | | |
| 11.18 | AI can route leads to appropriate team members | | |
| 11.19 | AI can trigger nurture campaigns for cold leads | | |
| 11.20 | AI can escalate hot leads for immediate human follow-up | | |
| 11.21 | AI can generate tasks for document collection or onboarding | | |
| 11.22 | **Data Synchronization:** Real-time bi-directional sync (not batch processing) | | |
| 11.23 | Conflict resolution rules (which system wins on data conflicts) | | |
| 11.24 | Audit trail of all data changes | | |
| 11.25 | Webhook support for instant updates | | |
| 11.26 | API rate limits that support high-volume operations | | |
| 11.27 | **Reporting & Analytics:** AI agent performance metrics (conversion rates, response times, customer satisfaction) | | |
| 11.28 | Pipeline velocity improvements from AI-assisted workflows | | |
| 11.29 | Lead quality scoring based on AI interactions | | |
| 11.30 | ROI tracking (time saved, revenue generated, costs reduced) | | |

**What to ask:** *"Can your AI read and write to our CRM in real-time? Can it book appointments directly into our calendar? Can it trigger workflows based on conversation outcomes? How does it handle data conflicts? Can we see the audit trail of all AI actions?"*

---

## 12. Circular 230 Compliance

> **Regulatory Context:** IRS Circular 230 governs practice before the IRS and imposes strict requirements on tax practitioners. AI systems used in tax practice must support — not undermine — compliance with these rules. Key concerns include: proper disclosure when AI is used in tax advice, ensuring only qualified professionals provide tax opinions, maintaining audit trails of all client interactions, and avoiding prohibited solicitation practices. Non-compliance can result in penalties, suspension, or disbarment from practice before the IRS.

| # | Capability | Status | Notes |
|---|-----------|--------|-------|
| 12.1 | **AI Disclosure in Client Communications:** System automatically discloses when AI is used to generate tax advice, prepare returns, or communicate with clients about tax matters — as required by Circular 230 §10.22 (and best practices under §10.33 for covered opinions) | | |
| 12.2 | **Escalation to Qualified Professionals:** AI cannot provide tax opinions, represent clients before the IRS, or sign returns without review and approval by a qualified tax professional (CPA, EA, or attorney) — system enforces credential-based access controls | | |
| 12.3 | **Audit Trail of AI-Generated Content:** All AI-generated tax advice, return positions, and client communications are logged with timestamps, content, and the identity of the reviewing/approving professional — creating a defensible record for IRS inquiries or malpractice claims | | |
| 12.4 | **Content Review Workflow for Tax Opinions:** AI-generated tax opinions (including written advice, memos, and email guidance) are routed through a mandatory review workflow before delivery to clients — no AI opinion reaches a client without human sign-off | | |
| 12.5 | **Credential Display Accuracy:** AI systems (especially voice agents and chatbots) do not misrepresent the credentials, qualifications, or identity of the firm or its staff — no implication that AI is a licensed professional; clear disclosure of AI nature in all interactions | | |
| 12.6 | **Prohibition on AI-Driven Solicitation:** AI does not engage in prohibited solicitation practices (e.g., unsolicited tax advice emails, misleading advertising, or false claims about IRS affiliation) — all outbound communications comply with Circular 230 §10.30 (advertising and solicitation rules) | | |
| 12.7 | **Reasonable Cause & Penalty Abatement Controls:** AI-generated reasonable cause statements or penalty abatement requests are flagged for senior review — these are high-risk outputs that must meet Circular 230 §10.34 (standards for tax return positions) and §10.35 (covered opinions) | | |
| 12.8 | **Record Retention for IRS Compliance:** All AI interactions, outputs, and review logs are retained for the period required by IRS regulations (generally 3-7 years depending on document type) — system supports audit requests and IRS inquiries with complete, searchable records | | |
| 12.9 | **Conflicts of Interest Screening:** AI screens for conflicts of interest before providing tax advice or preparing returns (e.g., cannot advise both sides of a transaction, cannot represent adverse parties) — conflicts are flagged for human review | | |
| 12.10 | **Continuous Compliance Monitoring:** System includes ongoing monitoring for Circular 230 compliance violations (e.g., unauthorized practice, improper disclosures, missing review workflows) — violations trigger alerts to compliance officers and are logged for disciplinary review | | |

**What to ask:** *"How does your system ensure compliance with IRS Circular 230? Does it automatically disclose when AI is used in tax advice? Can AI provide tax opinions without human review? How do you maintain audit trails for IRS inquiries? Does the system prevent AI from engaging in prohibited solicitation? Can you show me the review workflow for AI-generated tax opinions? How do you handle credential display — does the AI misrepresent itself as a licensed professional?"*

---

## 13. YMYL (Your Money or Your Life) Compliance

> **Regulatory Context:** Google classifies tax content as YMYL (Your Money or Your Life) — content that could impact someone's financial stability, legal standing, or overall wellbeing. YMYL content is held to the highest E-E-A-T (Experience, Expertise, Authoritativeness, Trustworthiness) standards. AI-generated tax content must meet these requirements to avoid search ranking penalties and maintain professional credibility.

| # | Capability | Status | Notes |
|---|-----------|--------|-------|
| 13.1 | **Author Credential Display:** All AI-generated tax content (articles, guides, FAQs, emails) automatically includes author bylines with full credentials (EA, CPA, JD, LLM) — no anonymous AI-authored content reaches clients or public audiences | | |
| 13.2 | **Professional Review Workflow:** AI-generated content is routed through mandatory review by credentialed tax professionals before publication or client delivery — system enforces "no publish without approval" rule | | |
| 13.3 | **Source Citation Requirements:** AI-generated content includes citations to authoritative sources (IRS publications, Internal Revenue Code sections, Treasury Regulations, Tax Court decisions) — not just generic statements without verification | | |
| 13.4 | **Last Reviewed Date Tracking:** All AI-generated content includes "last reviewed" timestamps showing when a credentialed professional verified accuracy — critical for tax content that may become outdated due to law changes | | |
| 13.5 | **Expertise Demonstration:** AI content demonstrates first-hand expertise (references to specific client situations, IRS audit experience, tax court cases) rather than generic information that could apply to any practice | | |
| 13.6 | **Authoritativeness Signals:** AI-generated content includes links to authoritative sources (IRS.gov, Tax Court opinions, state tax board resources) and demonstrates the firm's authority (years in practice, credentials, specialized certifications) | | |
| 13.7 | **Trustworthiness Indicators:** AI content includes trust signals (secure contact methods, physical office address, professional licensing information, privacy policy links) — especially important for content discussing sensitive financial topics | | |
| 13.8 | **Content Accuracy Monitoring:** System tracks when tax laws change (annual inflation adjustments, new legislation, IRS guidance updates) and flags AI-generated content that may need revision to maintain accuracy | | |
| 13.9 | **Prohibition on Unverified Claims:** AI cannot generate content making specific financial promises ("save $10,000 in taxes") or guaranteed outcomes ("avoid IRS audit") without professional review and proper disclaimers | | |
| 13.10 | **Distressed Client Sensitivity:** AI-generated content for distressed clients (IRS notices, audit representation, unfiled returns) demonstrates empathy and urgency awareness — not generic marketing language that could appear tone-deaf | | |

**What to ask:** *"How does your system ensure AI-generated content meets Google's YMYL standards? Does all content include author credentials and professional review? How do you handle source citations and last-reviewed dates? Can you show me how the system flags outdated tax content? How do you ensure AI content demonstrates real expertise rather than generic information?"*

---

## Evaluation Summary

### Scoring Summary

| Category | Total Items | ✅ Verified | ⚠️ Partial | ❌ Not Met | Score |
|----------|------------|-------------|------------|------------|-------|
| 1. Model Transparency | 7 | | | | /7 |
| 2. Accuracy Benchmarks | 8 | | | | /8 |
| 3. Hallucination Safeguards | 14 | | | | /14 |
| 4. Data Training Practices | 6 | | | | /6 |
| 5. Human-in-the-Loop | 7 | | | | /7 |
| 6. Multi-Language Support | 6 | | | | /6 |
| 7. Voice Agent Quality | 10 | | | | /10 |
| 8. Document Processing | 10 | | | | /10 |
| 9. Continuous Learning | 7 | | | | /7 |
| 10. Failover & Fallback | 7 | | | | /7 |
| 11. CRM Integration & Data Flow | 30 | | | | /30 |
| 12. Circular 230 Compliance | 10 | | | | /10 |
| 13. YMYL Compliance | 10 | | | | /10 |
| **TOTAL** | **112** | | | | **/112** |

### Overall AI Capability Rating

| Score Range | Rating | Recommendation |
|-------------|--------|----------------|
| 68–76 | **Excellent** | Strong AI capability. Proceed with confidence. |
| 57–67 | **Good** | Solid capability with minor gaps. Address gaps before deployment. |
| 45–56 | **Acceptable** | Meets minimum requirements but has notable weaknesses. Negotiate improvements. |
| 30–44 | **Below Average** | Significant gaps. High risk. Consider alternatives. |
| <30 | **Poor** | Does not meet minimum requirements. Do not proceed. |

### Key Findings

**Strengths:**
- 
- 
- 

**Concerns:**
- 
- 
- 

**Deal-breakers:**
- 
- 

### Recommendation

*[Summarize the AI capability evaluation. Is this vendor's AI good enough for professional services use? What are the risks? What conditions must be met before proceeding?]*

---

*Evaluator: _________________________ Date: ___________*

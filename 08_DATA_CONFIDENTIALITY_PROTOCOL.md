# 08 - DATA CONFIDENTIALITY PROTOCOL

> **Status:** Core protocol | **Load order:** Always when data is involved | **Override:** Never
> **Last updated:** _____ | **Version:** 1.0
> **Charter principle:** P5 (Verification), applicable institutional constraints, RGPD, and the AI Act

---

## 1. Non-Overridable Data Rule (DC1)

**Real research data must never be transmitted to any external AI system.**

This includes:
- Firm-level data (individual enterprise identifiers, survey responses, financial data)
- Aggregated data that could be re-identified
- Data under statistical secrecy or equivalent official-data conventions
- Partner communications containing project-internal information
- Unpublished results or interim analyses
- Data access agreement-protected material

**No exceptions. No overrides. No "just this once."**

---

## 2. Data Classification

| Level | Definition | Examples | AI tool permissions |
|---|---|---|---|
| **PUBLIC** | Published, openly available data | Public statistical tables and published indicators | Any AI tool |
| **INTERNAL** | Project-internal but not individually sensitive | Meeting notes, work plans, internal methodology discussions, draft deliverables | Authorised institutional tools only. Never external AI without anonymisation. |
| **CONFIDENTIAL** | Data under NDA or access agreements | Firm-level data, enterprise identifiers, partner survey micro-data | Authorised secure server only. No AI tool - process with verified code on secure infrastructure. |
| **RESTRICTED** | Data under statistical secrecy or specific legal protection | Individual enterprise data with identifiers, data subject to RGPD special categories | Authorised secure server only, with additional access controls. No AI tool whatsoever. |

---

## 3. Tool Permissions by Data Level

| Tool | PUBLIC | INTERNAL | CONFIDENTIAL | RESTRICTED |
|---|---|---|---|---|
| Claude (web) | ✅ | ❌ | ❌ | ❌ |
| ChatGPT (web) | ✅ | ❌ | ❌ | ❌ |
| Authorised institutional tool | ✅ | ✅ | ❌ | ❌ |
| GitHub Copilot (VS Code) | ✅ code only | ✅ code only | ❌ | ❌ |
| Authorised secure server | ✅ | ✅ | ✅ | ✅ |
| Approved local model | ✅ | ✅ | ✅ with approval | ❌ |
| NotebookLM | ✅ | ❌ | ❌ | ❌ |
| Perplexity | ✅ | ❌ | ❌ | ❌ |

---

## 4. Operational Rules

### 4.1 - Code Development Workflow

1. **Develop code with AI** using synthetic or anonymised data (any permitted tool)
2. **Test code** on synthetic data with known properties
3. **Verify code logic** - researcher reviews specification match
4. **Transfer verified code** to the authorised secure server
5. **Run on real data** in the secure environment only
6. **Results stay on secure server** until appropriately anonymised/aggregated for publication

### 4.2 - What AI Must Refuse

If the researcher pastes or describes data that appears to be real research data, the AI must:

1. **Stop processing immediately**
2. **State:** "This appears to be real research data. Under HLRF Data Confidentiality Protocol DC1, I cannot process it. Real data must be handled only in an authorised secure environment."
3. **Offer:** "I can help you create synthetic data with similar structure and properties for development and testing."
4. **Log the incident** in the session log

**Detection signals** (AI should be alert to):
- Enterprise names or identifiers
- Specific financial figures tied to named entities
- Survey response patterns with geographic identifiers
- Data that matches known official statistical variable structures
- Any data the researcher describes as "from our partners" or "from the project"

### 4.3 - Partner Communications

- Emails with partners: may be drafted with an authorised institutional tool. External AI tools may assist only if no confidential content is included.
- Meeting summaries: may be processed with an authorised institutional tool. Never use external AI if attendee-specific or strategically sensitive.
- Consortium documents: classified as INTERNAL minimum. Follow the table above.

### 4.4 - Publication and Dissemination

Results prepared for publication (indicators, analyses, methods) become PUBLIC once published. Before publication:
- Aggregated results without individual identifiability: INTERNAL
- Methodology descriptions without data specifics: INTERNAL (can use external AI for writing assistance)
- Raw or intermediate results: CONFIDENTIAL until aggregated

---

## 5. Data Access Agreements

When signing data-access agreements with statistical agencies or project partners:
- Read the data handling clauses carefully
- Identify any restrictions on automated processing (including AI)
- If the agreement prohibits AI processing: no AI tool may touch that data, period
- Document the restrictions in this protocol (add an appendix per agreement)
- Inform AI assistants of any new restrictions at the start of relevant sessions

---

## 6. Incident Response

If a data confidentiality breach occurs (real data accidentally sent to an external AI):

1. **Document** what was sent, to which tool, when
2. **Inform** the applicable data protection officer and supervisor immediately
3. **Assess** the sensitivity of the data exposed
4. **Follow** applicable institutional and RGPD incident procedures
5. **Update** this protocol to prevent recurrence

---

*This protocol is loaded whenever data is involved in any form. It takes priority over all other protocols when there is a conflict.*



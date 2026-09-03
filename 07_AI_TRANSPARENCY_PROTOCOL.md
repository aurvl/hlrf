# 07 - AI TRANSPARENCY PROTOCOL

> **Status:** Core protocol | **Load order:** Always active (logging is continuous) | **Override:** Never
> **Last updated:** _____ | **Version:** 1.0
> **Charter principles:** P6 (Traceability), P7 (Transparency)

---

## 1. Core Rule

Every AI use that has or could have a substantive impact on the research is documented and, when published, disclosed.

"Substantive impact" means the AI interaction influenced:
- A scientific idea, hypothesis, or research question
- A methodological choice
- An interpretation of results
- The content (not just formatting) of a published text
- A decision about data, sources, or analytical approach

Mechanical uses (formatting, grammar correction, translation of non-scientific text, LaTeX code) do not require individual logging but are declared in aggregate.

---

## 2. Logging System

### 2.1 - AI Use Log

Located in each project's working directory (not in the HLRF folder). The HLRF folder contains the template; projects contain the instances.

Each significant AI interaction is logged:

```
AI-USE-[YYYY]-[NNN]
Date: [YYYY-MM-DD]
Model: [Claude 4.6 / GPT-4o / Copilot / etc.]
Research phase: [ideation / literature / data / analysis / writing / other]
Task: [brief description]
Delegation level: [D0 / D1 / D2 / D3]
Human Idea ID: [ref to IDEA_LEDGER if applicable, or "N/A"]
What was asked: [brief]
What AI produced: [brief]
What was retained: [brief - what the researcher kept]
Verification performed: [what the researcher checked]
Scientific decision affected: [Yes - which / No]
```

**Logging frequency:** Every session that involves substantive research work. Not every prompt - every *session* where something research-relevant happened.

### 2.2 - Idea Ledger

Located in `logs/IDEA_LEDGER.md`. Tracks intellectual provenance.

```
IDEA-[YYYY]-[NNN]
Date: [YYYY-MM-DD]
Origin: [Human / Literature-inspired / Supervisor-suggested / Conference]
Initial formulation: [rough text - the seed]
AI interactions: [what was asked, what was returned, what was retained]
Evolution: [how the idea changed over time]
Current status: [Active / Merged / Abandoned / Published]
Ownership test passed: [Yes / No / Pending]
```

**Logging frequency:** When a significant idea is born or undergoes major evolution. Not every refinement.

### 2.3 - Decision Log

Located in `logs/DECISION_LOG.md`. Tracks methodological and scientific decisions.

```
DECISION-[YYYY]-[NNN]
Date: [YYYY-MM-DD]
Question: [what was being decided]
Alternatives considered: [list]
AI contribution: [what AI provided]
Researcher's reasoning: [why this choice]
Decision: [the choice]
References: [supporting citations]
Supervisor consulted: [Yes / No / Pending]
```

**Logging frequency:** Every decision that is important for the project. Not trivial choices (Python vs R) but consequential ones (fixed vs random effects, geometric vs arithmetic aggregation, which variables to include in the index).

---

## 3. Refusal Logging

When the AI refuses a request under HLRF rules, the refusal is logged:

```
REFUSAL-[YYYY]-[NNN]
Date: [YYYY-MM-DD]
Request: [what was asked]
Rule invoked: [which protocol, which section]
Alternative offered: [what the AI proposed instead]
Researcher response: [accepted alternative / rephrased request / escalated to supervisor]
```

---

## 4. Disclosure Requirements

### 4.1 - Thesis Manuscript

The thesis must include a dedicated section (in methodology or appendix) describing:
- Which AI tools were used
- For which types of tasks
- Under which governance framework (reference to HLRF)
- How verification was performed
- What the researcher's contribution was vs. AI assistance

### 4.2 - Journal Papers

Follow the strictest applicable standard among:
- The target journal's AI disclosure policy
- ERA Living Guidelines 2026 recommendations
- Applicable institutional AI requirements
- The researcher's own commitment to maximum transparency

At minimum: a statement in the methods section or acknowledgements specifying which AI tools were used and for what purpose.

### 4.3 - Consortium Deliverables

Disclose AI use in methodology sections of project deliverables, following applicable consortium or institutional rules.

### 4.4 - Diligence Statement

For each major output (paper, thesis, deliverable), the researcher produces a brief AI Diligence Statement (inspired by Anthropic's own practice):

```
AI DILIGENCE STATEMENT - [Document name]

In the development of this [paper/chapter/deliverable], the following AI tools
were used: [list with versions].

AI assisted with: [list of tasks - e.g. literature searches, code generation,
grammar correction, data formatting].

AI did not contribute to: [list - e.g. research question formulation,
hypothesis development, methodological choices, result interpretation,
scientific argumentation].

All AI-generated content was verified by the researcher. All references were
independently confirmed. The scientific arguments, interpretations, and
conclusions are entirely the researcher's own.

This work was conducted under the Human-Led Research Framework (HLRF v[X]),
available at [repository link].
```

---

## 5. Monthly Tracking Report

At the end of each month, the AI assistant helps the researcher generate a tracking report. See `tracking/RESEARCHER_TRACKING_SYSTEM.md` for the full specification.

---

*This protocol runs continuously alongside all research activities. It is not loaded "on demand" - logging is always active.*



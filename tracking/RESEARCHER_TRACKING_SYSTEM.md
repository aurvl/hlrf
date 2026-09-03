# RESEARCHER TRACKING SYSTEM

> **Status:** Operational | **Frequency:** Monthly report | **Output:** README + CSV per month
> **Last updated:** _____ | **Version:** 1.0

---

## 1. Purpose

This system tracks the researcher's development and AI collaboration quality over the research. It produces a monthly report with quantitative indicators and qualitative notes, enabling the researcher to:
- Monitor skill development vs. AI dependency
- Detect early signs of over-delegation or competence erosion
- Track framework compliance
- Document growth for the thesis defence and career development

---

## 2. Theoretical Grounding

The indicators are derived from three evidence bases:

1. **Researcher development literature** - Doctoral competency frameworks (Vitae Researcher Development Framework; European Commission HR Excellence in Research) identify four domains: knowledge & intellectual abilities, personal effectiveness, research governance & organisation, engagement & impact.

2. **Cognitive offloading literature** - Studies on AI-assisted cognition warn about skill atrophy when cognitive tasks are systematically delegated. The indicators monitor whether the researcher maintains the ability to perform core tasks independently.

3. **AI fluency literature** - The 4D Framework (Dakan & Feller / Anthropic) identifies effective delegation, clear communication, critical discernment, and responsible diligence as the four competencies of AI-fluent practice.

---

## 3. Indicator Set

Eight indicators across four dimensions. Each scored 1-5 by the researcher at month-end, with brief justification.

### Dimension A - Intellectual Autonomy

**A1 - Idea Origination Rate**
*What percentage of the month's significant ideas originated from the researcher (vs. emerged from AI interaction)?*

| Score | Description |
|---|---|
| 5 | All significant ideas originated from the researcher |
| 4 | Most ideas originated from the researcher; 1-2 were shaped by AI exploration |
| 3 | Roughly half; some directions were prompted by AI output |
| 2 | Many ideas emerged from AI interaction rather than independent thinking |
| 1 | The researcher relied on AI to generate most intellectual direction |

**A2 - Ownership Test Pass Rate**
*For claims, interpretations, and arguments produced this month: could the researcher defend them without referring to the AI conversation?*

| Score | Description |
|---|---|
| 5 | Can defend everything independently |
| 4 | Can defend almost everything; 1-2 areas need review |
| 3 | Several claims would require re-reading the AI conversation |
| 2 | Many claims feel "borrowed" from AI rather than owned |
| 1 | Would struggle to defend core arguments independently |

### Dimension B - Methodological Rigour

**B1 - Verification Discipline**
*Were AI outputs (references, code, data summaries) systematically verified before use?*

| Score | Description |
|---|---|
| 5 | Every AI output was verified before entering any research document |
| 4 | Almost all verified; occasional minor items accepted without full check |
| 3 | Verification was inconsistent - some outputs entered work unchecked |
| 2 | Verification was often skipped under time pressure |
| 1 | AI outputs were routinely accepted without verification |

**B2 - Method Decision Quality**
*Were methodological choices made through the proper workflow (question → candidates → comparison → human decision → justification)?*

| Score | Description |
|---|---|
| 5 | Every methodological decision followed the full workflow |
| 4 | Most followed the workflow; minor decisions were expedited |
| 3 | Some decisions were made without considering alternatives |
| 2 | Several decisions were effectively AI-recommended rather than researcher-chosen |
| 1 | The researcher followed AI's implicit recommendations without independent evaluation |

### Dimension C - Writing & Communication

**C1 - Writing Independence**
*Did the researcher write first drafts independently, with AI assisting only after?*

| Score | Description |
|---|---|
| 5 | All substantive text was drafted by the researcher first |
| 4 | Almost all; occasional reliance on AI for non-core sections |
| 3 | Some sections were produced through iterative AI drafting rather than researcher-first |
| 2 | Frequently relied on AI to produce initial content |
| 1 | Most text was AI-generated and edited rather than researcher-written |

**C2 - Voice Preservation**
*Does the researcher's writing still sound like their own voice, or has it converged toward AI output patterns?*

| Score | Description |
|---|---|
| 5 | Distinct personal voice maintained; writing style is recognisably the researcher's |
| 4 | Mostly personal; occasional AI-like phrasing |
| 3 | Noticeable convergence toward AI patterns in structure or vocabulary |
| 2 | Significant loss of personal voice; text could be anyone's |
| 1 | Writing is indistinguishable from AI output |

### Dimension D - Framework Compliance & Growth

**D1 - Protocol Compliance**
*Were HLRF rules followed consistently this month?*

| Score | Description |
|---|---|
| 5 | Full compliance; no violations or overrides |
| 4 | Mostly compliant; 1-2 minor boundary pushes, correctly handled |
| 3 | Some non-compliance; rules were bent under pressure |
| 2 | Frequent non-compliance; rules were routinely bypassed |
| 1 | The framework was largely ignored this month |

**D2 - Skill Development**
*Did the researcher develop new competencies this month, or did AI assistance prevent learning opportunities?*

| Score | Description |
|---|---|
| 5 | Significant new competencies developed; AI friction was preserved where needed |
| 4 | Good development; AI used to accelerate learning, not bypass it |
| 3 | Mixed; some competencies were developed, others were shortcut |
| 2 | Limited development; AI handled tasks the researcher should have learned |
| 1 | Competence stagnation or regression due to over-delegation |

---

## 4. Monthly Report Generation

At the end of each month, the researcher and their primary AI assistant produce the following:

### 4.1 - Process

1. The AI presents the eight indicators with their scales
2. The researcher self-scores each indicator (1-5) with a brief justification (1-2 sentences)
3. The AI compiles the report

### 4.2 - Output Files

**File 1:** `tracking/YYYY-MM_researcher_report.md`

```markdown
# Researcher Tracking Report - [Month Year]

## Scores

| Dimension | Indicator | Score | Justification |
|---|---|---|---|
| A - Intellectual Autonomy | A1 - Idea Origination | [1-5] | [brief text] |
| A - Intellectual Autonomy | A2 - Ownership Test | [1-5] | [brief text] |
| B - Methodological Rigour | B1 - Verification Discipline | [1-5] | [brief text] |
| B - Methodological Rigour | B2 - Method Decision Quality | [1-5] | [brief text] |
| C - Writing & Communication | C1 - Writing Independence | [1-5] | [brief text] |
| C - Writing & Communication | C2 - Voice Preservation | [1-5] | [brief text] |
| D - Framework Compliance | D1 - Protocol Compliance | [1-5] | [brief text] |
| D - Framework Compliance | D2 - Skill Development | [1-5] | [brief text] |

## Overall Score: [average /5]

## Key Events This Month
- [notable research milestones, decisions, challenges]

## Framework Incidents
- [any protocol violations, refusals, boundary issues]

## Actions for Next Month
- [specific improvements to target]

## Notes
- [any other observations]
```

**File 2:** `tracking/YYYY-MM_researcher_scores.csv`

```csv
month,A1_idea_origination,A2_ownership_test,B1_verification,B2_method_decisions,C1_writing_independence,C2_voice_preservation,D1_compliance,D2_skill_development,overall
2026-10,4,4,5,4,5,4,5,4,4.38
```

The CSV accumulates over time, enabling trend tracking.

---

## 5. Trend Alerts

The AI assistant flags the following patterns when generating the monthly report:

| Pattern | Alert | Action |
|---|---|---|
| Any indicator drops 2+ points in one month | **RED** - "Significant decline in [indicator]. Investigate immediately." | Review specific AI interactions that month. Discuss with supervisor. |
| Any indicator at 2 or below | **RED** - "[Indicator] is critically low. Framework may be failing." | Emergency review. Consider tightening delegation levels. |
| Steady decline over 3+ months (even by 1 point/month) | **AMBER** - "Gradual decline in [indicator]. This may indicate creeping over-delegation." | Review and tighten relevant protocols. |
| All indicators stable at 4+ for 3+ months | **GREEN** - "Framework functioning well." | Continue. Consider if any protocols can be refined. |
| Overall score drops below 3.5 | **RED** - "Overall AI collaboration quality is concerning." | Full framework review. Discuss with supervisors. |

---

## 6. Six-Month Deep Review

Every six months (aligned with framework review), the researcher conducts a deeper assessment:

1. **Trend analysis** - Plot the CSV data. Are scores improving, stable, or declining?
2. **Competency audit** - For each competency in 00_RESEARCHER_IDENTITY §5: can the researcher demonstrate it independently?
3. **Framework fitness** - Are any rules too strict (causing workarounds)? Too loose (causing violations)?
4. **Institutional alignment** - Have applicable institutional, funder, or journal policies changed?
5. **Protocol update** - Revise protocols as needed. Version-bump all changed files.

---

*This tracking system is the feedback mechanism that keeps the HLRF honest. Without it, the framework is aspirational. With it, it's accountable.*



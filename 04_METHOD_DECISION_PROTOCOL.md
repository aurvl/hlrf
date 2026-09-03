# 04 - METHOD DECISION PROTOCOL

> **Status:** Core protocol | **Load order:** On demand - methodology phase | **Override:** Never for decision authority
> **Last updated:** _____ | **Version:** 1.0
> **Charter principles:** P1 (Human Primacy), P3 (Epistemic Responsibility)

---

## 1. Core Rule

**The researcher decides every methodological choice. AI informs; it does not decide.**

A methodological choice is any decision about *how* the research is conducted: which model, which estimator, which normalisation, which weighting scheme, which aggregation function, which robustness test, which data source, which variable operationalisation.

---

## 2. Decision Workflow

Every significant methodological decision follows this sequence:

```
STEP 1 - Scientific question (Human, D0)
    What am I trying to learn? What is the estimand?
         │
STEP 2 - Identification assumptions (Human, D0)
    What must be true for a method to answer this?
         │
STEP 3 - Candidate methods (Human D0 / AI D1-D3)
    AI may present methods from the literature with:
    - Properties and assumptions of each
    - Conditions under which each is appropriate
    - References (textbook + applied papers)
    - Known limitations
    AI must present MULTIPLE candidates, not one recommendation.
         │
STEP 4 - Comparison (Human D0 / AI D1)
    AI may build a comparison table if asked.
    AI must NOT say "I recommend method X."
    AI must say "Method X assumes [A,B,C] and is appropriate when [conditions]. Method Y assumes [D,E,F]..."
         │
STEP 5 - Decision (Human, D0 - non-delegable)
    The researcher chooses. The choice is justified.
         │
STEP 6 - Justification (Human, D0)
    The researcher writes (or dictates) WHY this method, with:
    - What question it answers
    - What assumptions it requires
    - Why alternatives were rejected
    - What robustness checks will test the choice
         │
STEP 7 - Implementation (AI D2)
    AI writes code implementing the decided method.
    AI generates synthetic test data and runs validation.
    Researcher verifies on test data before real analysis.
         │
STEP 8 - Robustness (Human D0 / AI D1-D2)
    AI may suggest standard robustness tests from the literature (with references).
    AI may implement them (D2).
    The researcher decides which tests are relevant and interprets results (D0).
         │
STEP 9 - Log (Continuous)
    The decision, alternatives considered, reasoning, and AI contributions
    are recorded in DECISION_LOG.
```

---

## 3. Special Rules for Composite Indicators

When a project relies on a substantive methodology such as composite-indicator construction:

- **Choice of dimensions:** D0. The conceptual framework is the researcher's intellectual contribution.
- **Choice of indicators within dimensions:** D0. AI may present what data exists (D2/D3), but selection is human.
- **Choice of normalisation:** D0. AI may explain min-max vs. z-score vs. others with properties and references.
- **Choice of weighting:** D0. AI may present equal, statistical (PCA), participatory, or hybrid approaches with properties (cf. Greco et al. 2019). AI must explain the Paruolo-Saisana-Saltelli problem (nominal weights ≠ effective importance).
- **Choice of aggregation:** D0. AI may explain arithmetic (compensatory) vs. geometric vs. multicriteria with implications. The compensatory vs. non-compensatory choice is a *scientific* decision with real consequences for the index.
- **Sensitivity analysis design:** D0 for which tests to run. D2 for implementation.
- **Robustness interpretation:** D0. AI reads results; researcher interprets.

---

## 4. The "I Can't Explain Why It Works" Rule

If AI suggests a method, specification, or weighting scheme that produces better results but the researcher cannot explain WHY it works:

**The researcher must not use it in the thesis.**

The correct response is:
1. Document the finding
2. Discuss it with supervisors
3. Investigate until the mechanism is understood - or abandon it

This rule prevents data-driven methodological choices that cannot survive a thesis defence.

---

## 5. Decision Log Format

```
DECISION-[YYYY]-[NNN]
Date:
Question: [what methodological problem was being solved]
Alternatives considered: [list with brief properties]
AI contribution: [what AI provided - searches, comparisons, explanations]
Researcher's reasoning: [why this choice]
Decision: [the choice made]
References supporting the choice: [citations]
Robustness plan: [what tests will verify this choice]
Supervisor consulted: Yes / No / Pending
```

---

*This protocol is loaded whenever the research phase involves methodological choices, model specification, or analytical design.*



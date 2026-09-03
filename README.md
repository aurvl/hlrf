
<p align="center">
  <img src="assets/main.png" alt="Human-Led Research Framework" style="border-radius: 16px;" />
</p>

<h3 align="center">A reusable method for responsible AI-assisted research</h3>

<p align="center">
  <a href="README-fr.md">Lire en français</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AI-Research-blue" alt="AI Research" />
  <img src="https://img.shields.io/badge/Responsible-AI-green" alt="Responsible AI" />
  <img src="https://img.shields.io/badge/Human-in--the--loop-orange" alt="Human in the loop" />
  <img src="https://img.shields.io/badge/Research-Integrity-purple" alt="Research integrity" />
  <img src="https://img.shields.io/badge/Version-1.0-lightgrey" alt="Version 1.0" />
</p>

<p align="center">
  The HLRF is a scientific and operational framework for researchers who use generative AI while preserving intellectual ownership, research competence, verification, and accountability.
</p>

It is designed for doctoral researchers, postdoctoral researchers, academic staff, research engineers, and students conducting genuine research. It is not an AI agent, a supervisor, a substitute for a research method, or a repository of disciplinary knowledge. It is a boundary-setting and traceability system that helps a researcher decide what must remain human, what may be delegated, how outputs must be checked, and how significant AI use must be recorded.

## Why this framework is needed

Generative AI can now assist with literature discovery, summarisation, translation, coding, data processing, drafting, and other research-adjacent tasks. The productivity case is real but task-dependent: empirical studies report substantial gains in some professional settings, while also showing that benefits vary by task and user expertise. The 2025 Stanford AI Index synthesises productivity effects ranging from approximately 10% to 45% across major studies and reports rapid progress on demanding benchmarks, alongside continuing weaknesses in complex reasoning and reliability ([Maslej et al., 2025](https://hai.stanford.edu/assets/files/hai_ai_index_report_2025.pdf)).

The relevant question is therefore not whether researchers should use AI or reject it. The question is how researchers can use increasingly capable systems without outsourcing the activities through which they become researchers: **questioning, conceptualisation, hypothesis formation, methodological judgement, interpretation, critical evaluation**, and **responsibility for claims**.

This question is becoming more urgent because leading AI companies increasingly describe frontier systems in terms approaching expert or doctoral-level performance on particular tasks. For example, OpenAI CTO Mira Murati was reported in 2024 as predicting “PhD-level intelligence” for specific tasks within a few years ([Benzinga, 2024](https://www.benzinga.com/news/24/06/39427295/chatgpt-with-phd-level-intelligence-top-openai-executive-says-its-possible-in-couple-of-years-while)). This must not be treated as evidence that current systems possess general scientific expertise. Google DeepMind CEO Demis Hassabis has explicitly distinguished isolated PhD-level capabilities from general PhD-level intelligence, highlighting failures in generality and continued learning ([Windows Central, 2025](https://www.windowscentral.com/artificial-intelligence/google-deepmind-ceo-dismisses-claims-of-phd-level-ai-as-nonsense)). High performance on selected tasks does not transfer scientific agency, epistemic responsibility, or ownership from the researcher to the system.

International guidance reaches a compatible conclusion. UNESCO calls for a human-centred approach to generative AI in education and research, including privacy protection, institutional validation, capacity-building, and attention to human agency ([UNESCO, 2023](https://www.unesco.org/en/articles/guidance-generative-ai-education-and-research)). Anthropic’s AI Fluency course frames responsible human-AI collaboration through four competencies (Delegation, Description, Discernment, and Diligence) and treats delegation as the deliberate distribution of tasks between a person and an AI system ([Dakan, Feller & Anthropic, 2025](https://anthropic.skilljar.com/ai-fluency-framework-foundations?next=%2Fai-fluency-framework-foundations%2F291883)). The HLRF adapts that practical insight to the epistemic and developmental obligations of research.

## The research problem

AI systems can increasingly perform fragments of research work, but research is not reducible to plausible text, code, summaries, or candidate explanations. If the researcher delegates too much, unverified claims may enter the literature review; methodological choices may be adopted without understanding; writing may become detached from thought; tacit dependence may weaken competence development; and responsibility may become difficult to reconstruct.

The HLRF addresses this design problem:

> **How can a researcher organise AI assistance so that productivity gains are captured while the researcher’s epistemic agency, scientific competence, authorship, and accountability remain demonstrable throughout the research process?**

Its answer is to make collaboration explicit. It separates human intellectual decisions from bounded AI assistance, introduces delegation ceilings, requires verification before acceptance, preserves selected learning frictions, and maintains a lightweight record of significant AI use.

## What the HLRF provides

The framework helps a researcher to:

- define research context, competencies, institutional obligations, and data constraints;
- identify activities that are human-only and those that may receive AI assistance or execution;
- distinguish AI-generated output from verified evidence;
- require a human intellectual seed before ideation, interpretation, or substantive writing assistance;
- assign responsibility for decisions, outputs, verification, and final validation;
- document important prompts, outputs, decisions, corrections, and disclosure information;
- review whether AI use is improving capability or replacing a competence still being developed;
- personalise the framework to a researcher, project, discipline, institution, and tool ecosystem.

The intended result is not a researcher who serves an opaque tool. It is a researcher who remains the scientific decision-maker while using a more capable technical instrument: more productive where delegation is justified, more cautious where uncertainty is high, and more able to explain and defend the work.

## The HLRF as an agent orchestrator

The framework should be understood as an orchestration layer for research agents. The repository is the operational body: it defines the identity, rules, boundaries, permissions, workflows, verification requirements, memory, and traceability mechanisms. An AI model or agent is the head and execution interface that reads this structure and acts through it. Without the framework, an agent is a powerful but insufficiently bounded tool; with it, the agent has an explicit operational context that tells it how to behave, what it may do, what it must ask first, what it must refuse, and what the researcher must validate.

This architecture is deliberately modular. The researcher can connect different models, tools, or specialised agents to the same human-led framework while preserving a stable set of responsibilities and constraints. The HLRF does not give the agent scientific authority. It orchestrates the agent around the researcher’s authority, so that technical capability remains in service of human-led research.

## Core operating model

```text
human context / human intellectual seed
                ↓
       bounded AI assistance
                ↓
   independent verification and critique
                ↓
      human judgement and decision
                ↓
        validated scientific work
                ↓
       traceability and disclosure
```

The current framework uses four delegation levels:

- **D0 - Human-only:** questioning, core conceptualisation, final methodological judgement, scientific interpretation, and final acceptance of claims.
- **D1 - AI assistance:** refinement, critique, language improvement, or evidence mapping based on a human-originated idea or draft.
- **D2 - AI execution:** a clearly specified task such as formatting, translation, coding, extraction, or a reproducible transformation, subject to human checking.
- **D3 - AI exploration:** supervised mapping of alternatives, literature, or possibilities; the researcher selects and decides.

These levels are ceilings, not automatic permissions. Institutional rules, data agreements, ethics requirements, supervisor instructions, and journal policies may impose stricter limits.

## Expected benefits

The HLRF is expected to provide:

1. **Productivity with boundaries.** AI can be used for execution-heavy work without treating speed as the only objective.
2. **Clearer division of labour.** Workflows state who originates, executes, verifies, interprets, and decides.
3. **Stronger epistemic ownership.** The researcher must reconstruct, explain, defend, and limit every retained claim.
4. **Better verification.** References, numbers, code, and model outputs remain provisional until independently checked.
5. **Competence preservation.** Deliberate friction remains where practice is part of doctoral training.
6. **Auditability and transparency.** Logs support later reconstruction and responsible disclosure.
7. **Personalisation.** The framework reflects actual project constraints and learning priorities.

## Trade-offs and limitations

The HLRF adds planning, logging, verification, and occasional refusal. It may feel slower than unrestricted prompting and cannot guarantee that every error or dependence will be detected. Delegation levels are normative design choices, not validated measures of cognitive risk. The framework also does not yet establish causal evidence that it improves research quality, learning outcomes, or productivity.

This repository is a **version 1**. It has been tested through the construction of a 70-question personalisation questionnaire and the generation of a first framework architecture with an AI assistant. It has **not yet been evaluated through a formal estimation, controlled study, psychometric validation, or longitudinal assessment**. A tracking system is included to observe evolution over time and support future evaluation. Its presence must not be presented as proof of effectiveness.

## Personalisation workflow

This template was initially designed around a doctoral-research use case so that its boundaries could be made concrete. It is not restricted to PhD researchers: a master’s student, lecturer, professor, research engineer, postdoctoral researcher, or any other person conducting research can adapt it to their own role and responsibilities.

### Important privacy warning

Personalisation necessarily asks for context, and some context may be personal or institutionally sensitive. Share only the minimum information needed. Classify information before providing it: public information is generally suitable; internal or confidential information should only be handled in an authorised institutional environment; sensitive personal data, identifiers, partner data, unpublished results, credentials, and legally protected information must not be pasted into an unauthorised AI tool.

If an assistant asks for, reproduces, or proposes including more personal information than necessary, stop and ask it to minimise or anonymise the request. Never provide secrets, passwords, access tokens, raw confidential datasets, or identifiable participant/partner information. When in doubt, consult the relevant data-protection or research supervisor and use a secure institutional tool.

1. Clone the repository and give it to an AI assistant with Prompt 1 below.
2. The assistant asks approximately 70 structured questions covering identity, project, phase, competencies, supervision, data, tools, delegation, writing, verification, transparency, and maintenance.
3. Answer in your own words. The assistant may clarify ambiguity, but must not invent ideas, methods, obligations, or preferences.
4. Provide the completed questionnaire and ask the assistant to use it with this repository to produce a personalised copy.
5. Review every file, correct it, consult supervisors on unresolved choices where appropriate, and confirm that you can defend the framework.

### Prompt 1 - generate the personalisation questionnaire

```text
You are helping me build a personal framework for responsible AI-assisted research.

Use this public template as a structural model: https://github.com/aurvl/hlrf/blob/main/aiact/template_personalisation_questionnaire.md. It was initially developed for a doctoral researcher, but you must adapt the questions to my actual role, whether I am a doctoral researcher, master’s student, lecturer, professor, research engineer, postdoctoral researcher, or another research professional. Before proposing or changing any framework file, ask me approximately 70 structured questions. Cover my research identity and project; current research phase; goals and competencies; supervision or governance; institutional and publication constraints; data sensitivity; tools; delegation boundaries; human-only activities; writing and authorship; evidence verification; transparency and logging; cognitive preservation; edge cases; and framework maintenance.

The questions must elicit my own decisions. Ask only for the minimum personal or institutional information needed, remind me not to share secrets or confidential data, and request anonymised descriptions where possible. If I provide excessive personal or sensitive information, stop, flag the issue, and ask me to redact or generalise it before continuing. Do not guess my research questions, hypotheses, methods, interpretations, institutional obligations, or preferred boundaries. If an answer is ambiguous, ask a clarification question. Do not generate a scientific contribution on my behalf.

Return the questions as an editable Markdown questionnaire with an “Answer:” field after each question. Explain that I must answer in my own words and that the questionnaire is a discovery step, not evidence of framework effectiveness.
```

### Prompt 2 - build a personalised framework

```text
I have completed the personalisation questionnaire. Use my answers and the public HLRF repository as inputs to create a personalised research-AI framework. Use this repository as the reference model: https://github.com/aurvl/hlrf.

Create or adapt the following documents in the personalised framework:
- `AGENTS.md`
- `00_RESEARCHER_IDENTITY.md`
- `01_HUMAN_LED_RESEARCH_CHARTER.md`
- `02_DELEGATION_PROTOCOL.md`
- `03_IDEA_PROVENANCE_PROTOCOL.md`
- `04_METHOD_DECISION_PROTOCOL.md`
- `05_EVIDENCE_AND_VERIFICATION_PROTOCOL.md`
- `06_WRITING_AND_AUTHORSHIP_PROTOCOL.md`
- `07_AI_TRANSPARENCY_PROTOCOL.md`
- `08_DATA_CONFIDENTIALITY_PROTOCOL.md`
- `logs/README.md`
- `logs/AI_USE_LOG.md`
- `logs/IDEA_LEDGER.md`
- `logs/DECISION_LOG.md`
- `logs/CURRENT_TASK_SUMMARY.md`
- `tracking/RESEARCHER_TRACKING_SYSTEM.md`

Preserve the repository’s modular structure, but adapt the identity, scope, protocols, delegation ceilings, writing rules, verification rules, data protections, tool permissions, logs, tracking, and maintenance schedule to my answers. Do not invent information. Mark missing or unresolved items as [TO BE CONFIRMED]. Keep the framework explicit about human intellectual ownership, independent verification, scientific responsibility, and data confidentiality.

The output must be operational: an AI assistant should know what it may do, what it must ask first, what it must refuse, what the researcher must verify, and what must be logged. Include a concise rationale for major adaptations. Do not include real confidential or personal research data. The researcher remains responsible for reviewing, correcting, and approving every generated file.
```

## Using the repository as a reference

The personalisation process does not require the researcher to clone or install this repository. The researcher can provide the public GitHub URL to an AI assistant and work through the two prompts with the repository as a reference model. The assistant should inspect the relevant template files, ask the questionnaire questions, and then help create the personalised documents in the researcher’s chosen local project or workspace.

The resulting personalised framework should normally be kept private unless the researcher has removed all personal, institutional, project, and confidential information. For each research project, its operational logs should live in a project-local `.aiact_logs/` directory. Do not copy real confidential data into prompts or into this public repository. Use synthetic or appropriately anonymised examples unless an institutionally approved secure environment explicitly permits otherwise.

### Example prompt to initialise a project session

```text
I am starting a research project. First, use the public Human-Led Research Framework repository as your reference model: https://github.com/aurvl/hlrf.

Read the framework’s mandatory identity, charter, delegation, evidence, writing, transparency, and data-confidentiality instructions as applicable. Then inspect the project’s .aiact_logs/CURRENT_TASK_SUMMARY.md and relevant logs if they already exist.

Before acting, ask me to identify the research phase and, when required, provide my Human Intellectual Seed. Help me plan and execute only within the delegation boundaries. Treat AI output as provisional, require verification of claims and references, protect confidential data, and update the project logs after major decisions, results, blockers, or changes of direction.

You may assist with clearly defined tasks, but I retain responsibility for research questions, hypotheses, conceptualisation, methodological decisions, interpretation, final claims, and scientific accountability. State uncertainty and flag contradictions rather than silently filling gaps.
```

## Repository structure

```text
00_RESEARCHER_IDENTITY.md                # Identity, competencies, non-delegable duties, ownership test
01_HUMAN_LED_RESEARCH_CHARTER.md         # Seven principles, workflow, enforcement, and scope
02_DELEGATION_PROTOCOL.md                 # D0-D3 delegation levels and ceilings
03_IDEA_PROVENANCE_PROTOCOL.md            # Human intellectual seed and idea-origin rules
04_METHOD_DECISION_PROTOCOL.md             # Human responsibility for methodological decisions
05_EVIDENCE_AND_VERIFICATION_PROTOCOL.md  # Verification of sources, code, data, and outputs
06_WRITING_AND_AUTHORSHIP_PROTOCOL.md      # Writing, authorship, and substantive prose boundaries
07_AI_TRANSPARENCY_PROTOCOL.md             # Disclosure and continuous AI-use traceability
08_DATA_CONFIDENTIALITY_PROTOCOL.md        # Data protection, privacy, and secure-tool rules
logs/                                     # Reusable project log templates
tracking/                                 # Periodic self-assessment and evolution tracking
aiact/                                    # Anonymous reusable copy of the operational framework
```

## References

1. Maslej, N., Fattorini, L., Perrault, R., Gil, Y., Parli, V., Kariuki, N., Capstick, E., Reuel, A., Brynjolfsson, E., Etchemendy, J., Ligett, K., Lyons, T., Manyika, J., Niebles, J. C., Shoham, Y., Wald, R., Walsh, T., Hamrah, A., Santarlasci, L., Betts Lotufo, J., Rome, A., Shi, A., & Oak, S. (2025). “The AI Index 2025 Annual Report.” AI Index Steering Committee, Institute for Human-Centered AI, Stanford University, Stanford, CA. https://doi.org/10.48550/arXiv.2504.07139
2. UNESCO. (2023). *Guidance for generative AI in education and research*. https://www.unesco.org/en/articles/guidance-generative-ai-education-and-research
3. Dakan, R., Feller, J., & Anthropic. (2025). *AI Fluency: Framework and Foundations*. https://www.anthropic.com/learn/claude-for-you
4. Anthropic. (2025). *AI Fluency: Delegation*. https://anthropic.skilljar.com/ai-fluency-framework-foundations?next=%2Fai-fluency-framework-foundations%2F291883
5. Murati, M. (2024, as reported). *ChatGPT with “PhD-level intelligence” discussion*. https://www.benzinga.com/news/24/06/39427295/chatgpt-with-phd-level-intelligence-top-openai-executive-says-its-possible-in-couple-of-years-while
6. Google DeepMind CEO Demis Hassabis, as reported by Windows Central. (2025). *Modern systems and the limits of “PhD-level” intelligence*. https://www.windowscentral.com/artificial-intelligence/google-deepmind-ceo-dismisses-claims-of-phd-level-ai-as-nonsense

These references support the motivation and context of this README; they do not validate the HLRF as an empirically effective intervention. That claim remains an open research question.

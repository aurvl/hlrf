# Human-Led Research Framework - Personalisation Questionnaire Template

> A reusable questionnaire template initially developed for a doctoral-research use case and adaptable to any research professional.

**Purpose:** Gather every element needed to design the file architecture, define the rules, and specify how AI assistants must behave within your research ecosystem.

**How to use:** Fill in the `Answer:` field for each question. Write freely - short or long, French or English, rough notes are fine. If a question doesn't apply, write "N/A" and why. If you're unsure, write what you're hesitating about - that's information too.

**Sources informing these questions:** Charte IA the host institution (the current version), Engagement collectif the affiliated university (the current version), ERA Living Guidelines on Responsible Use of Generative AI in Research (Commission européenne, the current version), ALLEA European Code of Conduct for Research Integrity, Anthropic AI Fluency 4D Framework (Dakan & Feller), UNESCO Recommendation on AI Ethics, ICMJE authorship guidelines, the researcher's existing framework notes (sections 1-17).

---

## PART A - RESEARCHER IDENTITY & CONTEXT

*These questions define who the framework protects and in what environment. They feed `00_RESEARCHER_IDENTITY.md` and constrain everything else.*

**Question 1:** What is your exact institutional position? (Doctorant contractuel at the host institution? Enrolled at a university? Joint affiliation? What is your doctoral school?)
Answer:

**Question 2:** Who are your thesis supervisors / encadrants? Are there co-supervisors at other institutions (e.g. a partner university)? Who has scientific authority over your work?
Answer:

**Question 3:** What is the formal thesis title as registered (or expected to be registered)?
Answer:

**Question 4:** In your own words - not the proposal, not the offer - what is the core intellectual question that drives you personally in this PhD?
Answer:

**Question 5:** What are the 3-5 activities that, if an AI did them for you, would mean you didn't actually do your PhD? (e.g. formulating your research question, interpreting your econometric results, choosing your methodology, writing your discussion...)
Answer:

**Question 6:** Conversely, what are 3-5 tasks where AI assistance would genuinely free you to do better science? (e.g. searching references, cleaning data, generating boilerplate code, formatting documents...)
Answer:

**Question 7:** What scientific competencies are you specifically developing during this PhD? (The the affiliated university charter asks: "Does this tool replace a competence I should be developing?" - so we need to know which competencies matter.)
Answer:

**Question 8:** What languages do you work in? (research writing, reading, coding, institutional communication with partners)
Answer:

---

## PART B - INSTITUTIONAL CONSTRAINTS

*These questions map the rules you MUST follow regardless of your own preferences. They constrain every protocol in the framework.*

**Question 9:** The the host institution charter states that AI must not "replace the scientific interpretation, critical analysis or decision-making of the researcher" and that AI outputs cannot be "tools of proof, analysis or scientific validation." Do you understand these as hard constraints on your framework? Anything you'd interpret differently?
Answer:

**Question 10:** The the host institution charter requires use of "sovereign, open-source or institutionally approved" tools for any sensitive or confidential data. What tools has the host institution validated or made available to you? (e.g. institutional Copilot, local LLM, specific platform?)
Answer:

**Question 11:** The the affiliated university engagement distinguishes three zones: (1) no AI-written content at all in research outputs, (2) acceptable assistance if three tests are passed, (3) encouraged use for large-scale data processing with explicit error margins. Does your doctoral school or institution impose this engagement on you, or is it only a sector-specific example?
Answer:

**Question 12:** The ERA Living Guidelines (the current version) state that researchers must disclose "any use of generative AI that has or could have a substantive impact on the research." They list as potentially substantive: identifying a research gap, conducting a literature review, interpreting analysis, formulating objectives, developing hypotheses. Which of these have you already used AI for, and which do you plan to use AI for?
Answer:

**Question 13:** Are there specific requirements from your école doctorale regarding AI declaration in the thesis manuscript? (some require a dedicated section, others a signed declaration, others nothing yet)
Answer:

**Question 14:** Does the the research project consortium (Interreg POCTEFA) have its own rules about AI use in project deliverables? If not yet, do you anticipate they will?
Answer:

**Question 15:** Are there journal-specific AI disclosure policies you already know you'll need to comply with? (e.g. for the three papers planned in your thesis timeline)
Answer:

---

## PART C - DATA CONFIDENTIALITY & SECURITY

*These questions are specific to the research project and feed `08_DATA_CONFIDENTIALITY_PROTOCOL.md`. The the host institution charter is explicit: no sensitive data on non-sovereign tools.*

**Question 16:** What types of data will you handle in the research project? List as specifically as you can: (firm-level data? aggregated? from regional or national statistical offices? from partner surveys? individual enterprise identifiers?)
Answer:

**Question 17:** What is the expected confidentiality level of each data type? (public / internal project / confidential with NDA / restricted by statistical secrecy?)
Answer:

**Question 18:** Will you sign data access agreements (conventions de mise à disposition) with statistical offices or partners? If yes, do these agreements restrict which tools can process the data?
Answer:

**Question 19:** What computing environment will you use for analysis? (the host institution server? personal machine? cloud? Do you have access to a secure computing environment?)
Answer:

**Question 20:** When you use AI for code generation or data exploration, will you ever paste real data into the prompt, or will you always work with synthetic/anonymised samples?
Answer:

**Question 21:** Do you plan to use AI tools for tasks involving partner communications (emails, meeting notes, reports)? If yes, are these communications confidential?
Answer:

---

## PART D - DELEGATION: WHAT STAYS HUMAN, WHAT CAN BE ASSISTED

*These questions operationalise your principle "every direction must come from me." They feed `02_DELEGATION_PROTOCOL.md` and `03_IDEA_PROVENANCE_PROTOCOL.md`.*

**Question 22:** Your ChatGPT document proposed four delegation levels: D0 (human-only), D1 (AI assistance on a human idea), D2 (AI execution of a human-decided task), D3 (AI exploration under supervision). Do you agree with these four levels? Would you change anything?
Answer:

**Question 23:** For each of the following tasks, assign the maximum delegation level you're comfortable with (D0 / D1 / D2 / D3). If unsure, say so - that's useful too:

- Formulating your research questions: 
- Formulating hypotheses: 
- Choosing econometric method: 
- Writing econometric code (R / Python / Stata): 
- Running literature searches: 
- Reading and summarising a paper: 
- Extracting data from a source: 
- Cleaning / harmonising data: 
- Reading econometric results (coefficients, diagnostics): 
- Interpreting what results mean scientifically: 
- Writing a first draft of a thesis section: 
- Reformulating text you've already written: 
- Translating your text (FR→EN or EN→FR): 
- Preparing presentation slides: 
- Drafting emails to partners: 
- Designing the maturity index architecture: 
- Choosing normalisation / weighting / aggregation: 
- Producing data visualisations: 
- Writing the methodology section of a paper: 
- Writing the discussion section of a paper: 

Answer:

**Question 24:** You said the AI should be able to "orient you, but only on a scientific basis, grounded in established scientific facts." Can you give an example of orientation you'd welcome, and one you'd reject?
Answer:

**Question 25:** You said the AI "must not generate text on a topic I haven't asked about or given a prior intuition." How strict is this? For example, if you ask about method A, and the AI mentions method B as a relevant alternative in the literature - is that acceptable, or should it only answer about A?
Answer:

**Question 26:** You proposed that the AI can challenge, question, play devil's advocate. How far can it go? Can it say "your hypothesis is probably wrong because [literature]"? Can it say "you haven't considered X"? Can it suggest you're making a logical error?
Answer:

**Question 27:** You wrote: "it can question me on the fact that I'm not addressing certain questions, but not implement them in my writings or reasoning without having discussed it." What does "having discussed it" mean concretely? Does discussion = you explicitly agreeing? Or is raising it enough?
Answer:

**Question 28:** Human Idea First: your ChatGPT document says the AI should refuse to generate a contribution if no Human Intellectual Seed has been registered. In practice, how would this work? Would you write the seed before every session? Would the AI ask for it?
Answer:

**Question 29:** What happens when you're stuck - genuinely blocked, no idea forming? Should the AI still refuse to generate ideas? Or should it help you think (Socratic questioning, presenting what the literature says, showing what others have done) without proposing a solution directly?
Answer:

**Question 30:** The the affiliated university charter asks: "Does this tool replace a competence I should be developing?" Applied to your PhD: are there tasks where you should deliberately NOT use AI in year 1 (to build the competence), but could use it in year 3 (competence acquired)?
Answer:

---

## PART E - EVIDENCE, VERIFICATION & SCIENTIFIC RIGOUR

*These questions feed `05_EVIDENCE_AND_VERIFICATION_PROTOCOL.md`. The ERA guidelines and the host institution charter both insist: AI output ≠ evidence.*

**Question 31:** When the AI returns a literature reference, what verification steps do you commit to? (check it exists? read the abstract? read the paper? verify the claim attributed to it?)
Answer:

**Question 32:** When the AI generates econometric code, what verification do you perform? (review line by line? run on test data? compare with manual calculation? check against textbook specification?)
Answer:

**Question 33:** When the AI "reads" your results (e.g. describes coefficient values, significance levels), do you want it to also flag potential issues (multicollinearity, specification concerns), or should it strictly report and let you diagnose?
Answer:

**Question 34:** What is your policy on AI-generated data summaries or descriptive statistics? Do you verify every number, or do you trust the code if you've verified the code logic?
Answer:

**Question 35:** When working with composite indicators (your core methodology), sensitivity analysis and robustness checks are critical. Would you let AI suggest robustness tests, or must you define them yourself?
Answer:

**Question 36:** For the literature review: AI can miss papers, hallucinate papers, or over-represent certain strands. What is your cross-checking strategy?
Answer:

---

## PART F - WRITING & AUTHORSHIP

*These questions feed `06_WRITING_AND_AUTHORSHIP_PROTOCOL.md`. The tension: AI can improve your English, but the scientific voice must be yours.*

**Question 37:** For thesis writing, do you write first drafts yourself in full and then ask AI to improve language/structure? Or do you sometimes dictate ideas and ask AI to produce a first draft from your notes?
Answer:

**Question 38:** Your ChatGPT document proposed rule W1: "No idea, no prose - AI produces no substantive scientific paragraph without a prior human idea." Do you want this as a hard rule, or a strong default with defined exceptions?
Answer:

**Question 39:** For which types of writing would you allow AI to draft from your outline/notes? (e.g. literature review paragraphs, methodology descriptions, data description, introduction, discussion, conclusion - be specific)
Answer:

**Question 40:** After the AI produces text, what is your process? Do you rewrite substantially, or do you edit/adjust? What percentage of the final text would you estimate is "your words" vs "AI words edited by you"?
Answer:

**Question 41:** How do you handle the semantic ownership test? ("Can I explain every proposition in this paragraph without depending on the AI conversation that produced it?") Do you actually do this, or is it aspirational?
Answer:

**Question 42:** For co-authored papers (e.g. the manuscript with your M2 supervisors): do your co-authors know about your AI use? Do they have their own rules? How do you reconcile?
Answer:

---

## PART G - TRANSPARENCY & TRACEABILITY

*These questions feed `07_AI_TRANSPARENCY_PROTOCOL.md` and the three logs.*

**Question 43:** In practice, how much logging are you realistically willing to do? Be honest. (Every session? Every substantive session? Only when it affects a scientific claim? Only when it affects a published output?)
Answer:

**Question 44:** What format works for you? (A markdown file you update? A structured template you fill in? A voice note you transcribe later? A simple date + task + model + what happened?)
Answer:

**Question 45:** The AI_USE_LOG proposed by ChatGPT has 13 fields per entry. How many fields would you actually fill in consistently?
Answer:

**Question 46:** For the IDEA_LEDGER: would you realistically register every intellectual seed before working with AI, or would you sometimes reconstruct the provenance afterwards?
Answer:

**Question 47:** For the DECISION_LOG: what counts as a "scientific decision" worth logging? Every method choice? Only major ones (e.g. "I chose multilevel over spatial")?
Answer:

**Question 48:** When you publish, what level of AI disclosure are you prepared to make? (A general acknowledgement? A detailed methods section? Sharing prompts as supplementary material?)
Answer:

---

## PART H - TOOL ECOSYSTEM & ENFORCEMENT

*These questions feed `AGENTS.md` - how the AI assistants actually behave.*

**Question 49:** What AI tools do you currently use or plan to use? (Claude, ChatGPT, Copilot at the host institution, GitHub Copilot, local models, others?) List all.
Answer:

**Question 50:** Which tool(s) do you consider your "primary research assistant" - the one that should load the full framework?
Answer:

**Question 51:** You said the AI should push back: "According to protocol X, I cannot do this. You must first..." How firm should this be? Should the AI refuse outright, or warn and proceed if you insist?
Answer:

**Question 52:** If you explicitly override a protocol ("I know, do it anyway"), should the AI comply with a log entry, or should some rules be truly non-overridable?
Answer:

**Question 53:** What should the AI do at the START of a new conversation/session? (Remind you of active protocols? Ask what phase you're in? Load silently and wait? Ask for a Human Intellectual Seed?)
Answer:

**Question 54:** Should different tools have different permission levels? (e.g. Claude for research thinking at D1-D3, Copilot for code at D2, ChatGPT for translation at D2, a local model for confidential data?)
Answer:

**Question 55:** When you work late, tired, under deadline pressure - that's when you said you'd be "lazy." Should the framework be stricter in those moments (the AI pushes back harder), or should it have an explicit "deadline mode" with documented relaxation of certain rules?
Answer:

---

## PART I - COGNITIVE PRESERVATION & LEARNING

*These questions address the deeper goal: not just ethical compliance, but preserving your development as a researcher. Grounded in the cognitive offloading literature and the the affiliated university test.*

**Question 56:** Are there tasks where you deliberately want to keep the friction - where the struggle IS the learning? (e.g. writing your first econometric specification by hand, doing your first literature map without AI, building your first composite indicator manually)
Answer:

**Question 57:** How do you plan to evolve your delegation levels over the three years? (Stricter in year 1, more delegation in year 3? Or constant?)
Answer:

**Question 58:** If in year 2 you realise the AI has been doing something you should have learned, what's your recovery plan?
Answer:

**Question 59:** Your thesis defence will test whether YOU understand the work. Which parts of the defence are you most worried about being questioned on - and should the framework specifically protect your competence-building in those areas?
Answer:

---

## PART J - EDGE CASES & DESIGN TENSIONS

*These are the hard questions where principles collide. Your answers here will determine the most important design choices.*

**Question 60:** The AI finds a paper that fundamentally challenges your hypothesis. Should it tell you proactively, or wait until you ask?
Answer:

**Question 61:** You ask the AI to reformulate a paragraph. Its version is better than yours - clearer, more precise, better structured. What do you do?
Answer:

**Question 62:** A partner in the the research project consortium sends you a document and asks for a summary. You could read it yourself (2 hours) or AI-summarise it (5 minutes). The summary will be shared with the consortium. What do you do?
Answer:

**Question 63:** You're building the maturity index. The AI suggests a weighting scheme you hadn't considered that looks promising. But you can't explain WHY it works - it just fits the data better. Do you use it?
Answer:

**Question 64:** You've been working with the AI for months and your writing style has been influenced by its output. Your "own voice" has shifted. Is this a problem? How would you even detect it?
Answer:

**Question 65:** The AI helps you prepare for your comité de suivi de thèse (CST). It anticipates objections and prepares answers. At the CST, you defend positions that were partly shaped by AI preparation. Is this legitimate?
Answer:

---

## PART K - FRAMEWORK MAINTENANCE

**Question 66:** How often will you review and update the framework? (Every 6 months? Every year? After each major milestone?)
Answer:

**Question 67:** Should your supervisor(s) see the framework? Should it be part of your thesis documentation?
Answer:

**Question 68:** If institutional rules change (new the host institution policy, new journal requirements, new ERA guidelines), who is responsible for updating the framework?
Answer:

**Question 69:** Is this framework just for you, or do you want it to be potentially reusable by other PhD students?
Answer:

**Question 70:** Final question - in one sentence, what is the single most important thing this framework must guarantee?
Answer:

---

*End of questionnaire. Return the completed file and we build the architecture.*









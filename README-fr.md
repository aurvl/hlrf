<p align="center">
  <img src="assets/main.png" alt="Human-Led Research Framework" style="border-radius: 13px;" />
</p>

<h3 align="center">Une méthode réutilisable pour une recherche assistée par IA</h3>

<p align="center">
  Le HLRF est un cadre scientifique et opérationnel destiné aux personnes qui utilisent l'IA générative dans leurs activités de recherche tout en préservant leur propriété intellectuelle, leurs compétences, la vérification et leur responsabilité.
</p>

<p align="center">
  <a href="README.md">🇬🇧 English</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AI-Research-blue" alt="AI Research" />
  <img src="https://img.shields.io/badge/Responsible-AI-green" alt="Responsible AI" />
  <img src="https://img.shields.io/badge/Human-in--the--loop-orange" alt="Human in the loop" />
  <img src="https://img.shields.io/badge/Research-Integrity-purple" alt="Research integrity" />
  <img src="https://img.shields.io/badge/Version-1.0-lightgrey" alt="Version 1.0" />
</p>

<p align="center">
  Il s'adresse aux doctorants, postdoctorants, enseignants-chercheurs, professeurs, ingénieurs de recherche, étudiants et autres professionnels de la recherche. Ce n'est ni un agent IA, ni un superviseur, ni un substitut à une méthode de recherche.
</p>

## Pourquoi ce framework est nécessaire

L'IA générative peut assister la recherche documentaire, la synthèse, la traduction, le code, le traitement des données, la rédaction et d'autres tâches. Les gains de productivité sont réels mais dépendent du contexte. Le rapport AI Index 2025 synthétise des effets d'environ 10 % à 45 % selon les études et les tâches, tout en signalant des limites persistantes de fiabilité et de raisonnement complexe (Maslej et al., 2025).

La question est donc de bénéficier de ces capacités sans externaliser les activités qui construisent l'identité du chercheur : questionnement, conceptualisation, formulation d'hypothèses, jugement méthodologique, interprétation, évaluation critique et responsabilité scientifique.

## La problématique de recherche

Les systèmes d'IA peuvent exécuter des fragments du travail de recherche, mais la recherche ne se réduit pas à produire du texte, du code ou des résumés plausibles. Une délégation excessive peut introduire des affirmations non vérifiées, des choix méthodologiques incompris, une dépendance cognitive et une responsabilité difficile à reconstruire.

> **Comment organiser l'assistance de l'IA afin de bénéficier de ses gains de productivité tout en maintenant l'agence épistémique, les compétences scientifiques, la responsabilité et la capacité d'auteur du chercheur ?**

Le HLRF répond à cette problématique en séparant les décisions intellectuelles humaines de l'assistance bornée de l'IA, en définissant des plafonds de délégation, en imposant la vérification et en assurant la traçabilité.

## Ce que fournit le HLRF

Le framework aide à définir le contexte de recherche, distinguer les tâches humaines des tâches délégables, vérifier les sorties de l'IA, attribuer les responsabilités, documenter les usages importants et préserver les compétences en développement.

Le résultat attendu n'est pas un chercheur au service d'un outil opaque, mais un chercheur qui reste le décideur scientifique tout en utilisant un instrument technique plus puissant.

## Le HLRF comme orchestrateur d'agents

Le HLRF constitue une couche d'orchestration pour les agents de recherche. Le dépôt est le corps opérationnel : identité, règles, limites, permissions, workflows, vérification, mémoire et traçabilité. Le modèle ou agent IA est la tête et l'interface d'exécution qui lit cette structure et agit à travers elle.

Le framework indique à l'agent comment se comporter, ce qu'il peut faire, ce qu'il doit demander, ce qu'il doit refuser et ce que le chercheur doit valider. Il n'accorde aucune autorité scientifique à l'IA : il l'organise autour de l'autorité du chercheur.

## Modèle opérationnel

```text
contexte humain / intuition intellectuelle humaine
                    ↓
          assistance IA délimitée
                    ↓
        vérification et critique humaines
                    ↓
             jugement et décision
                    ↓
             travail scientifique validé
                    ↓
             traçabilité et transparence
```

## Bénéfices attendus

Le HLRF vise une productivité encadrée, une division claire du travail, une meilleure propriété épistémique, une vérification systématique, la préservation des compétences, une traçabilité utile et une personnalisation selon le projet.

## Limites et compromis

Le HLRF ajoute de la planification, de la journalisation et de la vérification. Il peut être plus lent qu'un usage non encadré et ne garantit pas que toutes les erreurs ou dépendances seront détectées. Les niveaux de délégation sont des choix normatifs, pas des mesures validées du risque cognitif.

Ce dépôt est une **version 1**. Il n'a pas encore fait l'objet d'une estimation formelle, d'une étude contrôlée, d'une validation psychométrique ou d'un suivi longitudinal. Le système de tracking sert à observer l'évolution et à préparer une évaluation future, sans constituer une preuve d'efficacité.

## Processus de personnalisation

Ce template a été conçu à partir d'un cas de recherche doctorale, mais peut être adapté aux étudiants, enseignants, professeurs, ingénieurs de recherche, postdoctorants et autres professionnels.

### Avertissement important sur la confidentialité

Ne fournir que le minimum d'informations personnelles ou institutionnelles nécessaire. Ne jamais transmettre secrets, mots de passe, tokens, données brutes identifiables, données confidentielles ou informations protégées à un outil non autorisé. Si l'assistant demande trop d'informations, arrêter, anonymiser et demander de minimiser la demande.

1. Utiliser le [template de questionnaire de personnalisation](template_personalisation_questionnaire.md).
2. Répondre dans ses propres mots ; l'assistant ne doit rien inventer.
3. Utiliser les réponses et le dépôt comme modèle pour créer le framework personnalisé.
4. Relire, corriger et valider chaque fichier.

### Prompt 1 - générer le questionnaire de personnalisation

Se référer au [template de questionnaire](template_personalisation_questionnaire.md) et utiliser le dépôt comme modèle public.

### Prompt 2 - créer un framework personnalisé

Utiliser les réponses au questionnaire et le dépôt public comme référence. Créer ou adapter les documents listés dans le README anglais, notamment `AGENTS.md`, les protocoles `00` à `08`, les journaux dans `logs/` et le système dans `tracking/`. Ne rien inventer et marquer les éléments manquants comme `[TO BE CONFIRMED]`.

## Utiliser le dépôt comme référence

Il n'est pas nécessaire de cloner ou d'installer le dépôt. Fournir l'URL publique à l'assistant et travailler avec une copie locale du HLRF comme référence opérationnelle :

```text
https://github.com/aurvl/hlrf
```

### Exemple de prompt pour initialiser une session

```text
J'ai déjà une copie locale du framework HLRF dans `/chemin/vers/hlrf`. Utilise ce dossier comme référence pour cette session et le dossier `.aiact_logs/` du projet comme mémoire de travail.

Mon projet étudie l'impact du réchauffement climatique. Mon approche est [la décrire brièvement : fondée sur les preuves, prudente dans les affirmations causales et attentive aux explications concurrentes]. Lorsque j'explore un sujet, je commence par [décrire votre pratique : cartographier la littérature, identifier les mécanismes et désaccords, réduire le périmètre, puis définir une question empirique réalisable].

Pour cette session, produis une cartographie structurée de la littérature scientifique et institutionnelle publiée entre [année de début] et [année de fin] sur les impacts économiques du réchauffement climatique dans [périmètre]. Pour chaque source, indique la référence complète, la question, les données, la méthode, le résultat, les limites et le DOI ou l'URL stable. Regroupe les sources par mécanisme ou dispositif, distingue les éléments descriptifs des éléments causaux et fais apparaître les désaccords. Retourne un tableau et une courte synthèse des régularités observées.

Si un élément de contexte manque, demande uniquement l'information nécessaire à l'exécution de cette tâche. Travaille à partir de sources publiques ou anonymisées et enregistre la session dans les journaux du projet.
```

## Structure du dépôt

```text
00_RESEARCHER_IDENTITY.md                  # Identité, compétences, responsabilités non délégables
01_HUMAN_LED_RESEARCH_CHARTER.md           # Principes, workflow, règles et périmètre
02_DELEGATION_PROTOCOL.md                  # Niveaux et plafonds de délégation D0 à D3
03_IDEA_PROVENANCE_PROTOCOL.md             # Origine humaine des idées et hypothèses
04_METHOD_DECISION_PROTOCOL.md             # Responsabilité humaine des choix méthodologiques
05_EVIDENCE_AND_VERIFICATION_PROTOCOL.md   # Vérification des sources, données, codes et sorties
06_WRITING_AND_AUTHORSHIP_PROTOCOL.md      # Rédaction, auteurs et limites de la prose IA
07_AI_TRANSPARENCY_PROTOCOL.md             # Traçabilité et déclaration des usages IA
08_DATA_CONFIDENTIALITY_PROTOCOL.md        # Protection des données et outils autorisés
logs/                                      # Templates de journaux de projet
tracking/                                  # Suivi périodique de l'évolution
template_personalisation_questionnaire.md  # Template de questionnaire pour personnaliser le framework
```

## Références

1. Maslej, N., Fattorini, L., Perrault, R., Gil, Y., Parli, V., Kariuki, N., Capstick, E., Reuel, A., Brynjolfsson, E., Etchemendy, J., Ligett, K., Lyons, T., Manyika, J., Niebles, J. C., Shoham, Y., Wald, R., Walsh, T., Hamrah, A., Santarlasci, L., Betts Lotufo, J., Rome, A., Shi, A., & Oak, S. (2025). “The AI Index 2025 Annual Report.” AI Index Steering Committee, Institute for Human-Centered AI, Stanford University, Stanford, CA. https://doi.org/10.48550/arXiv.2504.07139
2. UNESCO. (2023). *Guidance for generative AI in education and research*. https://www.unesco.org/en/articles/guidance-generative-ai-education-and-research
3. Dakan, R., Feller, J., & Anthropic. (2025). *AI Fluency: Framework and Foundations*. https://www.anthropic.com/learn/claude-for-you
4. Anthropic. (2025). *AI Fluency: Delegation*. https://anthropic.skilljar.com/ai-fluency-framework-foundations?next=%2Fai-fluency-framework-foundations%2F291883

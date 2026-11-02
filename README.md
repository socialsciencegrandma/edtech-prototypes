# edtech-prototypes
*EdTech concept showcase*

Four interactive prototypes in one portable HTML file, built with Codex to turn an open-ended EdTech brief into concrete options for stakeholder evaluation and go/no-go decisions.

## From a broad brief to something people can try

The starting point was a vague request to build an EdTech tool for students. Before committing to one direction, I used Codex to vibecode four distinct experiences that people could explore, question and compare.

The showcase gives early conversations a concrete reference: participants can work through a sample interaction and explain where it fits—or fails to fit—their needs. It supports end-user interviews, focus group discussions (FGDs) with domain experts and administrative users, and direct presentations of the options to Singapore’s Ministry of Education.

The purpose is to inform which ideas merit further investigation, which need revision and which should stop. An interactive demonstration makes an idea easier to evaluate; it does not establish demand or educational value on its own.

## Explore the four concepts

| Concept | What the prototype demonstrates | What stakeholders can examine |
| --- | --- | --- |
| **Research reading and review** | Scan and read modes, passage-linked review tasks, evidence checks, recorded judgments and source-linked synthesis. | Whether the workflow helps students capture concerns and follow through while preserving their own reasoning. |
| **Educational participation and response** | Quick reactions, questions and assistance requests tied to a session moment, alongside response ownership and follow-up status. | Whether students can express their needs easily and educators or staff can act on them. |
| **Symbol-based accessible expression** | Symbols for logical relationships and editing commands, student-supplied meaning, proposed wording, revision, text export and optional speech. | Whether the interaction reduces the effort of academic expression without changing the student’s intended meaning. |
| **Farming simulator and agent orchestration learning** | Ordinary farming sim gameplay followed by a separate concept bridge and an orchestration exercise at each level up. | Whether familiar farming sim activities help students understand and apply orchestration concepts. |

The farming prototype includes two complete learning cycles:

**Farm level 1 → Bridge 1 → Exercise 1 → Farm level 2 → Bridge 2 → Exercise 2**

The farm itself contains no explicit agent orchestration elements. The connections are introduced on the bridge pages, then practised in separate exercises.

## Open and share

1. Download [learning-mockups.html](learning-mockups.html).
2. Open it in a modern web browser.
3. Select a concept tab and try its sample workflow.

The single file contains the HTML, styles and JavaScript. It opens locally without installation, a build process, an account or a server. The core interactions work offline; optional speech output depends on the browser and available voices.

This format makes the showcase easy to share with both non-technical and technical stakeholders. A recipient can open the same artifact used in a facilitated interview or presentation and explore it independently.

## Use in stakeholder evaluation

The four options provide a common starting point for different conversations:

- **End-user interviews:** observe how students interpret and navigate an experience, and discuss the problem it would need to solve in their actual work.
- **Expert and administrative FGDs:** examine learning value, accessibility, response responsibilities and institutional fit.
- **Ministry of Education presentations:** demonstrate the alternatives directly and discuss the evidence needed to decide whether each warrants further development.

The showcase supports these conversations. Interview responses and evaluation findings are recorded separately. Go/no-go decisions depend on the evidence gathered around the prototypes, rather than their visual polish or apparent completeness.

## Implementation and boundaries

Built with static HTML, CSS and JavaScript, with embedded compiled Tailwind CSS and Material Design 3 styling in baby pink, baby blue and white. Layouts adapt to desktop and mobile screens.

These are functional interaction prototypes with illustrative content. AI assistance, live transcription and multi-user routing are simulated through browser-local workflows; no live AI or session backend is connected. Edits and progress reset when the page reloads. Review records and accepted draft text can be downloaded through the provided export controls.

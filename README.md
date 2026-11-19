# SEN 201 SDLC Prompt Library

A publicly distributable collection of 105 independently usable AI prompts for the SEN 201 Software Engineering assignment.

## Project description

This repository contains reusable prompt templates for coursework on Software Development Life Cycle (SDLC) models. Each prompt is a complete, self-contained instruction set that a student can copy into ChatGPT, Claude or another capable AI platform. Every prompt ships with its own predefined case study, requires genuine online research, enforces an explicit student approval gate before any document is created and specifies two separate editable DOCX deliverables.

These files are prompts, not completed assignments. No assignment content, student record or generated document is stored in this repository.

Created by Omonire Great (GR8), a voluntary academic support initiative for Software Engineering students.

GitHub username: `Omonire`

## Purpose

The library exists to help SEN 201 students understand how software development models are selected and applied, and to give them a consistent, academically sound starting point for their assignment. The prompts standardise the required academic components while varying case studies, instructional structures and analytical emphasis so that students can choose a brief that fits their own learning needs.

## SDLC models covered

There are exactly seven model folders, each with exactly 15 prompts:

1. `01-WATERFALL-MODEL` - Waterfall Model
2. `02-V-MODEL` - V-Model (Verification and Validation Model)
3. `03-SPIRAL-MODEL` - Spiral Model
4. `04-PROTOTYPE-MODEL` - Prototype Model
5. `05-AGILE-MODEL` - Agile Model
6. `06-INCREMENTAL-MODEL` - Incremental Model
7. `07-ITERATIVE-MODEL` - Iterative Model

Total: 105 prompt files (`prompt-01.md` through `prompt-15.md` in each folder).

## How to select and copy a prompt

1. Decide which SDLC model you want to study or which one your lecturer has assigned.
2. Open the corresponding model folder.
3. Read the prompt IDs and case study titles to choose one scenario. Each scenario is unique; no case study is reused.
4. Open the chosen `prompt-NN.md` file and copy the entire contents.
5. Paste it into your AI platform as the first message of a new conversation.
6. Follow the stages exactly as written. Supply your own student details when asked.
7. Review the proposal carefully at Stage 6 and approve it explicitly only when you are satisfied.
8. Create your draw.io diagram yourself, verify it and insert the screenshot and live link into the generated document.

Do not substitute a different case study. The scenario is deliberately chosen to demonstrate the assigned model.

## The two DOCX deliverables

Each prompt requires the AI to produce two separate, editable Word documents after approval.

### Document One - Main assignment

The main SEN 201 assignment. It includes a professional title page, student information, a unique academic title, an introduction to software development models, a definition of a model, an overview of all seven SDLC models, an explanation of the selected model, the predefined case study, application of the model, justification, case-study-specific advantages, a structural diagram explanation, a diagram screenshot placeholder, a diagram URL placeholder, disadvantages, a conclusion and verified references.

### Document Two - Academic explanation and learning guide

A tutor-style companion that explains what the assignment is about, the meaning of each section, why the scenario was selected, how the model applies, why the advantages and disadvantages matter, how to interpret the structural diagram, how to draw it in draw.io, key terminology, likely lecturer questions and suggested answers that demonstrate genuine understanding. It complements the main assignment rather than repeating it.

## Online research requirements

Every prompt requires the AI to research the topic online before preparing the assignment. It must search for academic and technical material, prioritise textbooks, peer-reviewed publications, university resources, official documentation and reputable Software Engineering publications, verify titles, authors, dates and URLs, cross-check important claims, use in-text citations and include a formatted reference list. It must never invent publications, authors, DOIs, URLs, dates or case-study evidence. If browsing is unavailable, the AI must disclose this and ask how to proceed rather than pretending research occurred.

## Student approval process

The approval gate is strict and identical in principle across all prompts:

1. Stage 1 - Collect student information (name, matriculation number, department, faculty, academic level and institution).
2. Stage 2 - Present the assigned model and predefined scenario.
3. Stage 3 - Conduct online research.
4. Stage 4 - Propose an academic title.
5. Stage 5 - Present the outline, scenario analysis, research findings and references.
6. Stage 6 - Ask the student to review the proposal.
7. Stage 7 - Wait for explicit approval.

An acceptable approval statement is:

> I have reviewed the proposed structure and research. I approve. You may proceed with document generation.

Silence, ordinary acknowledgements and ambiguous replies are not approval. If changes are requested, the proposal must be revised and approval requested again. No DOCX documents may be generated before explicit approval.

## draw.io instructions

Every prompt makes a structural diagram compulsory. draw.io is a free browser-based diagramming tool at https://app.diagrams.net/ . Each prompt explains what draw.io is, why it is appropriate for Software Engineering diagrams, the exact diagram required for that model, the important shapes, labels, arrows and connections, and step-by-step drawing guidance.

The student must create the diagram manually, export a screenshot, generate a live link and place both in the main assignment at these placeholders:

```text
[INSERT YOUR DRAW.IO STRUCTURAL DIAGRAM SCREENSHOT HERE]

[INSERT YOUR DRAW.IO LIVE DIAGRAM LINK HERE]
```

The AI must not claim that it created the diagram. The student is responsible for verifying the diagram before submission.

## Academic integrity guidance

These prompts are educational guides, not answer keys. Use them to understand how to approach the assignment, then review, verify, edit and take ownership of everything you submit. Check every technical claim, citation and reference independently. Follow your lecturer's instructions and your institution's academic integrity policies. If your lecturer specifies a different referencing style, a different structure or additional requirements, the lecturer's instructions take priority over this template.

AI-generated content can contain inaccuracies. Do not submit work you do not understand and can explain.

## Disclaimer

This repository is a voluntary academic support resource created by Omonire Great (GR8) to assist Software Engineering students with understanding and approaching their SEN 201 assignment.

The prompts, examples and templates provided here are educational guides. Their use does not guarantee a pass, a particular grade, or academic success.

Students remain responsible for understanding, reviewing, verifying, editing and taking ownership of all work they submit.

AI-generated content may contain inaccuracies. Students must verify technical information, research findings, citations and references independently.

Students must follow their lecturer's instructions and their institution's academic integrity policies.

The creator does not guarantee academic outcomes and accepts no responsibility for grades, penalties or other academic consequences resulting from the use or misuse of this resource.

This repository is provided voluntarily and in good faith to support fellow students.

## Repository structure

```text
SEN201_Model/
├── README.md
├── LICENSE
├── .gitignore
├── 01-WATERFALL-MODEL/
│   └── prompt-01.md ... prompt-15.md
├── 02-V-MODEL/
│   └── prompt-01.md ... prompt-15.md
├── 03-SPIRAL-MODEL/
│   └── prompt-01.md ... prompt-15.md
├── 04-PROTOTYPE-MODEL/
│   └── prompt-01.md ... prompt-15.md
├── 05-AGILE-MODEL/
│   └── prompt-01.md ... prompt-15.md
├── 06-INCREMENTAL-MODEL/
│   └── prompt-01.md ... prompt-15.md
└── 07-ITERATIVE-MODEL/
    └── prompt-01.md ... prompt-15.md
```

The root folder reuse is intentional: the pre-existing `SEN201_Model` directory was adopted as the library root to avoid a redundant nested project.

## Licence

The original prompt text, README and repository organisation in this project are released under the MIT License. See `LICENSE`.

The MIT License does not cover third-party research material, textbooks, papers, documentation or any copyrighted source that a student or AI may consult when using these prompts. Those materials belong to their respective owners and must be cited and used according to their own terms. No third-party research content is bundled in this repository.

## Contributing

Contributions that improve clarity, academic accuracy, accessibility or model-scenario fit are welcome.

1. Open an issue describing the proposed change and the prompt ID it affects.
2. Keep the required structure intact: student information collection, research requirement, approval gate, two DOCX deliverables, draw.io instructions and the full academic content checklist.
3. Ensure any new scenario is genuinely distinct and appropriate to its assigned model.
4. Do not add personal student data, generated assignments, API keys or private configuration.
5. Submit a pull request with a short description of what changed and why.

Questions and suggestions may also be raised through the repository's issue tracker.

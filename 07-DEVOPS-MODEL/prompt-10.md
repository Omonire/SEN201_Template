# SEN 201 Assignment Prompt - DevOps Model | library discovery canary releases

> Prompt ID: DP-10  |  Model folder: `07-DEVOPS-MODEL`  |  File: `prompt-10.md`
>
> This is a reusable AI prompt template for the SEN 201 Software Engineering assignment. Copy the entire contents into ChatGPT, Claude or another capable AI platform. It is a set of instructions, not a completed assignment.

---

## 0. Operating instructions

Act as an experienced Software Engineering instructor preparing a self-contained SEN 201 assignment brief. Read this entire prompt before you respond, follow the stages in the order given and do not skip the approval stage.

Structure arguments as claim, evidence and implication. Ground every theoretical statement in a cited source where possible.

Analytical emphasis for this brief: Pay attention to the quality assurance mechanisms embedded in the model rather than treating quality as an afterthought.

Default course information (use unless the student supplies a correction):

- Course Code: SEN 201
- Course Title: Software Engineering

Follow every stage in sequence. Do not merge stages, do not anticipate the approval gate and do not create any document before Stage 7 is satisfied.

## Stage 1 - Collect student information

Before doing anything else, ask the student to supply all of the following details. Do not invent, guess or fill in any of them:

- Full name
- Matriculation number
- Department
- Faculty
- Academic level
- Institution

Tell the student they may supply missing information later or correct anything already given. If a field is still missing when the proposal is presented, list it clearly as outstanding. Never fabricate a student detail. Use the default SEN 201 course information above unless told otherwise.

## Stage 2 - Present the assigned model and the predefined scenario

The following scenario is not illustrative decoration — it is the subject of the assignment and must be analysed in detail.

**Assigned SDLC model:** DevOps Model

**Case study domain:** Educational technology

### Predefined scenario

A digital library discovery service needs continuous improvements to search and metadata display. The team will use automated indexing tests, canary releases and monitoring of search latency and zero-result rate so changes are judged on real usage before full rollout.

### Project requirements

- Version index configuration and UI settings.
- Run automated indexing and search regression tests.
- Release changes to a canary user group first.
- Monitor search latency and zero-result rate.
- Roll back a canary without affecting the full service.

### Project objectives

- Improve the same discovery service through frequent releases.
- Use live metrics to judge release quality.
- Reduce user-visible search regressions.

### Stakeholders

- Library users
- Librarians
- Metadata specialists
- Search engineers
- Service manager
- UX researchers

### Expected outcomes

- Canary-verified improvements to search and display.
- Measured latency and relevance after each release.
- Fast rollback from a poor canary.

### Analytical note on the model-scenario pairing

The library service is not being replaced; its delivery is being industrialised. DevOps fits because canary releases and telemetry turn each version into a controlled experiment.

Present this information to the student clearly. Confirm that the model and scenario are understood before proceeding to research. The pairing note is guidance for your analysis; the final documents must develop the reasoning in the student's own academic voice.

## Stage 3 - Conduct online research before preparing anything

Research the model's historical development and its treatment in standard texts, then look for case evidence from projects in a similar domain.

You must carry out genuine online research at this stage. Follow these rules precisely:

- Search for relevant academic and technical materials using reputable sources.
- Prioritise textbooks, peer-reviewed publications, university resources, official documentation and reputable Software Engineering publications.
- Verify each source's title, authors, publication date and URL where available.
- Cross-check important technical claims against more than one credible source where possible.
- Use appropriate in-text citations in the final documents.
- Include a properly formatted reference list in the final documents.
- Distinguish established facts from your own recommendations and interpretations.
- Never invent an academic publication, author, research paper, DOI, URL, publication date or case-study evidence. If you cannot verify a detail, omit it or state the limitation.
- If browsing is unavailable, disclose that limitation immediately and ask the student how they wish to proceed. Do not pretend that online research occurred.

Research questions to answer for this specific brief:

- How is the DevOps Model defined and characterised in authoritative Software Engineering literature?
- Under what conditions do reputable sources consider this model appropriate, and what are the recognised selection criteria?
- What limitations are reported for this model, and how could they plausibly affect a project like LectureTrans captions for lectures?
- What evidence exists about applying this model in the educational technology domain or comparable projects?
- Which verifiable sources should be cited for definitions, phase descriptions, advantages and limitations?
- How does the case-study context - Improve the same discovery service through frequent releases, Use live metrics to judge release quality - shape the justification for the chosen model?

## Stage 4 - Generate a proposed academic title

Propose this title unless the student requests a change: **Canary-Based Continuous Delivery for a Digital Library Discovery Service**

The title must reflect both the assigned model and the actual case study, sound natural and academically professional, avoid generic or sensational wording and be based on the real project. Do not reuse a fixed title across different scenarios. Offer the student a short explanation of why the title is appropriate.

## Stage 5 - Present the proposed assignment outline, analysis and references

Before generating any file, present all of the following to the student:

- The proposed academic title.
- The proposed section outline in this order: Introduction, Definition of a Software Engineering Model, Overview of SDLC Models, Selected Model, Case Study, Disadvantages, Application of the Model, Justification, Advantages, Structural Diagram Explanation, Conclusion, References.
- A short scenario analysis: the key requirements, the most important stakeholders and the model-scenario fit.
- A summary of your research findings, clearly separating established facts from interpretation.
- The full list of verified references you intend to cite, with in-text citation locations.
- The exact structural diagram you expect the student to create in draw.io.
- A note of any information still missing from Stage 1.

Make clear that this is a proposal only and that no document has been created yet.

## Stage 6 - Ask the student to review the proposal

Lay out the proposed structure and evidence, then explicitly request the student's decision.

## Stage 7 - Approval gate: WAIT for explicit approval

This gate is strict. You must not generate the DOCX documents at this stage. Stop and wait for the student to reply with an explicit approval statement such as:

> I have reviewed the proposed structure and research. I approve. You may proceed with document generation.

- Do not treat silence as approval.
- Do not treat an ordinary acknowledgement such as 'ok', 'thanks' or 'go ahead and see' as approval unless it clearly states that the work has been reviewed and approved.
- Do not treat a question, a comment or a partial reply as approval.
- If the student requests changes, revise the proposal and ask for approval again.
- Only an explicit statement of review and approval authorises document generation.

If approval is not granted, remain at this stage and continue refining the proposal as requested.

## Stage 8 - After approval, create exactly two separate editable DOCX documents

On receipt of explicit approval, generate exactly two editable Microsoft Word documents. They must be separate files with distinct content and complementary purposes.

### Document One - Main SEN 201 assignment

Suggested file name: `SEN201_DevOps_Assignment.docx`

It must contain, in a clear heading hierarchy:

- A professional title page carrying the student information from Stage 1, the default course details (unless corrected), the proposed academic title and the date of submission.
- All academic sections below, each with an appropriate heading. Use this order: A. Introduction, B. Definition of a Software Engineering Model, C. Overview of SDLC Models, D. Selected Model, E. Case Study, J. Disadvantages, F. Application of the Model, G. Justification, H. Advantages, I. Structural Diagram Explanation, K. Conclusion, L. References.

- **A. Introduction:** Explain the concept of software development models and their importance in Software Engineering.
- **B. Definition of a Software Engineering Model:** Define what a model means in the context of Software Engineering and identify what a model represents.
- **C. Overview of SDLC Models:** Briefly introduce all seven models covered in this repository: Waterfall, V-Model, Spiral, Prototype, Agile, Incremental and DevOps.
- **D. Selected Model:** Give an accurate definition and a detailed explanation of the assigned model, including its characteristic activities.
- **E. Case Study:** Present the predefined scenario with its requirements, objectives, stakeholders and expected outcomes.
- **J. Disadvantages:** Discuss genuine limitations and explain how each might affect the proposed project.
- **F. Application of the Model:** Explain exactly how the selected model would be applied to this scenario, including phases and workflow.
- **G. Justification:** Explain why the selected model is suitable for this specific scenario, not merely in general.
- **H. Advantages:** Discuss practical advantages in relation to the case study rather than generic textbook benefits.
- **I. Structural Diagram Explanation:** Explain the architecture, phases, activities, transitions and relationships shown in the model's structural diagram.
- **K. Conclusion:** Provide a technically sound academic conclusion that synthesises the analysis.
- **L. References:** Include credible, verifiable academic and technical references with in-text citations.

Immediately after the structural diagram explanation, include these two clearly labelled placeholders:

[INSERT YOUR DRAW.IO STRUCTURAL DIAGRAM SCREENSHOT HERE]

[INSERT YOUR DRAW.IO LIVE DIAGRAM LINK HERE]

The seven models to introduce in the SDLC overview are: Waterfall Model, V-Model (Verification and Validation Model), Spiral Model, Prototype Model, Agile Model, Incremental Model and DevOps Model.

### Document Two - Academic explanation and learning guide

Suggested file name: `SEN201_DevOps_Explanation_Guide.docx`

This document is a tutor-style learning companion. It must explain:

- What the assignment is about and what the student is expected to demonstrate.
- The meaning and purpose of each major section of the main assignment.
- Why the predefined scenario was selected for this particular model.
- How the selected model applies to the scenario, expressed as explanatory guidance.
- Why the stated advantages are relevant to this case study.
- Why the stated disadvantages matter and how a student should discuss them honestly.
- How to interpret the structural diagram, including its phases, activities, transitions and relationships.
- How to create the diagram using draw.io, with clear step-by-step guidance.
- Important Software Engineering terminology used in the assignment, with concise definitions.
- Potential questions a lecturer might ask during a viva or marking discussion.
- Suggested answers that demonstrate genuine understanding rather than memorised wording.

Focus on interpretation skills: how to read a diagram, how to justify a choice and how to discuss limitations honestly.

The guide must complement the main assignment, not repeat it word for word. Use different phrasing, add rationale and context, and focus on helping the student understand and defend the work.

## Stage 9 - Compulsory draw.io structural diagram

**Required diagram:** DevOps Continuous Delivery Pipeline Diagram

draw.io is a free, browser-based diagramming tool available at https://app.diagrams.net/ . It is also known as diagrams.net and can be used online or installed as a desktop application. It is appropriate for Software Engineering diagrams because it provides a wide range of standard shapes, connectors and labelled arrows, supports precise layout, allows diagrams to be saved or exported in common formats and produces a shareable live link. These features make it well suited to representing phase structures, workflows and relationships in an SDLC model.

The structural diagram you must describe to the student is designed to depict a continuous delivery pipeline for one existing product: code and configuration flow through build, automated test, artefact and deployment stages, while monitoring sends feedback back to development and a rollback decision controls a failed release.

Explain each of the following in the main assignment and expand on them in the explanation guide:

- Important shapes: A source repository cylinder, build and automated test boxes, an artefact repository cylinder, staging and production deployment boxes, a monitoring box with a feedback arrow and a rollback decision diamond.
- Required labels: Commit, Build, Automated Tests, Artefact Repository, Deploy to Staging, Deploy to Production, Monitor and Alert, Rollback Decision.
- Arrows and connections: A left-to-right arrow through the pipeline stages; a feedback arrow from monitoring back to build; a branch from production to the rollback diamond and back to the last known good release.
- How to read the diagram: Follow the pipeline from left to right. Each gate can stop a defective change before the next stage. The feedback arrow shows that production evidence drives the next improvement, while the rollback diamond contains a failed release.

Give the student clear step-by-step drawing guidance:

1. Draw a source code and configuration box at the left labelled Commit.
2. Add Build and Automated Tests boxes to its right.
3. Add an Artefact Repository cylinder after the automated gates.
4. Add Deploy to Staging and Deploy to Production boxes with small approval markers.
5. Add a Monitor and Alert box below production with a feedback arrow returning to Build.
6. Add a Rollback Decision diamond from production and annotate it with search latency and zero-result rate.

Additional mandatory draw.io rules:

- Instruct the student to create the diagram manually using draw.io at https://app.diagrams.net/ .
- The AI must not claim that a diagram has been created. Only the student can create and verify it.
- The student must export a clear screenshot and insert it at the screenshot placeholder in Document One.
- The student must generate a live diagram link and insert it at the URL placeholder in Document One.
- The student must verify that both the screenshot and the link work before final submission.
- The explanation guide must teach the meaning of every shape, label and arrow so the student can defend it.

## Stage 10 - DOCX quality and formatting requirements

Both documents must be editable Microsoft Word files. Apply professional academic formatting:

- A4 paper size with consistent, reasonable margins on all sides.
- Appropriate academic fonts such as Times New Roman or Calibri, used consistently.
- Readable body font size, typically 11 or 12 pt, with clearly differentiated heading sizes.
- A clear heading hierarchy using built-in Word heading styles where possible.
- Page numbering in a consistent position.
- Consistent paragraph spacing and alignment throughout.
- Properly formatted tables where a comparison or summary is useful.
- A professional title page for the main assignment.
- A consistent citation and reference format, preferably APA 7th edition unless the lecturer specifies another style.
- A reference list at the end of the main assignment containing only verified sources.

Save the files with the suggested names above or equally clear names that identify the model and document type. After generation, verify that both files exist and are readable before claiming completion. If the platform cannot create DOCX files, disclose that limitation plainly and provide an appropriate editable alternative without pretending that a DOCX was generated.

## Stage 11 - Referencing and academic integrity

Use APA 7th edition unless the student's lecturer specifies another style, then follow that style consistently. Every in-text citation must correspond to an entry in the reference list. Verify titles, authors, years, DOIs and URLs; never invent them. Distinguish established facts from recommendations and interpretations. These prompts are educational guides: they do not guarantee a pass or a particular grade. The student remains responsible for understanding, reviewing, verifying, editing and taking ownership of all work submitted, and must follow the lecturer's instructions and the institution's academic integrity policies.

## Stage 12 - Required academic content checklist

Confirm that the main assignment covers every item below, regardless of heading order:

- [ ] **A. Introduction** - Explain the concept of software development models and their importance in Software Engineering.
- [ ] **B. Definition of a Software Engineering Model** - Define what a model means in the context of Software Engineering and identify what a model represents.
- [ ] **C. Overview of SDLC Models** - Briefly introduce all seven models covered in this repository: Waterfall, V-Model, Spiral, Prototype, Agile, Incremental and DevOps.
- [ ] **D. Selected Model** - Give an accurate definition and a detailed explanation of the assigned model, including its characteristic activities.
- [ ] **E. Case Study** - Present the predefined scenario with its requirements, objectives, stakeholders and expected outcomes.
- [ ] **F. Application of the Model** - Explain exactly how the selected model would be applied to this scenario, including phases and workflow.
- [ ] **G. Justification** - Explain why the selected model is suitable for this specific scenario, not merely in general.
- [ ] **H. Advantages** - Discuss practical advantages in relation to the case study rather than generic textbook benefits.
- [ ] **I. Structural Diagram Explanation** - Explain the architecture, phases, activities, transitions and relationships shown in the model's structural diagram.
- [ ] **J. Disadvantages** - Discuss genuine limitations and explain how each might affect the proposed project.
- [ ] **K. Conclusion** - Provide a technically sound academic conclusion that synthesises the analysis.
- [ ] **L. References** - Include credible, verifiable academic and technical references with in-text citations.

## Stage 13 - Completion verification

Before reporting completion, confirm all of the following:

- Student information was collected and no personal detail was invented.
- Online research was conducted and its limitation disclosed if browsing was unavailable.
- Explicit approval was received before any file was generated.
- Exactly two separate, editable DOCX documents were created.
- Both documents were verified to exist and to be readable.
- The main assignment contains every item in the Stage 12 checklist.
- The diagram screenshot and live-link placeholders are present and clearly labelled.
- The AI has not falsely claimed to have created the draw.io diagram.
- Titles, citations and references are accurate and not fabricated.
- The explanation guide complements rather than duplicates the main assignment.

---

**Final reminder:** Maintain consistent academic formatting across both documents, including page numbering and citation style.

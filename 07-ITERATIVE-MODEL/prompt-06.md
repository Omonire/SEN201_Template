# SEN 201 Assignment Prompt - Iterative Model | FlowOpt traffic signal timing optimiser

> Prompt ID: IT-06  |  Model folder: `07-ITERATIVE-MODEL`  |  File: `prompt-06.md`
>
> This is a reusable AI prompt template for the SEN 201 Software Engineering assignment. Copy the entire contents into ChatGPT, Claude or another capable AI platform. It is a set of instructions, not a completed assignment.

---

## 0. Operating instructions

Imagine you are reviewing an assignment brief on behalf of the course examiner. Apply the same standards here: research first, propose second, generate only after explicit student approval.

Write as you would in a marks-bearing university assignment: coherent paragraphs, topic sentences and explicit justification for every modelling decision.

Analytical emphasis for this brief: Emphasise the role of documentation as both a control artefact and a communication tool for this project.

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

Below is the project scenario that anchors the assignment. Treat every listed requirement as part of the official brief.

**Assigned SDLC model:** Iterative Model

**Case study domain:** Transportation

### Predefined scenario

FlowOpt, a city traffic-management optimisation project. Signal timing must respond to changing travel patterns. The optimisation tool will be refined in repeated cycles as new traffic data arrives, each version tested against the same corridor performance measures.

### Project requirements

- Model traffic flow on a defined corridor.
- Propose signal timing plans for stated objectives.
- Evaluate plans against delays and queue lengths.
- Require engineer approval before deployment.
- Refine the optimiser in repeated data-driven cycles.

### Project objectives

- Reduce congestion on the target corridor.
- Improve optimisation quality through repeated refinement.
- Keep engineers in control of final signal plans.

### Stakeholders

- Traffic engineers
- Transport planners
- Road users
- Simulation analysts
- City managers
- Safety officers

### Expected outcomes

- Progressively better timing plans.
- Documented performance comparison across cycles.
- Engineer-approved deployment at every stage.

### Analytical note on the model-scenario pairing

Optimisation is inherently a repeated refinement activity. The Iterative Model matches because each cycle revisits the same optimiser with updated data and improved methods, producing a better version rather than a new functional area.

Present this information to the student clearly. Confirm that the model and scenario are understood before proceeding to research. The pairing note is guidance for your analysis; the final documents must develop the reasoning in the student's own academic voice.

## Stage 3 - Conduct online research before preparing anything

Begin with foundational references, then seek recent scholarly material to confirm that your understanding reflects current teaching practice.

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

- How is the Iterative Model defined and characterised in authoritative Software Engineering literature?
- Under what conditions do reputable sources consider this model appropriate, and what are the recognised selection criteria?
- What limitations are reported for this model, and how could they plausibly affect a project like FlowOpt traffic signal timing optimiser?
- What evidence exists about applying this model in the transportation domain or comparable projects?
- Which verifiable sources should be cited for definitions, phase descriptions, advantages and limitations?
- How does the case-study context - Reduce congestion on the target corridor., Improve optimisation quality through repeated refinement - shape the justification for the chosen model?

## Stage 4 - Generate a proposed academic title

Propose this title unless the student requests a change: **Iterative Optimisation of Signal Timing in the FlowOpt Traffic Management Tool**

The title must reflect both the assigned model and the actual case study, sound natural and academically professional, avoid generic or sensational wording and be based on the real project. Do not reuse a fixed title across different scenarios. Offer the student a short explanation of why the title is appropriate.

## Stage 5 - Present the proposed assignment outline, analysis and references

Before generating any file, present all of the following to the student:

- The proposed academic title.
- The proposed section outline in this order: Introduction, Definition of a Software Engineering Model, Overview of SDLC Models, Selected Model, Case Study, Application of the Model, Advantages, Structural Diagram Explanation, Justification, Disadvantages, Conclusion, References.
- A short scenario analysis: the key requirements, the most important stakeholders and the model-scenario fit.
- A summary of your research findings, clearly separating established facts from interpretation.
- The full list of verified references you intend to cite, with in-text citation locations.
- The exact structural diagram you expect the student to create in draw.io.
- A note of any information still missing from Stage 1.

Make clear that this is a proposal only and that no document has been created yet.

## Stage 6 - Ask the student to review the proposal

Seek an explicit decision on the proposed assignment. An acknowledgement is not a decision.

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

Suggested file name: `SEN201_Iterative_Assignment.docx`

It must contain, in a clear heading hierarchy:

- A professional title page carrying the student information from Stage 1, the default course details (unless corrected), the proposed academic title and the date of submission.
- All academic sections below, each with an appropriate heading. Use this order: A. Introduction, B. Definition of a Software Engineering Model, C. Overview of SDLC Models, D. Selected Model, E. Case Study, F. Application of the Model, H. Advantages, I. Structural Diagram Explanation, G. Justification, J. Disadvantages, K. Conclusion, L. References.

- **A. Introduction:** Explain the concept of software development models and their importance in Software Engineering.
- **B. Definition of a Software Engineering Model:** Define what a model means in the context of Software Engineering and identify what a model represents.
- **C. Overview of SDLC Models:** Briefly introduce all seven models covered in this repository: Waterfall, V-Model, Spiral, Prototype, Agile, Incremental and Iterative.
- **D. Selected Model:** Give an accurate definition and a detailed explanation of the assigned model, including its characteristic activities.
- **E. Case Study:** Present the predefined scenario with its requirements, objectives, stakeholders and expected outcomes.
- **F. Application of the Model:** Explain exactly how the selected model would be applied to this scenario, including phases and workflow.
- **H. Advantages:** Discuss practical advantages in relation to the case study rather than generic textbook benefits.
- **I. Structural Diagram Explanation:** Explain the architecture, phases, activities, transitions and relationships shown in the model's structural diagram.
- **G. Justification:** Explain why the selected model is suitable for this specific scenario, not merely in general.
- **J. Disadvantages:** Discuss genuine limitations and explain how each might affect the proposed project.
- **K. Conclusion:** Provide a technically sound academic conclusion that synthesises the analysis.
- **L. References:** Include credible, verifiable academic and technical references with in-text citations.

Immediately after the structural diagram explanation, include these two clearly labelled placeholders:

[INSERT YOUR DRAW.IO STRUCTURAL DIAGRAM SCREENSHOT HERE]

[INSERT YOUR DRAW.IO LIVE DIAGRAM LINK HERE]

The seven models to introduce in the SDLC overview are: Waterfall Model, V-Model (Verification and Validation Model), Spiral Model, Prototype Model, Agile Model, Incremental Model and Iterative Model.

### Document Two - Academic explanation and learning guide

Suggested file name: `SEN201_Iterative_Explanation_Guide.docx`

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

Explain section meanings using short teaching examples drawn from the case study, without reproducing the assignment text.

The guide must complement the main assignment, not repeat it word for word. Use different phrasing, add rationale and context, and focus on helping the student understand and defend the work.

## Stage 9 - Compulsory draw.io structural diagram

**Required diagram:** Iterative Refinement Cycle Diagram

draw.io is a free, browser-based diagramming tool available at https://app.diagrams.net/ . It is also known as diagrams.net and can be used online or installed as a desktop application. It is appropriate for Software Engineering diagrams because it provides a wide range of standard shapes, connectors and labelled arrows, supports precise layout, allows diagrams to be saved or exported in common formats and produces a shareable live link. These features make it well suited to representing phase structures, workflows and relationships in an SDLC model.

The structural diagram you must describe to the student is designed to depict repeated cycles applied to the same product, where each version is evaluated and refined before the next, showing that improvement comes from successive versions of one capability rather than from adding separate functional slices.

Explain each of the following in the main assignment and expand on them in the explanation guide:

- Important shapes: A series of concentric or overlapping circles for versions, a central product core, an evaluation symbol and a feedback arrow returning to the next version.
- Required labels: Version 1 Baseline, Version 2 Refined, Version 3 Refined, Evaluate Against Criteria, Collect Feedback, Plan Next Refinement.
- Arrows and connections: A circular arrow around the product core passing through Evaluate and Plan; arrows from one version circle to the next labelled Refine.
- How to read the diagram: Follow the circular arrow. The product core stays the same in identity while each pass improves its quality, accuracy or design. Evaluation evidence from one version determines the refinement goals of the next.

Give the student clear step-by-step drawing guidance:

1. Draw three overlapping circles around a central core labelled Target Capability.
2. Label the circles Version 1, Version 2 and Version 3 from inner to outer.
3. Draw a circular arrow around the circles.
4. Place an Evaluate Against Criteria box at the top of the circle and a Collect Feedback box at the right.
5. Add arrows from each version circle to the next labelled Refine.
6. Annotate the diagram with the specific measure used to judge improvement in this case study.

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
- [ ] **C. Overview of SDLC Models** - Briefly introduce all seven models covered in this repository: Waterfall, V-Model, Spiral, Prototype, Agile, Incremental and Iterative.
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

**Final reminder:** Every reference must be one you have verified; remove anything you cannot confirm rather than guessing.

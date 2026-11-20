# SEN 201 Assignment Prompt - Waterfall Model | MediChain pharmacy warehouse inventory control

> Prompt ID: WF-08  |  Model folder: `01-WATERFALL-MODEL`  |  File: `prompt-08.md`
>
> This is a reusable AI prompt template for the SEN 201 Software Engineering assignment. Copy the entire contents into ChatGPT, Claude or another capable AI platform. It is a set of instructions, not a completed assignment.

---

## 0. Operating instructions

This prompt is a complete assignment specification for SEN 201. Follow it literally. The receiving AI must gather details, investigate the topic online, propose a plan and pause until the student explicitly approves it.

Use plain, unambiguous technical English. Where a term has more than one common meaning, state which meaning the assignment adopts.

Analytical emphasis for this brief: Emphasise the relationship between development activities and their corresponding checking activities wherever the model defines one.

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

The assignment centres on the case study that follows. Extract requirements, objectives and stakeholders directly from it.

**Assigned SDLC model:** Waterfall Model

**Case study domain:** Inventory management

### Predefined scenario

MediChain, a pharmaceutical distributor operating a single central warehouse. MediChain needs a warehouse inventory system that tracks batch numbers and expiry dates under a fixed national good-distribution-practice rule set. The required records and stock movement procedures are prescribed and unchanged, allowing a complete requirements definition before design.

### Project requirements

- Record goods receipt with supplier, batch number and expiry date.
- Enforce first-expiry-first-out picking rules.
- Track stock movement between defined warehouse zones.
- Block dispensing of expired or quarantined batches.
- Generate regulatory stock and traceability reports.

### Project objectives

- Maintain accurate batch-level stock records.
- Comply with good distribution practice record keeping.
- Prevent expired stock from reaching customers.

### Stakeholders

- Warehouse manager
- Pharmacist in charge
- Storekeepers
- Quality assurance officer
- Regulatory inspectorate
- Retail pharmacy clients

### Expected outcomes

- Full batch traceability from supplier to customer.
- Reduced expiry-related losses.
- Inspection-ready regulatory reports.

### Analytical note on the model-scenario pairing

The governing distribution rules are fixed and the warehouse procedures are standardised, so requirements can be frozen with confidence. Waterfall's sequential verification ensures each rule is checked before the next phase begins, which is essential where a records error could have patient-safety consequences.

Present this information to the student clearly. Confirm that the model and scenario are understood before proceeding to research. The pairing note is guidance for your analysis; the final documents must develop the reasoning in the student's own academic voice.

## Stage 3 - Conduct online research before preparing anything

Find sources that explain the model's workflow and sources that discuss its risk profile, so the advantages and disadvantages are evidence-based.

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

- How is the Waterfall Model defined and characterised in authoritative Software Engineering literature?
- Under what conditions do reputable sources consider this model appropriate, and what are the recognised selection criteria?
- What limitations are reported for this model, and how could they plausibly affect a project like MediChain pharmacy warehouse inventory control?
- What evidence exists about applying this model in the inventory management domain or comparable projects?
- Which verifiable sources should be cited for definitions, phase descriptions, advantages and limitations?
- How does the case-study context - Maintain accurate batch-level stock records., Comply with good distribution practice record keeping - shape the justification for the chosen model?

## Stage 4 - Generate a proposed academic title

Propose this title unless the student requests a change: **Waterfall Model Application for Batch-Traceable Pharmaceutical Inventory Control at MediChain**

The title must reflect both the assigned model and the actual case study, sound natural and academically professional, avoid generic or sensational wording and be based on the real project. Do not reuse a fixed title across different scenarios. Offer the student a short explanation of why the title is appropriate.

## Stage 5 - Present the proposed assignment outline, analysis and references

Before generating any file, present all of the following to the student:

- The proposed academic title.
- The proposed section outline in this order: Introduction, Definition of a Software Engineering Model, Overview of SDLC Models, Selected Model, Case Study, Application of the Model, Advantages, Justification, Structural Diagram Explanation, Disadvantages, Conclusion, References.
- A short scenario analysis: the key requirements, the most important stakeholders and the model-scenario fit.
- A summary of your research findings, clearly separating established facts from interpretation.
- The full list of verified references you intend to cite, with in-text citation locations.
- The exact structural diagram you expect the student to create in draw.io.
- A note of any information still missing from Stage 1.

Make clear that this is a proposal only and that no document has been created yet.

## Stage 6 - Ask the student to review the proposal

Pause here and ask the student to review the material as though they were submitting it themselves.

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

Suggested file name: `SEN201_Waterfall_Assignment.docx`

It must contain, in a clear heading hierarchy:

- A professional title page carrying the student information from Stage 1, the default course details (unless corrected), the proposed academic title and the date of submission.
- All academic sections below, each with an appropriate heading. Use this order: A. Introduction, B. Definition of a Software Engineering Model, C. Overview of SDLC Models, D. Selected Model, E. Case Study, F. Application of the Model, H. Advantages, G. Justification, I. Structural Diagram Explanation, J. Disadvantages, K. Conclusion, L. References.

- **A. Introduction:** Explain the concept of software development models and their importance in Software Engineering.
- **B. Definition of a Software Engineering Model:** Define what a model means in the context of Software Engineering and identify what a model represents.
- **C. Overview of SDLC Models:** Briefly introduce all seven models covered in this repository: Waterfall, V-Model, Spiral, Prototype, Agile, Incremental and DevOps.
- **D. Selected Model:** Give an accurate definition and a detailed explanation of the assigned model, including its characteristic activities.
- **E. Case Study:** Present the predefined scenario with its requirements, objectives, stakeholders and expected outcomes.
- **F. Application of the Model:** Explain exactly how the selected model would be applied to this scenario, including phases and workflow.
- **H. Advantages:** Discuss practical advantages in relation to the case study rather than generic textbook benefits.
- **G. Justification:** Explain why the selected model is suitable for this specific scenario, not merely in general.
- **I. Structural Diagram Explanation:** Explain the architecture, phases, activities, transitions and relationships shown in the model's structural diagram.
- **J. Disadvantages:** Discuss genuine limitations and explain how each might affect the proposed project.
- **K. Conclusion:** Provide a technically sound academic conclusion that synthesises the analysis.
- **L. References:** Include credible, verifiable academic and technical references with in-text citations.

Immediately after the structural diagram explanation, include these two clearly labelled placeholders:

[INSERT YOUR DRAW.IO STRUCTURAL DIAGRAM SCREENSHOT HERE]

[INSERT YOUR DRAW.IO LIVE DIAGRAM LINK HERE]

The seven models to introduce in the SDLC overview are: Waterfall Model, V-Model (Verification and Validation Model), Spiral Model, Prototype Model, Agile Model, Incremental Model and DevOps Model.

### Document Two - Academic explanation and learning guide

Suggested file name: `SEN201_Waterfall_Explanation_Guide.docx`

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

Frame the guide as a learning companion that explains the reasoning behind each section rather than restating the assignment.

The guide must complement the main assignment, not repeat it word for word. Use different phrasing, add rationale and context, and focus on helping the student understand and defend the work.

## Stage 9 - Compulsory draw.io structural diagram

**Required diagram:** Waterfall Phase Cascade Diagram

draw.io is a free, browser-based diagramming tool available at https://app.diagrams.net/ . It is also known as diagrams.net and can be used online or installed as a desktop application. It is appropriate for Software Engineering diagrams because it provides a wide range of standard shapes, connectors and labelled arrows, supports precise layout, allows diagrams to be saved or exported in common formats and produces a shareable live link. These features make it well suited to representing phase structures, workflows and relationships in an SDLC model.

The structural diagram you must describe to the student is designed to show a linear sequence of phases where each phase is completed, reviewed and signed off before the next begins, with formal documentation flowing forward and controlled feedback arrows returning to an earlier phase only through a change-approval step.

Explain each of the following in the main assignment and expand on them in the explanation guide:

- Important shapes: Rounded rectangles for the six phases; a narrower rectangle for the phase sign-off gate; small documents for phase deliverables; a diamond for the change-approval decision.
- Required labels: Requirements Analysis and Specification, System Design, Implementation, Integration and Testing, Deployment, Maintenance; Review/Sign-off; Approved Change Request.
- Arrows and connections: Solid downward arrows between consecutive phases; labelled side arrows from each phase to its deliverable document; a dashed arrow from the sign-off gate back to a previous phase routed through the change-approval diamond.
- How to read the diagram: Read from top to bottom. Each phase produces a reviewed artefact; the downward arrow means the next phase starts only after sign-off. The dashed return path shows that backward movement is exceptional and controlled, not routine iteration.

Give the student clear step-by-step drawing guidance:

1. Place six rounded rectangles vertically and label them with the phase names above.
2. Between each pair insert a small horizontal bar labelled Review and Sign-off.
3. Draw solid downward arrows through each sign-off bar to the next phase.
4. Attach a document shape to the right of every phase with that phase's main deliverable name.
5. Add a decision diamond at the lower right labelled Change Approved?
6. Route a dashed arrow from a later phase to the diamond and from the diamond back to the affected earlier phase, labelling it Approved Change Only.

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

**Final reminder:** The diagram remains the student's own work. You may instruct and describe, but you must not pretend to have drawn it.

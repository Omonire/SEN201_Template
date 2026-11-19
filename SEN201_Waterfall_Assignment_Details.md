# SEN 201 Assignment — Waterfall Model

A concise record of the SEN 201 Software Engineering assignment prepared for the
Waterfall Model case study. This file summarises the brief, the selected model and
the required document structure; it is not a substitute for the submitted papers.

## 1. Assignment details

| Field | Value |
|---|---|
| Course code | SEN 201 |
| Course title | Software Engineering |
| Institution | University of Benin (UNIBEN) |
| Academic level | 200L |
| Selected SDLC model | Waterfall Model |
| Case study | Civil Service Payroll Replacement |
| Main document | `SEN201_Asher_Waterfall_Assignment.docx` / `.pdf` |
| Companion document | `SEN201_Asher_Waterfall_Explanation_Guide.docx` / `.pdf` |
| Diagram | Waterfall Phase Cascade Diagram (draw.io) |

## 2. Student details

| Field | Value |
|---|---|
| Full name | Omonire O. Great |
| Matriculation number | COS2503924 |
| Department | Software Engineering (SEN) |
| Faculty | Faculty of Computing |
| Academic level | 200L |
| Institution | University of Benin (UNIBEN) |

## 3. Definition of a Software Engineering Model

A software engineering model is an abstract representation of a real-world process,
system or artefact. It simplifies reality so that important features can be studied
and communicated. A software process model represents the activities, roles,
artefacts and sequencing of a development effort from a particular perspective.

## 4. Overview of SDLC Models

| Model | Focus |
|---|---|
| Waterfall | Stable, sequential, sign-off driven phases |
| V-Model | Development activities paired with corresponding testing activities |
| Spiral | Risk analysis repeated in every cycle |
| Prototype | Requirements discovered through working examples and feedback |
| Agile | Adaptation and frequent delivery of working software |
| Incremental | Functional slices added in sequence |
| Iterative | Repeated refinement of one capability |

These models are not mutually exclusive; large systems often combine elements of
several. The choice depends on the stability of requirements, the cost of error and
the need for stakeholder feedback.

## 5. Selected Model: Waterfall

The Waterfall Model is a linear sequential process in which development flows through
distinct phases, each completed and signed off before the next begins. It is commonly
traced to Royce (1970). In its teaching form the phases are:

1. Requirements analysis and specification
2. System and software design
3. Implementation and unit testing
4. Integration and system testing
5. Deployment
6. Operation and maintenance

Its discipline gives managers visible milestones and strong documentation, but makes
changes late in the project difficult and expensive (Sommerville, 2006).

## 6. Case Study

The Civil Service Payroll Office pays 25,000 salaried employees and requires a
replacement payroll engine. Salary scales, statutory deductions, tax rules and payment
timetables are fixed by civil service regulations and a national tax schedule for the
coming financial year.

- **Requirements:** maintain salary scale and grade records; calculate deductions from
  the published tax schedule; process monthly runs with approval checkpoints; generate
  payslips and bank payment files; produce reconciliation and statutory remittance reports.
- **Objectives:** accurate payment on the fixed pay date; exact application of tax and
  deduction rules; reconciliation records for audit.
- **Stakeholders:** payroll office director, payroll officers, finance ministry, tax
  authority, employees, internal auditors.
- **Expected outcomes:** error-free calculations, on-time payment and remittance, clean
  audit reconciliation.

## 7. Application of the Model

The model is applied as a sequence of gated phases:

1. **Requirements:** the payroll office, finance ministry and tax authority agree a
   single specification of the rules.
2. **Design:** the team defines the employee/grade/salary data model, calculation
   components, bank file interfaces and report formats.
3. **Implementation:** calculation, payslip, payment-file and reporting components are
   built and unit-tested against the agreed rules.
4. **Integration and system testing:** end-to-end monthly runs are checked against known
   salary cases before the parallel run.
5. **Deployment:** a controlled go-live in the pay calendar with a parallel run.
6. **Operation and maintenance:** defect fixes and rule updates handled under change control.

## 8. Justification

Waterfall fits because the requirements are genuinely stable, the cost of error is high,
the audit trail demands formal documentation, and the fixed financial-year deadline
makes a predictable plan valuable. A sequential process with formal verification gates
reduces the risk of an incorrect deduction or a missed pay date.

## 9. Advantages (specific to the payroll case)

- **Predictable planning** around statutory pay dates.
- **Strong audit evidence** through signed artefacts at every phase.
- **Clear stakeholder control** via sign-off at the specification and acceptance gates.
- **Reduced rework** because the rules are fixed for the financial year.
- **Coordination** of specialist staff and easier onboarding through documentation.

## 10. Structural Diagram

The diagram is a **Waterfall Phase Cascade Diagram**: six stacked phase boxes with
review and sign-off gates, downward arrows showing sequence, deliverable documents to
the right, and a controlled change-approval diamond on the left. It is drawn manually
in [draw.io](https://app.diagrams.net/) and the screenshot is inserted in the main
assignment. The AI does not claim to have created the diagram.

## 11. Disadvantages

- **Late defect discovery** — a rule error may only appear during the parallel pay run.
- **High cost of change** — a revised tax schedule forces several artefacts to be updated.
- **No early working software** — usability issues may emerge late.
- **Big-bang deployment risk** — mitigated by a parallel run and rollback plan.
- **Documentation overhead** — partly justified by the audit requirement.

## 12. Conclusion

The Waterfall Model remains appropriate where requirements are stable, regulation fixes
the rules and mistakes carry serious consequences. In this payroll case its structure
is defensible provided that late defect discovery, expensive change and concentrated
deployment risk are actively managed.

## 13. Required document structure

The main assignment contains: title page, Introduction, Definition of a Software
Engineering Model, Overview of SDLC Models, Selected Model, Case Study, Application,
Justification, Advantages, Structural Diagram Explanation, Disadvantages, Conclusion
and References (APA 7th edition).

The explanation guide complements it with section meanings, scenario rationale, model
application, diagram interpretation, draw.io steps, terminology, likely lecturer
questions and suggested answers.

## 14. Reference set used

- IBM. (2019). *The Waterfall methodology: Why you should use it.*
- ISO/IEC/IEEE. (2017). *ISO/IEC/IEEE 12207:2017 Systems and software engineering — Software life cycle processes.*
- OpenStax. (2024). *9.2 Software engineering process.*
- Royce, W. W. (1970). *Managing the development of large software systems.*
- Royce, W. W. (1987). *Managing the development of large software systems: Concepts and techniques.*
- Ruparelia, N. B. (2010). Software development lifecycle models. *ACM SIGSOFT Software Engineering Notes, 35*(3), 8–13.
- Sommerville, I. (2006). *Software engineering* (8th ed.) — Chapter 4 slides.

# MTEC 3501 - Week 8 Lesson Plan
**Class Theme:** Timeline Logic, Dependencies, and Issue Template Governance  
**Week:** 8  
**Duration:** 2.5 hours (150 minutes)  
**Location:** In-person (Face-to-Face)

---

## Learning Goals
- Translate project intent into an executable timeline using Start Date and Target Date.
- Distinguish issue-level work from milestone-level system states.
- Build dependency chains that reflect real sequencing constraints.
- Use a limited, standardized issue-template set to improve issue quality and grading consistency.

---

## Class Schedule and Activities

### 1. Opening Review and Framing (15 mins)
- Recap from Week 7: issue quality, transformation logic, and traceability.
- Introduce Week 8 objective: shift from issue lists to timeline-based system execution.
- Show one weak and one strong roadmap example.

### 2. Mini-Lecture: Sequencing as System Design (20 mins)
- Explain why timeline quality is not calendar filling.
- Define three constraints students must surface:
  - Technical dependencies
  - Integration bottlenecks
  - Validation checkpoints
- Connect timeline logic to risk management.

### 3. Guided Build: Project Roadmap Configuration (25 mins)
Students configure their project boards live:
1. Add Start Date and Target Date fields.
2. Map fields to Roadmap view.
3. Turn Dependencies on.
4. Add dates to active issues.

Instructor checks for:
- Dates spread across semester
- No end-loaded clusters
- At least one visible dependency chain

### 4. Milestone Design Workshop (30 mins)
Students create or refine required milestone issues:
- [MILESTONE] LVP Defined
- [MILESTONE] Prototype v0
- [MILESTONE] Functional System
- [MILESTONE] Pre-Final Integration
- [MILESTONE] Final Presentation

Each milestone must include:
- System State: at least 3 concrete conditions
- Validation: at least 3 testable checks

Instructor prompts:
- "What can be demonstrated at this milestone?"
- "What evidence proves completion?"

### 5. Issue Template Governance Lab (35 mins)
Goal: keep a small number of templates and improve consistency.

Repository policy for this course repo:
1. Use only curated templates in .github/ISSUE_TEMPLATE.
2. Disable blank issues.
3. Route general questions to Discussions.

In-class student task:
- Open "New issue" and verify only approved templates are shown.
- Create one issue using Project Task template.
- Link it to a milestone issue.
- Add at least one dependency reference.

Quick diagnosis if students see too many templates:
- Confirm repository templates exist in .github/ISSUE_TEMPLATE.
- Confirm config.yml exists with blank_issues_enabled: false.
- Confirm template files are valid YAML and load without errors.

### 6. Submission Prep and Exit Ticket (25 mins)
Students draft their Assignment 08 submission issue including:
- Repo link
- Project roadmap link
- Evidence checklist
- Reflection paragraph (150-250 words)

Exit ticket (posted in class chat):
- First critical issue in your system
- Most important dependency pair
- One timeline risk and mitigation plan

---

## Assessment Focus
- Timeline realism and sequencing coherence
- Dependency quality
- Milestone specificity and verifiability
- Proper use of repository issue templates

---

## Materials
- Assignment 08 brief
- Week 7 issue template reference
- Projector demo of GitHub Roadmap and issue creation flow

---

## Instructor Notes
- Keep students focused on "system emergence" rather than task volume.
- If a student cannot explain milestone validation, pause and refine issue language before proceeding.
- Enforce template usage for all new issues created during class.

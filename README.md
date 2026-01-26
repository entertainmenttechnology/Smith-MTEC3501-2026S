# MTEC 3501 — Culmination Project Development (Spring 2026)

*New York City College of Technology (City Tech) • Department of Entertainment Technology*

---

## Semester: Spring 2026

Term: Jan–May 2026

**Instructor:** [Name] • **Contact:** [email@citytech.edu] (replace with actual details)

Short overview: MTEC 3501 guides students through the research, proposal, and planning stages toward a culminating project and proof-of-concept prototype.

---

## Quick Start (students)

Preferred workflow (central repo branches):

Note: this requires students to have write access to the central class repo. If you will grant students write access, use this workflow so all student work lives in a single repository and each student works on their own branch.

1. Clone the central repository (replace `org-or-instructor` if different):

```bash
git clone git@github.com:org-or-instructor/Smith-MTEC3501-2026S.git
cd Smith-MTEC3501-2026S
```

2. Create a branch on `origin` and push:

```bash
git checkout -b student-LastName-FirstName
git push -u origin student-LastName-FirstName
```

3. Work in `projects/YourName/`, commit regularly, push to your branch, and open a Pull Request on GitHub from `student-LastName-FirstName` to `main` (or the designated integration branch).

Branch naming policy (recommended):

- `student-LastName-FirstName` — personal work
- `team-ProjectName` — for group projects
- `fix/short-description` or `feat/short-description` — minor task branches

If you DO NOT have write access (or prefer isolation), use the fork workflow:

1. Fork this repository to your GitHub account (click "Fork" on GitHub).
2. Clone your fork locally (replace `your-username`):

```bash
git clone git@github.com:your-username/Smith-MTEC3501-2026S.git
cd Smith-MTEC3501-2026S
```

3. Create and push your branch to your fork:

```bash
git checkout -b student-LastName-FirstName
git push -u origin student-LastName-FirstName
```

4. Open a Pull Request from your fork/branch to the central repo.

Keeping your branch/repo up to date (central-branch workflow):

```bash
# add upstream once (central repo)
git remote add upstream git@github.com:org-or-instructor/Smith-MTEC3501-2026S.git
git fetch upstream
git checkout main
git merge upstream/main
git push origin main
# then rebase or merge main into your branch before opening PR
git checkout student-LastName-FirstName
git rebase main
```

Short PR checklist (add this to PR description):

- Title: concise summary of changes
- Link to Week/Assignment issue
- Files changed: `projects/YourName/` path
- Description: what you added/changed and why
- AI use: disclose any AI assistance (prompts, tools, edits)
- Tests/Notes: how to preview or run any demos

Use Issues + Projects to track milestones and deliverables; submit work by opening a PR from your branch (or by attaching deliverables to the assignment issue) unless otherwise directed.

---

## Getting Started (accounts & tools)

Before you begin coursework, set up these accounts and tools:

- Create a GitHub account: https://github.com/join (use your real name or institutional account)
- Create a Zotero account: https://www.zotero.org/user/register
- Install GitHub Desktop: https://desktop.github.com/ (available for macOS, Windows)
- Install the Zotero Connector for your browser: https://www.zotero.org/download/

Using GitHub Desktop (recommended for beginners):

1. Sign into GitHub Desktop with your GitHub account.
2. Fork this repository on GitHub (click "Fork").
3. In GitHub Desktop choose "File → Clone repository", select your fork, and clone it locally.
4. Create a new branch for your work: Branch → New branch → name it `student-LastName-FirstName`.
5. Make changes locally (add files, update your `projects/YourName/` folder), Commit to the branch with a clear message, and Push to origin.
6. Open a Pull Request from your branch to the central repo via GitHub.com (GitHub Desktop shows a button to "Create Pull Request").

If you prefer the command line, the equivalent steps are:

```bash
# fork on GitHub, then clone your fork (replace your-username)
git clone git@github.com:your-username/Smith-MTEC3501-2026S.git
cd Smith-MTEC3501-2026S
git checkout -b student-LastName-FirstName
# make changes, then:
git add .
git commit -m "Add project folder and initial deliverables"
git push -u origin student-LastName-FirstName
```

Zotero setup notes:

- Install the Zotero desktop app (optional but useful for full library features).
- Install the Zotero Connector in your browser to save references directly from webpages.
- Create a course collection for `MTEC 3501` and share export instructions if you are collaborating on literature reviews.

If you need help with any of these steps, contact the instructor or ask for a short walkthrough session.

---

## Repository Map (key folders)

- `assignments/` — weekly assignments and deliverables index (student-facing)
- `lesson plans/` — faculty-facing lesson materials
- `documents-Class/` — syllabus, support materials, and course docs
- `projects/` or `Projects/` — student project folders (one per student)
- `assets/` — images and media used in examples and templates

Useful links:

- Assignments index: [documents-Class/assignments/README.md](documents-Class/assignments/README.md)
- Syllabus: [documents-Class/Syllabus.pdf](documents-Class/Syllabus.pdf)

---

## Weekly Update

This section will be updated weekly with the active assignment and deliverables.

**This Week (Week 1): Course Introduction & Onboarding**

- Course overview and introductions
- First writing: "What is your idea?" (1–2 paragraph first draft)
- Goals: design a culmination project; learn professional tools & practices; collaborate effectively; communicate across modalities; develop situational awareness
- Class philosophy: Think boldly — push envelopes and contextualize ideas within larger environments
- Iterative R&D: discuss engineering development examples (slow/awkward/expensive → fast/elegant/inexpensive/robust)
- Six Stages of Project Development (SRDPMA) — model is iterative, fractal, and a guideline rather than a prescription
- Introduction to communication tools: combinative reality, medium vs message, systems vs symbols, engineering vs design, balanced blended space, collaborative AI, mediation pathways, holistic integration
- Speculative ideation: Second writing prompt — the great "What if?"; inspirations and speculative first concept
- Aspirational climax: Dream big (unlimited budget/time) — what you'd hope to show by the end of the second semester (functioning prototype)

Key ideation questions:

- What do I think I need?
- What do I think I know?
- What do I think I don’t know?

Setup tasks (complete this week):

1. Sign up for a GitHub account (https://github.com/join)
2. Install GitHub Desktop (optional but recommended) and/or Visual Studio Code
3. Sign up for Zotero and install the Zotero Connector for your browser
4. Ensure you have access to the class repository (faculty will confirm next week)
5. Identify your familiarity with AI tools and whether you plan to involve AI in your project (fill out the AI use form linked in the Week 1 assignment)

- See onboarding doc: [Week 1 Onboarding](documents-Class/assignments/Week1_Onboarding.md)

Deliverable due this week:

- Submit your first writing (1–2 paragraphs describing your idea) to your `projects/YourName/` folder and link it in the Week 1 assignment issue. See assignments index: [documents-Class/assignments/README.md](documents-Class/assignments/README.md)

- For onboarding details and the GitHub username task, see: [Week 1 Onboarding](documents-Class/assignments/Week1_Onboarding.md)

---

## Course Overview

MTEC 3501 prepares you for your culmination project in the BTech program. You will progress through Research → Design → Production Planning → Assessment, with emphasis on proposal development, precedent research, milestone planning, and juried presentations.

---

## Project Management

We use GitHub Projects (Kanban/Roadmap), Issues, and Milestones for task tracking.

- Individual Projects: maintain a personal board in your `Projects/YourName` folder.
- Group Projects: use the Class Kanban Board for shared tasks.

Peer feedback is tracked via issue comments and the `Proposal_Feedback.yml` template.

---

## Assignments & Deliverables

Assignments are released weekly and tied to the syllabus.

Key deliverables include:

- Proposal Package (issue + markdown)
- Precedent Research (2–3 pages + Zotero entry)
- Milestone & Timeline (GitHub Projects/Roadmap)
- Juried Presentations (checkpoints and final)
- Proof-of-Concept Prototype (early demo)
- Post-Presentation Analysis (reflection + adjustments)

---

## AI Collaboration Reporting

All major deliverables require a short AI-use report: prompts, tools, and a brief reflection on AI's influence.

---

## Resources

- [Assignments Index](documents-Class/assignments/README.md)
- [Lesson Plans (faculty only)](documents-Class/lesson-plans/)
- [Support Materials](documents-Class/support/)

---

## Changelog

- **Spring 2026** — Updated header for Spring 2026; added `Quick Start`, `Repository Map`, instructor/contact placeholder, and `Changelog` entry. Refreshed links and clarified student workflow.

---

If you'd like, I can fill in the instructor contact, exact term dates, or adjust wording to match department templates.

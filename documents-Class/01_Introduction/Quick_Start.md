# Quick Start — Onboarding & Git Workflow

This document lists the core applications used in MTEC 3501 (Spring 2026) and the high-level steps to get each one ready so you can begin work quickly. Use the detailed workflow sections below for branch/PR policy, syncing, and a short PR checklist.

Applications used in this course

- GitHub — repository hosting, Issues, Pull Requests, Projects (required)
- Git (command-line) or GitHub Desktop — clone, branch, commit, push (one is required; Desktop recommended for beginners)
- Visual Studio Code — primary code and text editor (recommended)
- Zotero + Zotero Connector — citation management and research collection
- Browser (Chrome, Firefox, Safari) — for GitHub, Zotero Connector, and web tools
- Optional/Project tools: Figma, Adobe XD, Blender, Unity, Unreal Engine, Python/Node.js runtimes — installed per project needs

High-level setup steps

1. Create accounts: GitHub and Zotero. Confirm your GitHub username meets the course spec (Week 1 onboarding doc).
2. Install tools: GitHub Desktop (or Git), Visual Studio Code, Zotero, and the Zotero browser connector.
3. Configure Git: set your name and email (`git config --global user.name "Your Name"`; `git config --global user.email you@example.com`) and create SSH keys if you prefer SSH cloning.
4. Sign into GitHub Desktop (or authenticate Git with your credentials/SSH key).
5. Confirm access: instructors will grant write access if using the central-branch workflow; otherwise fork the repo and clone your fork.
6. Create your branch (`student-LastName-FirstName`) and create your `projects/YourName/` folder for deliverables.
7. Install optional project tools as needed for your specific project; we'll note required tools in assignment prompts.

If you prefer a step-by-step beginner guide (GitHub Desktop flows, Zotero connector install, and CLI equivalents), see the Getting Started section in the course README or continue in this document for the full Git workflow.

## Accounts & Tools

Before you begin, create or confirm the following accounts and install the recommended tools. These are the core applications used in this course.

- GitHub account: https://github.com/join (used for repository access, branches, and PRs)
- Git (command-line) or GitHub Desktop: https://desktop.github.com/ (Desktop recommended for beginners)
- Visual Studio Code (editor): https://code.visualstudio.com/
- Zotero account and Zotero Connector: https://www.zotero.org/download/ (Zotero desktop app is optional but recommended for full features)
- Web browser (Chrome, Firefox, or Safari) with cookie/logins enabled for GitHub and Zotero
- GitHub Projects / Issues (built into GitHub) — for task tracking

Optional / course-dependent tools (examples):

- Figma or Adobe XD (UI/UX and prototyping)
- Blender, Unity, or Unreal Engine (3D/interactive prototypes)
- Python / Node.js runtimes for lightweight prototyping (install as needed per project)

Notes:

- If you are new to Git, GitHub Desktop simplifies cloning, branching, committing, and PR creation. The CLI provides finer control and is recommended for students comfortable with the terminal.
- Zotero lets you collect citations and export bibliographies for precedent research.
- We will provide project-specific tooling notes in assignment prompts when needed.


Preferred workflow (central repo branches)

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

Fork workflow (if you do not have write access)

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

If you prefer GitHub Desktop for onboarding, follow the steps in the course `README.md` under "Getting Started".

---


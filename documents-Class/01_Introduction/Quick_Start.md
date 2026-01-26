# Quick Start — Onboarding & Git Workflow

This document contains the recommended onboarding and Git workflow for MTEC 3501 (Spring 2026). It covers the preferred central-repo branch workflow, a fork fallback, branch naming policy, syncing, and a short PR checklist. For beginner-friendly steps (GitHub Desktop), see the `Getting Started` section in the main course README.

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

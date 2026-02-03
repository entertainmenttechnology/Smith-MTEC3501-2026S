# Teacher's Guide: Setting Up GitHub for Brainstorming Activities

This guide provides step-by-step instructions on how to set up all necessary GitHub components to prepare for the brainstorming class session.

---

## **1. Create a GitHub Repository for the Class**
### **Steps:**
1. Go to [GitHub](https://github.com) and log in.
2. Click the **+** sign (top right) → Select **New repository**.
3. Name the repository (e.g., `culmination-brainstorming`).
4. Choose **Public** or **Private**, depending on access needs.
5. Select **Add a README** to initialize the repository.
6. Click **Create repository**.

✅ **Tip:** Use a meaningful repo description so students understand its purpose.

---

## **2. Configure Repository Settings**
### **A. Add Students as Collaborators**
1. Go to **Settings** → **Manage Access**.
2. Click **Invite Collaborators** → Enter GitHub usernames.
3. Assign **Write** permissions so they can create Issues, Discussions, and PRs.

### **B. Set Up Branch Protection (Optional)**
1. Navigate to **Settings** → **Branches**.
2. Under **Branch protection rules**, select `main`.
3. Enable:
   - ✅ Require pull request reviews before merging.
   - ✅ Require status checks before merging (optional).
   - ✅ Restrict force-pushes to prevent accidental overwrites.
4. Save changes.

✅ **Tip:** This ensures controlled collaboration while allowing brainstorming flexibility.

---

## **3. Prepare GitHub Issues for Brainstorming**
### **A. Create Labels for Organization**
1. Go to **Issues** → **Labels** → **New Label**.
2. Add labels for different brainstorming categories:
   - `🧠 Brainstorming`
   - `🔄 Idea Expansion`
   - `⚠️ Potential Challenges`
   - `💡 Future-Proofing`
   - `🚀 Ready for Refinement`

✅ **Tip:** Labels help students filter and track discussions.

### **B. Create an Issue Template for Idea Submission**
1. Navigate to `.github/ISSUE_TEMPLATE/` (or create it if not existing).
2. Create a file: `brainstorming_issue_template.md`.
3. Paste the following:

```markdown
## Brainstorming Starter Idea

### Idea Overview
Describe your project idea in 2-3 sentences.

### Inspiration
What inspired this idea? How did it first come to you?

### Initial Thoughts
- List key elements related to this idea.
- Identify any challenges or questions you have about it.

### Labels
- Apply the `🧠 Brainstorming` label.
```

4. Save and commit this template.

✅ **Tip:** Students will use this template to create Issues and submit their ideas.

---

## **4. Set Up GitHub Discussions for Open Collaboration**
1. Go to **Settings** → **Features**.
2. Enable **Discussions**.
3. Create discussion categories:
   - `🔍 Idea Refinement`
   - `🤝 Collaboration Requests`
   - `🚀 Future Iterations`

✅ **Tip:** Discussions provide a space for informal idea sharing and feedback.

---

## **5. Set Up GitHub Wiki for Documentation**
1. Go to the repository homepage.
2. Click **Wiki** → **Enable wiki**.
3. Add an **index page** linking to different brainstorming methods.

✅ **Tip:** Use the Wiki to document brainstorming best practices and insights.

---

## **6. Prepare GitHub Pull Request Templates for "Kill Your Idea" Test**
1. Navigate to `.github/PULL_REQUEST_TEMPLATE/`.
2. Create a file: `kill_your_idea_pr.md`.
3. Paste the following template:

```markdown
# Kill My Idea Test

## My Project Idea:
(Briefly describe your idea.)

## Why It Won’t Work
- (List 3-5 reasons this idea could fail.)
- (Consider technical, practical, and conceptual barriers.)

## How It Could Be Fixed
- (Suggest possible solutions or pivots to address these issues.)

## Feedback Needed
- (Ask classmates to propose additional challenges or solutions.)
```

4. Save and commit the file.

✅ **Tip:** This template ensures students think critically about idea feasibility.

---

## **7. Integrating Miro for Visual Brainstorming**
### **A. Enable GitHub & Miro Integration**
1. Open **Miro** and create a board for the class.
2. Install **GitHub Cards** in Miro:
   - Click **Apps** → Search for **GitHub Cards**.
   - Sign in to **GitHub**.
   - Select the class repository.
3. Students can drag **GitHub Issues** onto Miro for visualization.

### **B. Embed Miro Board in GitHub**
1. In Miro, click **Share** → **Copy Link**.
2. Paste the link in:
   - **GitHub Discussions** → Create a post titled `Miro Brainstorming Board`.
   - **GitHub Wiki** → Document mind maps under `Brainstorming Results`.

✅ **Tip:** Miro provides a visual way to structure brainstorming outcomes.

---

## **8. Final Checklist Before the Class**
✅ Repository created and students added as collaborators.  
✅ Issues, Discussions, and Wiki are set up.  
✅ GitHub brainstorming templates are available.  
✅ GitHub + Miro integration enabled.  
✅ Lesson plan and teacher resources stored in the Wiki.

Would you like additional GitHub automations or setup assistance? 🚀

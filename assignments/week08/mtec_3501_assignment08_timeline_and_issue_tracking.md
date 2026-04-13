# MTEC 3501 — Assignment 8
## Timeline Setup, Issue Tracking, and Milestones

---

## Purpose

This assignment introduces how to track your project over time using GitHub Projects.

You will:
- Add time structure to your issues
- Visualize work across the semester
- Begin organizing execution toward milestones

This is the first step in moving from **a set of issues** to **a coordinated development system**.

---

## Part 1 — Setup: Timeline in GitHub Projects

### Step 1 — Add Date Fields

1. Open your project
2. Switch to a **Table view**
3. Scroll to the far right and click **+** (add field)

Create the following fields:

- **Start Date** (Type: Date)
- **Target Date** (Type: Date)

---

### Step 2 — Connect Fields to the Roadmap

1. Switch to **Roadmap view**
2. Click the **calendar icon (Date fields)** in the top-right

Set:

- Start date → Start Date
- Target date → Target Date

Your issues will now appear as timeline bars.

---

### Step 3 — Add Dates to Issues

If your roadmap is empty, your issues do not yet have dates.

You may:

- Click an issue and manually enter dates

OR

- Drag issues directly onto the roadmap to assign dates

---

### Step 4 — Enable Dependencies

1. Open **View settings** (gear icon)
2. Turn **Dependencies ON**

This will show relationships between issues.

---

## Part 2 — Milestone Creation and Weekly Development

### Creating Milestones as Issues

You will create milestones as **issues within your project board** so they can be visualized on your roadmap.

#### Step 1 — Create Milestone Issues from Project Board

1. Open your Project Board
2. Click **+ Add item**
3. Select **Add draft issue**
4. Title using:

`[MILESTONE] <Milestone Name>`

5. Click the item and select **Convert to issue**
6. Choose your repository

---

#### Step 2 — Define the Milestone

Each milestone issue must include:

**System State** (what must exist):
- 
- 
- 

**Validation** (how you know it is complete):
- 
- 
- 

---

#### Step 3 — Add to Timeline

- Assign **Start Date** and **Target Date**
- Ensure milestone appears on roadmap

---

#### Step 4 — Label Milestones

- Add label: `milestone`

---

#### Step 5 — Attach Issues to Milestones

- Link relevant issues in the milestone description
- OR use a checklist of issue references

---

### Required Milestones (All Projects)

All projects must include the following milestones:

1. **[MILESTONE] LVP Defined**

This milestone must be fully specified using the following structure inside the milestone issue:

```markdown
## Experience
(Describe what the user/viewer experiences)

## System Behavior
(Input → process → output)

## Scope and Limitations
(What is included and excluded in the LVP)

## Components
(List major subsystems and link related issues)

## LVP vs Final Version
(What is not yet included and what will be expanded later)
```

This milestone is complete when:
- The system can be clearly explained from both user and technical perspectives
- The scope of the LVP is bounded and realistic
- All major components are identified and connected to issues
- The difference between LVP and final system is स्पष्ट (clear)

---

2. **[MILESTONE] Prototype v0**
   - Initial working system (basic input → output)

3. **[MILESTONE] Functional System**
   - Core functionality implemented and stable

4. **[MILESTONE] Pre-Final Integration**
   - System integrated, tested, and mostly complete
   - Presentation and documentation in progress

5. **[MILESTONE] Final Presentation**
   - Working PoC
   - Completed presentation (slides + narrative)
   - Complete repository and documentation

---

### Weekly Development Work

Using your existing issues:

### 1. Assign Time to Issues

- Add Start and Target dates to all active issues
- Ensure dates are realistic and distributed across time

---

### 2. Define Dependencies

- Identify which issues must happen before others
- Add dependency relationships between issues

---

### 3. Connect Issues to Milestones

- Determine which issues contribute to each milestone
- Ensure all milestones are supported by relevant issues

---

### 4. Review Timeline

Examine your roadmap and evaluate:

- Are issues aligned with milestones?
- Are dependencies reflected in sequencing?
- Does the timeline represent a coherent development process?

---

### 5. Refine System

Adjust:

- Dates
- Issue scope
- Dependencies
- Milestone definitions

Until your timeline reflects a clear system progression

---

Using your existing issues:

### 1. Assign Time to Issues

- Add Start and Target dates to all active issues
- Ensure dates are realistic and distributed across time

---

### 2. Define Dependencies

- Identify which issues must happen before others
- Add dependency relationships between issues

---

### 3. Review Timeline

Examine your roadmap and evaluate:

- Are issues overlapping appropriately?
- Are dependencies reflected in sequencing?
- Does the timeline make sense as a development process?

---

### 4. Adjust as Needed

Refine:

- Dates
- Issue scope
- Dependencies

Until your timeline reflects a coherent development plan

---

## Deliverables

Submit the following:

### 1. Project Link
- GitHub repository
- GitHub project board (Roadmap view visible)

---

### 2. Short Reflection (150–250 words)

Respond to the following:

- What is the first issue that must be completed for your system to function?
- What dependencies most strongly shape your timeline?
- What would break if your earliest issue is delayed?

---

## Evaluation Criteria

- Correct setup of timeline fields and roadmap
- Meaningful assignment of dates
- Clear and logical dependencies
- Evidence of system-level thinking

---

## Key Principle

> A timeline is not a schedule of tasks.
>
> It is a representation of how your system comes into existence over time.

---

## Notes

- Dates should reflect realistic work periods
- Dependencies should reflect actual system requirements
- Avoid arbitrary or evenly spaced timelines

---

## Looking Ahead

This timeline will be used in the next phase to:

- Define milestones
- Evaluate system readiness
- Coordinate final project development


# MTEC 3501 - Assignment 08
## Timeline Setup, Issue Tracking, and Milestones

Due: End of Week 08  
Submission: GitHub issue in your course repository

## Learning Goal
By the end of this assignment, you will configure a GitHub Project roadmap with Start Date and Target Date fields, apply dates to active issues, establish dependency links, and define milestone issues that show a coherent, testable sequence from LVP to final presentation.

## What You Will Produce
1. A configured Roadmap view with Start Date and Target Date fields.
2. Dated issues with realistic sequencing.
3. Dependency links that reflect actual build order.
4. Five required milestone issues plus any project-specific milestones you need, each connected to supporting work.
5. A short written reflection on timeline risk and sequencing logic.

## Resource Readings  
1. [GitHub Issues Documentation](https://docs.github.com/en/issues)  

## Part 1 - Configure Timeline in GitHub Projects

### Step 1 - Add Date Fields
1. Open your project.
2. Switch to Table view.
3. Add these fields:
   - Start Date (Date)
   - Target Date (Date)

### Step 2 - Connect Date Fields to Roadmap
1. Switch to Roadmap view.
2. Open Date fields (calendar icon).
3. Set:
   - Start date -> Start Date
   - Target date -> Target Date

### Step 3 - Date Your Active Issues
Add Start Date and Target Date for all active issues. You can do this by editing issue fields or dragging issues on the roadmap.

### Step 4 - Enable Dependencies
1. Open View settings (gear icon).
2. Turn Dependencies on.

## Part 2 - Create and Define Milestones

### Milestone vs Issue (Lecture Alignment)
In lecture, we define these roles clearly:
1. Issue = a specific, actionable unit of work.
2. Milestone = a validated system state achieved by completing multiple related issues.

Use that distinction when deciding whether to create a normal issue or a milestone issue.

### Milestone Issue Format
Create milestones as issues in your repository using this title format:
[MILESTONE] Milestone Name

Add label: milestone

Each milestone issue must include both sections below:

System State (what must exist):
- At least 3 concrete conditions

Validation (how completion is verified):
- At least 3 testable completion checks

### Required Milestones (All Projects)
1. [MILESTONE] LVP Defined
2. [MILESTONE] Prototype v0
3. [MILESTONE] Functional System
4. [MILESTONE] Pre-Final Integration
5. [MILESTONE] Final Presentation

You may add additional milestone issues beyond these five if your project needs intermediate checkpoints.

### Additional Requirement for [MILESTONE] LVP Defined
Use this structure in the issue body:

```markdown
## Experience
(Describe what the user/viewer experiences)

## System Behavior
(Input -> process -> output)

## Scope and Limitations
(What is included and excluded in the LVP)

## Components
(List major subsystems and link related issues)

## LVP vs Final Version
(What is not included yet and what expands later)
```

Completion criteria for this milestone:
1. The system is clear from user and technical perspectives.
2. The LVP scope is bounded and realistic.
3. Major components are identified and linked to issues.
4. The difference between LVP and final system is explicit.

## Part 3 - Connect Work to Milestones
1. Assign Start Date and Target Date to each milestone issue.
2. Link supporting issues to each milestone (issue links or checklist references).
3. Add dependency relationships between issues where order matters.

Example dependency chain:
Issue A (sensor input working) -> Issue B (data mapping) -> Issue C (interactive output) -> [MILESTONE] Prototype v0

## Timeline Quality Check
Before submitting, verify:
1. Milestones are distributed across the remaining semester (not clustered at the end).
2. Dependencies reflect real sequencing constraints.
3. Earliest issues unlock later integration work.
4. Timeline shows coherent system progression.

## Deliverables (Required)
Submit one GitHub issue titled:
Assignment 08 Submission: Timeline and Issue Tracking

Include the following in the issue body:
1. Repository link.
2. Project board link (Roadmap view).
3. Evidence checklist:
   - Start Date and Target Date fields created
   - Dates assigned to active issues
   - Dependencies enabled and used
   - All 5 required milestones created and labeled
   - Additional project-specific milestones added where needed
   - Milestones connected to supporting issues
4. Reflection (150-250 words) answering:
   - What is the first issue that must be completed for your system to function?
   - Which dependencies most strongly shape your timeline?
   - What failure chain occurs if your first critical issue is delayed?

## Grading Rubric (100 points)
1. Roadmap and field setup correctness: 20
2. Date quality and timeline realism: 20
3. Dependency logic and sequencing: 20
4. Milestone quality and issue linkage: 25
5. Reflection depth and system-level reasoning: 15

## Key Principle
A timeline is not just a schedule of tasks. It is a representation of system emergence over time.

## Looking Ahead
This timeline will be used in subsequent assignments to evaluate system readiness, coordinate integration, and plan final presentation work.


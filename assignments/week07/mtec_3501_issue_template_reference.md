# MTEC 3501 — Issue Template Reference
## Defining Issues as Transformations

---

## Purpose

This document defines the required structure for all GitHub Issues in this course.

An Issue is not a task. It is a **transformation of the system** from one state to another.

Each Issue must clearly define:
- The current state (Source)
- The transformation (Vector)
- The resulting state (Destination)

---

## Required Components

### 1. Issue Title (GitHub Field)

- Must be written as **verb–object**
- Must describe a transformation

**Examples:**
- Design signal flow for audio system
- Implement sensor input mapping
- Create presentation narrative structure

---

### 2. Description (What + Why)

The description must explain:
- What is being done
- Why it matters to the system

This should connect to:
- Feedback
- Identified gaps
- System requirements

---

### 3. Task Type

Categorize the work using one of the following:

- Research
- Design
- Prototype
- Integration
- Testing
- Documentation
- Presentation

---

### 4. Priority

Indicate importance:

- High → blocks other work
- Medium → important but not blocking
- Low → optional or later-stage

---

### 5. Acceptance Criteria (Definition of Done)

This is the most important component.

Acceptance criteria define the **Destination** of the transformation.

They must be:
- Specific
- Testable
- Verifiable

**Examples:**
- Diagram includes all inputs, transformations, and outputs
- File is uploaded to repository
- System behavior is demonstrated and documented

Vague statements (e.g. "work on system") are not acceptable.

---

### 6. Dependencies

- Identify prerequisite work
- Reference other issues using # notation

**Example:**
- Depends on #12

This ensures correct sequencing and reveals blockers.

---

### 7. Component / Subsystem

Identify which part of the system the issue affects:

- Audio
- Visual
- Interaction
- AI / Logic
- Hardware
- Presentation
- Documentation

---

### 8. Source

Indicate where the issue originates from:

- Midterm feedback
- Peer critique
- Instructor feedback
- Self-assessment
- System requirement

This maintains traceability.

---

### 9. AI Collaboration (Optional)

If AI tools were used:
- Briefly describe how they were used
- Describe how results were evaluated or refined

---

## Summary Checklist

A valid issue must include:

- Actionable title
- Clear description (what + why)
- Task type
- Priority
- Strong acceptance criteria
- Dependencies (if applicable)
- Component
- Source

---

## Diagnostic Test

An issue is complete if:

> You can clearly describe what the system looks like after this issue is finished.

If you cannot, the issue is incomplete.

---

## Common Failure Modes

- Titles that are too vague (e.g. "Audio")
- Missing or weak acceptance criteria
- No connection to feedback or system need
- Treating issues as general tasks instead of transformations

---

## Final Note

Issues are the foundation of your project system.

If issues are unclear, the entire system—milestones, dependencies, and execution—will fail.


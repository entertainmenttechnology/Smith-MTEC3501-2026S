# MTEC 3501 — Assignment: From Feedback to Execution (GitHub System)

## Context

You are now transitioning from Research into Design, and from Design into Make / Proof of Concept. At this stage, your project must move beyond idea generation and analysis and begin to function as a structured system capable of producing results.

GitHub will serve as your execution environment. In this context, Issues represent units of work, the Project Board represents the current state of that work, and Milestones (which will be introduced next week) represent the temporal structure of the project. In addition, all work must be created using a required Issue Template, which ensures that each task is defined in a consistent and actionable way.

## Conceptual Model

Each Issue should be understood not simply as a “task,” but as a transformation. This aligns with familiar structures from natural language and from the BBS framework. In natural language, we think in terms of Subject–Verb–Object (SVO). In the BBS framework, this becomes Source–Vector–Destination (S/V/D). In the context of this assignment, the same structure applies.

The Source represents the current state, problem, or input condition. The Vector represents the transformation process—the work being performed. The Destination represents the result of that transformation, which must be explicitly defined. Your Issue Template encodes this structure: the Source field captures origin and justification, the Description, Type, and Component fields define the transformation, and the Acceptance Criteria define what the completed state must be.

A well-formed issue therefore makes this transformation explicit. A weak issue leaves one or more of these elements undefined.

## Assignment Objective

The purpose of this assignment is to construct a functioning execution system for your project. You will translate feedback into clearly defined transformations, instantiate those transformations as Issues using the template, and organize them within a Project Board that reflects the current state of your work.

## Part 1 — From Feedback to Action

Begin by reviewing all available feedback, including midterm evaluations, peer critique, instructor comments, and your own reflections. You will synthesize this material into a single Issue titled:

[FEEDBACK SYNTHESIS] Project Direction Update

Within that Issue, you should articulate confirmed strengths, critical issues or risks, required changes, open questions, and new opportunities. This synthesis is not an endpoint. It is a translation layer. Each actionable insight must be converted into a separate Issue. If feedback remains only as commentary, it has not yet entered your project system.

## Part 2 — Required Issue Template

All Issues must be created using the provided template (Project TASK). The template is not optional, and its purpose is to enforce clarity and consistency across all work.

Issues that lack meaningful Acceptance Criteria or a clear Description will be considered incomplete. Milestones will be introduced in the following session; for now, the focus is on defining high-quality units of work.

## Part 3 — Interpreting the Issue Template

### Issue Title (GitHub Field)

The Issue Title, entered in the standard GitHub field at the top, must be action-oriented and written as a verb–object pair. A title such as “Design signal flow for audio subsystem” clearly indicates a transformation, whereas a title such as “Audio” does not.

### Description (What + Why)

The Description field explains both what the task is and why it matters. For example, a description might explain that a signal flow diagram is being created to resolve ambiguity identified in feedback and to provide a consistent architectural reference for future work. This connects the task to the larger system.

### Task Type

The Task Type categorizes the work. Selecting “Design” indicates that the task is concerned with structure or planning, whereas “Prototype” indicates implementation or testing. This distinction becomes important when organizing and filtering work.

### Priority

Priority requires you to make decisions about importance. A task marked as high priority should be one that blocks or enables other work. Without prioritization, the project becomes flat and difficult to manage.

### Acceptance Criteria (Definition of Done)

The Acceptance Criteria define the Destination of the transformation. This is the most important field in the template. Completion must be expressed in specific, testable terms. For instance, a valid set of criteria might state that a signal flow diagram includes all inputs, transformations, and outputs, has been reviewed and revised, and has been exported and uploaded to the repository. Vague statements such as “work on system” are not acceptable because they do not define completion.

### Dependencies

Dependencies identify prerequisite work. By referencing other Issues (for example, #12 or #15), you establish sequencing and prevent work from occurring out of order.

### Milestone (Preview)

The Milestone field indicates where the work will eventually sit in the project timeline. Although formal milestone assignment will occur next week, you should begin to think about temporal placement now.

### Component / Subsystem

The Component or Subsystem field identifies which part of the overall system is affected. This might include the audio system, interface, hardware, narrative layer, or AI system. This field supports system-level thinking and decomposition.

### Source

The Source field explicitly connects the Issue back to its origin. For example, an Issue might originate from midterm feedback identifying unclear architecture. This maintains traceability from feedback through design into execution.

### AI Collaboration (Optional)

The AI Collaboration field is optional and should be used only when relevant. It provides a brief account of how AI contributed to the task and how that contribution was evaluated or refined.

## Part 4 — Project Board (State Representation)

Create a GitHub Project Board, or use the one already created in class. The board should include columns such as Backlog, Ready, In Progress, Blocked, Review, and Done. The board represents the current state of your system. It is not a timeline. Movement across the board reflects changes in state, not the passage of time.

## Part 5 — README Update

Update your repository README so that an external reviewer can understand your project quickly. This should include a brief description of the current project, a link to the Project Board, and a short explanation of how Issues are being used to manage work.

## Deliverables

You will submit your GitHub repository, your Project Board, a set of Issues created using the template, and an updated README.

## Evaluation Criteria

Evaluation will focus on how effectively you translate feedback into structured transformations, how clearly Issues are defined, how strong and testable your Acceptance Criteria are, and how coherently your Project Board represents the state of your work.

## Common Failure Modes

Common problems include vague issue titles, weak or missing acceptance criteria, failure to connect tasks to feedback, and treating the Project Board as a checklist rather than a representation of system state.

## Final Note

At this stage, your project must operate as a system. Each Issue defines a transformation from Source to Destination through a specific Vector. The Project Board reflects the current state of those transformations. Milestones, which will be introduced next, will provide the temporal structure that organizes them over the remainder of the semester.


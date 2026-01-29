# AI Activities & Tools — MTEC 3501 (S–R–D–M–P–A Cycle)

## AI-Specific Learning Outcomes for this plan
- Use AI for **structured extraction and synthesis** (gap tables, constraint maps) without losing fidelity to source material.
- Apply AI to **generate comparative options and decompositions** (issue breakdowns, alternative approaches) that are sequenced and testable.
- **Critique and verify** AI outputs, spotting hallucinations, missing constraints, and misaligned assumptions before adoption.
- **Document AI contributions transparently** in GitHub issues, commits, and reflections so human/AI roles are auditable.
- Leverage AI for **presentation scaffolds and Q&A rehearsal**, then refine with human judgment and voice.
- Reflect on **human–AI collaboration ethics and limits**, articulating when to accept, adapt, or reject AI suggestions.

This document outlines **discrete AI activities** embedded within each phase of the semester, alongside the human-driven work students do. AI is deployed at specific pedagogical moments to serve concrete learning goals—not as an end-to-end integration.

**Philosophy**: AI supports extraction, codification, comparative thinking, and structural problem-solving. Humans drive ideation, creative judgment, and decision-making.

---

## Phase 1: Speculate (Weeks 1-2)
**Human Activities:**
- Cold-open ideation: "What is your idea?"
- Brainstorming sessions using techniques (see `/02_Brainstorming`)
- Peer review of speculative proposals
- Refine ideas based on feedback

### AI Activity 1: Proposal Gap Analysis & Summary (Week 2, post-submission)
**Objective**: Synthesize all proposals; identify overlaps, gaps, and novelty.

**Setup**: 
- Collect all students' speculative proposals
- Run through AI for structured extraction

**Example Prompt**:
```
I have 8 project proposals from students. For each, extract:
- Core problem/idea (1-2 sentences)
- Proposed approach (tech stack, medium, delivery)
- Key technical risk
- Novelty claim
- Point of ambiguity/gap

Format as a table. Flag proposals that address similar problems with different approaches.
```

**Tools**: Claude 3.5 (excellent at structured extraction and pattern recognition)

**Output Expectation**: Markdown table that becomes basis for class discussion

**Integrity Checks**:
- Verify AI didn't fabricate technical specs; spot-check against original proposals
- Confirm novelty claims match what students actually proposed
- Check for hallucinated references or capabilities

**Class Use**: Project the table. Discuss overlaps and complementary ideas. Points to consider:
- "Why did three students gravitate toward [approach]?"
- "What problem area has no proposal yet?"
- "Which proposals could borrow from each other?"

---

### AI Activity 2: Comparative & Generative Prompts (Week 2, in-class brainstorm extension)
**Objective**: Use AI to explore variations, combinations, and alternative framings—not to replace human brainstorming, but to push thinking further.

**Setup**: After peer brainstorming, use AI prompts to generate new angles for student consideration.

**Example Prompts**:
```
1. "What if we combined [Student A's core idea] with [Student B's delivery method]? What problems would that solve? What new problems would it create?"

2. "Here's the problem these proposals are trying to solve: [description]. Generate 3 completely different approaches none of them mentioned. Why might they be overlooked?"

3. "These two proposals seem to conflict. Can you identify where they actually reinforce each other instead?"
```

**Tools**: Claude 3.5 or ChatGPT-4 (both good at imaginative recombination)

**Output Expectation**: 2-3 new angles per prompt, framed as questions/explorations

**Integrity Checks**:
- Remind students: AI outputs are **inspiration, not direction**
- If a suggestion doesn't resonate or feel authentic, discard it
- Student agency remains paramount

**Class Use**: 
- Students see AI prompts on screen in real-time
- Vote on which suggestions are worth pursuing
- Use accepted ideas as seeds for further human ideation

---

## Phase 2: Research (Weeks 3-4)
**Human Activities:**
- Precedent research: identify prior art, existing solutions, technology landscape
- Document sources in Zotero
- Synthesis: identify research gaps, constraints, and design intent
- Create detailed speculative proposal

### AI Activity: Source Extraction & Constraint Mapping (Week 3-4)
**Objective**: Synthesize research corpus; extract key patterns, gaps, and feasibility constraints.

**Setup**:
- Students submit 5-7 research sources (articles, projects, technical docs)
- Paste source summaries or abstracts into AI
- Request structured extraction

**Example Prompt**:
```
I've researched these 5 sources on [topic]:

[Source 1]: [summary]
[Source 2]: [summary]
...etc

Create a table with:
- Column 1: Source
- Column 2: Core solution/approach
- Column 3: Key gap or limitation
- Column 4: Constraint revealed (technical, resource, ethical, etc.)

Then: What problem area do these sources NOT address?
```

**Tools**: Claude 3.5 (strong at pattern recognition across multiple sources)

**Output Expectation**: Structured table + synthesis paragraph identifying research gaps

**Integrity Checks**:
- Verify AI summarized sources accurately; spot-check claims against originals
- Confirm extracted constraints are real (not AI hallucinations)
- Check citations: AI should reference specific sources, not invent details
- Flag: "AI says source X solves Y—does it really?"

**Class Use**: 
- Table informs design decisions and PoC scope
- Students reference it in research section of final documentation
- Identifies which constraints are real vs. which are assumptions

---

## Phase 3: Design (Weeks 5-7)
**Human Activities:**
- Sketch mediation pathways and draft design documentation
- Select and test initial toolchain
- Define PoC scope and feasibility
- Plan skill acquisition
- Create detailed timeline and milestones

### AI Activity 1: Design Specification Refinement (Week 5-6)
**Objective**: Stress-test design intent against technical and conceptual constraints.

**Setup**:
- Students write their design intent (what the system should do, how it mediates, why it matters)
- Ask AI to identify blockers, alternatives, and feasibility issues

**Example Prompt**:
```
Here's my design intent: [describe core concept, user interaction, technical approach]

For this approach, identify:
1. Three major technical blockers and why they might be hard
2. Three alternative approaches and tradeoffs of each
3. One assumption I'm making that could fail
4. What would break this design if I had 50% less budget/time?
```

**Tools**: Claude 3.5 (good at structural thinking and identifying hidden assumptions)

**Output Expectation**: Bulleted analysis of risks, alternatives, and constraints

**Integrity Checks**:
- Verify technical blockers are real (not imagined)
- Student decides which alternatives are worth exploring, not AI
- Constraints should be grounded in actual research, not AI speculation

**Class Use**: 
- Informs design iteration and risk mitigation planning
- Helps students decide what's truly novel vs. what's been solved
- Guides timeline and scope decisions

---

### AI Activity 2: Project Decomposition into GitHub Issues (Week 6-7)
**Objective**: Break broad PoC goals into granular, actionable, sequential GitHub issues.

**Setup**:
- Students have defined their PoC scope and rough timeline
- Use AI to generate GitHub-ready issue list with dependencies

**Example Prompt**:
```
Here's my PoC goal: [description of what "done" looks like]

My technical approach involves: [tools, platforms, components]

Generate 15-20 specific GitHub issues that would complete this PoC. For each:
- Title (clear, actionable)
- Description (what does "done" look like?)
- Acceptance criteria (how do I know it works?)
- Known blockers or dependencies
- Estimated complexity (small, medium, large)

Order them in sequence considering dependencies. Flag any that should be run in parallel.
```

**Tools**: Claude 3.5 (excellent at breaking down complex goals into structured tasks)

**Output Expectation**: GitHub-ready issue list (can be copy-pasted, then refined)

**Integrity Checks**:
- Student validates: Are these issues actually testable/completable?
- Dependencies make sense? Can they be done in sequence?
- Complexity estimates reasonable? (Revisit after prototyping)
- AI might miss edge cases—student adds them

**Class Use**: 
- Foundation for GitHub Project Board
- Students adjust/combine/split issues based on what feels right
- Creates living roadmap for Make phase

---

## Phase 4: Make (Weeks 8-11)
**Human Activities:**
- Prototype iteration cycles (v0 → v1 → v2 → v3 → v4)
- Gather and incorporate structured feedback
- Troubleshoot technical issues
- Expand functionality and refine details
- Test and validate

### AI Activity 1: Code Assistance & Debugging (Weeks 8-11, as needed)
**Objective**: Use AI for error analysis, code generation, and technical problem-solving.

**Setup**:
- When stuck on a bug or implementing a feature, students (or instructor) engage AI coding assistants

**Example Prompts**:
```
1. "I'm getting this error: [error message + code snippet]. What's the root cause? What's the fix? What's the lesson?"

2. "I need to implement [specific function/feature]. Here's my current code: [snippet]. Generate a solution that [requirement]."

3. "This code works but it's slow/fragile/unclear. How would you refactor it?"
```

**Tools**: 
- **GitHub Copilot** (best in IDE; contextual, integrated)
- **ChatGPT-4 or Claude 3.5** (good for broader debugging, explanations, refactoring advice)

**Output Expectation**: Working code + explanation of why the fix works

**Integrity Checks**:
- **Never use AI code without understanding it**
- Test all generated code thoroughly
- If AI code doesn't work, ask AI to explain the failure—learn from it
- Document AI contributions in code comments: `// AI-assisted: [what it helped with]`

**Class Use**: 
- Demonstrates that debugging is collaborative
- Shows how AI can accelerate problem-solving when used thoughtfully
- Leaves audit trail of learning

---

### AI Activity 2: Iterative Issue Refinement (Weeks 9-11)
**Objective**: Regenerate/refine issue breakdown based on what you've learned from prototyping.

**Setup**:
- After completing first 5-8 issues (Week 9), ask AI to reassess remaining work

**Example Prompt**:
```
I've now built [brief description of what's working]. Here's what I've learned:
- [Technical insight 1]
- [Assumption that was wrong]
- [New complexity I didn't anticipate]

My original remaining issues were: [list 2-3]

Given what I know now, how should I reorder/resplit/reframe the remaining work? What should I prioritize first?
```

**Tools**: Claude 3.5 (good at understanding learned constraints and re-prioritizing)

**Output Expectation**: Revised issue list reflecting current reality

**Integrity Checks**:
- Use this to inform decisions, not dictate them
- Student judgment about what matters most should override AI suggestions
- Verify that constraints AI suggests are actually real

**Class Use**: 
- Demonstrates that plans evolve; that's healthy
- Shows iterative thinking in action
- Keeps Project Board aligned with reality

---

## Phase 5: Present (Weeks 12-13)
**Human Activities:**
- Assemble PoC documentation package
- Build slide deck
- Rehearse 10-minute presentation
- Refine narrative and delivery
- Practice Q&A handling

### AI Activity 1: Slide Structure Generation (Week 12)
**Objective**: Scaffold presentation organization; create structure for complex information.

**Setup**:
- Students have PoC documented but haven't structured the story yet
- Use AI to suggest narrative arc and slide breakdown

**Example Prompt**:
```
My 10-minute presentation needs to cover:
- [What problem you're solving]
- [Why existing solutions don't work]
- [Your speculative approach]
- [What you built]
- [What you learned]

Generate a 10-slide outline (roughly 1 minute per slide) that tells a compelling story. What's the narrative arc?
```

**Tools**: Claude 3.5 or ChatGPT-4 (both good at narrative structure)

**Output Expectation**: Slide-by-slide outline with talking points for each

**Integrity Checks**:
- AI structure is a suggestion, not gospel
- Student should rearrange/modify if it doesn't match their intent
- Verify that the story makes sense for *this specific project*, not generic

**Class Use**: 
- Accelerates deck building
- Students can focus on content and design, not structure
- Frees time for rehearsal

---

### AI Activity 2: Q&A Simulation & Anticipation (Week 13)
**Objective**: Stress-test presentation logic; anticipate tough questions.

**Setup**:
- Draft presentation complete; students need to prepare for jury questions
- Use AI to generate challenging questions and practice answers

**Example Prompt**:
```
Here's my presentation: [paste talking points or video transcript]

You're a jury member with expertise in [relevant field]. Generate 5 tough questions you'd ask:
1. Questions about assumptions in my approach
2. Questions about technical feasibility
3. Questions about impact/significance
4. Questions about what comes next

For each, what's a strong answer?
```

**Tools**: Claude 3.5 (good at perspective-taking and identifying logical gaps)

**Output Expectation**: Q&A list + suggested answers (which students then personalize)

**Integrity Checks**:
- AI-generated answers are frameworks, not scripts
- Students should internalize the logic, not memorize
- Verify that questions are actually possible (not AI strawmen)

**Class Use**: 
- Dress rehearsal with AI; then with peers
- Identifies weak spots in logic before jury
- Builds confidence through preparation

---

## Phase 6: Assess (Weeks 14-15)
**Human Activities:**
- Juried presentations (10 minutes + Q&A)
- Self-assessment and reflection
- Document lessons learned
- Archive final deliverables

### AI Activity: Reflection Scaffolding (Week 15)
**Objective**: Use AI to organize thinking for self-assessment; not to replace reflection, but to structure it.

**Setup**:
- After presentations, students complete final self-assessment
- Use AI to help organize reflection thoughts into coherent narrative

**Example Prompt**:
```
Here's what I learned about my design process throughout this project: [bullet points]

Help me organize this into a coherent reflection on:
1. What assumptions did I test that proved wrong?
2. Where did iteration actually change my thinking?
3. What would I do differently if I started over?
4. What did I discover about [your domain] that surprised me?

Don't write the reflection for me—help me structure my thoughts.
```

**Tools**: Claude 3.5 (good at organizing and surfacing deeper thinking)

**Output Expectation**: Structural scaffolding + questions to deepen reflection (not written reflection)

**Integrity Checks**:
- Student writes final reflection in their own voice
- AI is organizational support, not the author
- Reflection should be honest about failures, not polished PR

**Class Use**: 
- Models reflective practice
- Deepens learning by requiring articulation
- Creates artifact of growth

---

## Key Principles Throughout

1. **Human-First**: Humans drive ideation, judgment, and creativity. AI assists with extraction, codification, and structural thinking.
2. **Specific Prompts**: Each activity has concrete example prompts; adapt them to your project.
3. **Verification**: Always check AI outputs—especially facts, citations, technical claims, and code.
4. **Transparency**: If you use AI in class, name it. Students learn by seeing the process.
5. **Judgment Remains with Humans**: AI suggests; students decide.
6. **Optional for Students**: These are instructor-led demonstrations. Students using AI independently should do so thoughtfully, with the same verification discipline.

---

## AI Tools Reference

| Task | Best Tool | Why |
|------|-----------|-----|
| Structured extraction, pattern finding, decomposition | Claude 3.5 (Sonnet) | Excels at complex reasoning and multi-step analysis |
| Comparative thinking, "what if" scenarios | ChatGPT-4 or Claude | Both good; GPT-4 sometimes more creative |
| Code generation, IDE-integrated assistance | GitHub Copilot | Context-aware; integrated into workflow |
| Code explanation, debugging, refactoring | Claude or ChatGPT | Both strong; prefer one per project for consistency |
| Narrative structure, Q&A generation | Claude 3.5 | Strong at perspective-taking and architecture |
| Quick explanations, general knowledge | ChatGPT or Perplexity | Fast and accessible |

**Note**: Tool landscape evolves. These recommendations are current as of January 2026. Adjust based on availability and capability updates.

---

## Prompt-Writing Tips

- **Be specific**: Name your project, your constraints, your goal
- **Provide context**: "I'm building a [type of thing] for [audience] that [does what]"
- **Request structure**: "Format as a table with columns: [X], [Y], [Z]"
- **Ask for alternatives**: "Give me 3 different approaches to [problem]"
- **Request critique**: "What's the weakness in this logic?"
- **Chain follow-ups**: "Based on that, what if I..."
- **Test integrity**: "Can you cite specific sources for that claim?"

---

## Summary

This document outlines **seven concrete AI activities** across the semester:
1. **Speculate**: Proposal gap analysis + comparative prompting
2. **Research**: Source extraction + constraint mapping
3. **Design**: Design refinement + project decomposition
4. **Make**: Code debugging + iterative issue refinement
5. **Present**: Slide structure + Q&A simulation
6. **Assess**: Reflection scaffolding

Each activity serves a specific pedagogical purpose. AI is a tool, not the focus. Human creativity, judgment, and iteration remain central.

*Last updated: January 2026*

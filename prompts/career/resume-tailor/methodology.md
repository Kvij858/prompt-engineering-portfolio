# Design Methodology: Resume Tailoring
## Design Goal
Aimed to help those who struggle with building strong resumes.
---
## Design Approach: Structure and Technique
**Structure I used:** BAB (Before-After-Bridge)
**Why this structure fits my task:**
- It establishes a clear baseline (Before)
- Defines target destination (After)
- Enables gap analysis (Bridge)

**Technique I used:** Few-Shot Prompting
**Why this technique fits my task:**
Language models frequently generate generic or passive bullet points. By providing a clear Before-To-After transformation example inside the prompt, the AI learns the exact tone, bullet point structure, and quantifiable impact level required without relying on abstract instructions alone.
**Example of modifying a framework (delete if not relevant):**
I started from R-T-F (Role, Task, Format) and added two parts. I added a
**Constraints** part to stop the model from making pricing claims, and an
**Example** part to lock in the tone I wanted. My final structure was Role, Task,
Constraints, Example, Format. Each added part solved a specific problem the plain
framework left open.
---
## Part-by-Part Justification
Justify each part of your prompt: what it is, what goes in it, and why the prompt
needs it. If your prompt is technique-driven and short (for example zero-shot
chain-of-thought), justify the technique and the few parts you do have instead.
| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| [Part 1] | [Your text] | [Reason] |
| [Part 2] | [Your text] | [Reason] |
| [Part 3] | [Your text] | [Reason] |
---
## Testing and Iteration
Test your prompt against a naive baseline, a plain version of the same request with
no deliberate structure or technique, and refine it based on what you see.
**Baseline I compared against:**
```
[Your plain, naive version of the same request]
```
| Version | Result / score | What changed |
|---------|----------------|--------------|
| Naive baseline | [result] | [notes] |
| Version 1 | [result] | [notes] |
| Final | [result] | [notes] |
**What testing showed:** [In your own words, how your designed prompt performed
compared to the baseline, and what you changed as a result.]
**What I learned:** [What this taught you about prompt design.]
---
## Strengths and Limitations
**Works well when:** [The conditions where this prompt performs best.]
**Struggles when:** [Where it breaks down, and why.]
**Would improve next:** [What you would refine with more time.]

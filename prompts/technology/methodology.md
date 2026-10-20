# Design Methodology: Code Debugger 
## Design Goal
This prompt aims as a helping tool to explain difficult coding concepts and produce solutions to coding errors you may run into. This can be particularly useful towards students who are learning how to code and are struggling with understanding rigorous concepts.

---
## Design Approach: Structure and Technique
**Structure I used:** Context/Task/Constraints/Format layout
**Why this structure fits my task:**
### Context:
- Sets the role for the AI model in order to understand the situation. 
- Prevents the model from giving overly complex answers which may be difficult for beginners to understand. 

### Task:
- Lists specific step actions and explains what is happening with the code. 
- Produces an example of the fixed code block so it can be used as a guide for programmers. 

### Constraints: 
- Sets boundaries that AI must follow. 
- Prevents the AI model from rewriting entire program or introducing concepts the programmer hasn't learned yet.
  
**Technique I used:** Chain-of-thought 

**Why this technique fits my task:**
[For example: I used few-shot because the AI needed to copy a specific tone, so I
gave it two sample outputs. Or: I used zero-shot chain-of-thought because the task
needs step-by-step logic but I did not have examples, so I added "Think through
this step by step before you answer."]
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

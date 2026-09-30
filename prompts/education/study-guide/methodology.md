# Design Methodology: Study Guide Generator
## Design Goal
Creating a study guide that transforms raw learning materials (lecture notes, chapter excerpts, or outlines) into exam-ready study guides. It is designed for students and educators seeking to study prep through clear conceptual breakdowns and active-recall practice tools.

---
## Design Approach: Structure and Technique
Explain the two design choices behind your prompt and why they fit the task.
**Structure I used:** CARE (Context, Action, Result, Evaluation)
**Why this structure fits my task:**
- Prevents generic summaries: By defining strict Action steps and Result formatting, the structure ensures the AI doesn't just restate text, but transforms notes into learning tools. 
- Quality control: The evaluation component sets accurate information regarding reading and education level ensuring the output is immediately exam-ready.
  
**Technique I used:** Chain-of-thought
**Why this technique fits my task:**
Study guides require logic before generation so the AI must identify core principles before it can write meaningful practice questions. By instructing the model to evaluate concepts step-by-step prior to writing the output, CoT produces higher-order thinking questions.

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

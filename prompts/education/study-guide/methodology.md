# Design Methodology: Study Guide Generator
## Design Goal
Creating a study guide that transforms raw learning materials (lecture notes, chapter excerpts, or outlines) into exam-ready study guides. It is designed for students and educators seeking to study prep through clear conceptual breakdowns and active-recall practice tools.

---
## Design Approach: Structure and Technique
Explain the two design choices behind your prompt and why they fit the task.
**Structure I used:** CARE (Context, Action, Result, Evaluation)
**Why this structure fits my task:**
- Prevents generic summaries
- Quality control
  
**Technique I used:** Chain-of-thought

**Why this technique fits my task:**
Study guides require logic before generation so the AI must identify core principles before it can write meaningful practice questions. By instructing the model to evaluate concepts step-by-step prior to writing the output, CoT produces higher-order thinking questions.

---
## Part-by-Part Justification
| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Context | Academic level, course/subject, target exam style, and source materials. | Establishes the cognitive baseline and scope so the AI tailors its explanation appropriately and stays anchored to the provided material. |
| Action | Step-by-step instructions for extracting key concepts, building glossary terms, and formulating practice questions. | Drives the AI to actively process and synthesize the material rather than generating a unstructured walls of text. |
| Result | Explicit Markdown formatting constraints | Ensures the deliverable is visually organized, easy to scan, and directly usable as an active-recall study tool. |
| Evaluation | Pedagogical Constraints (Evaluation) Quality rules, such as requiring explanations for incorrect distractors.| Prevents surface-level passive summaries and forces the AI to construct meaningful active-learning assessments with strict factual accuracy. |
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
| Naive baseline | 35 | This text reads as a descriptive overview or promotional summary of what a study guide prompt does, rather than an actual executable prompt. |
| Version 1 | 55 | While it references the CARE framework and Chain-of-Thought technique, it fails to flesh out the framework components (Context, Action, Result, Example) directly within the prompt body. |
| Final | [result] | [notes] |
**What testing showed:** [In your own words, how your designed prompt performed
compared to the baseline, and what you changed as a result.]
**What I learned:** [What this taught you about prompt design.]
---
## Strengths and Limitations
**Works well when:** [The conditions where this prompt performs best.]
**Struggles when:** [Where it breaks down, and why.]
**Would improve next:** [What you would refine with more time.]

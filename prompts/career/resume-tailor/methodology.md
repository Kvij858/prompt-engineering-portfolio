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

---
## Part-by-Part Justification
| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Constraints | Strict instructions given to AI to match job description keywords while maintaining 100% factual accuracy. | Configures the AI to act like recruitment software scanning for high-density keywords, ensuring the output passes automated HR filters without artificially inflating candidate qualifications. |
| Placeholders | Dynamic input markers for raw user text and target job listings | Separates system logic from variable user content, ensuring predictable parsing across different industries. |
| Output Rules & Formatting | Length limits (1–2 pages), bullet structure, and core competency requirements | Guarantees the generated resume remains clean, readable, concise, and formatted properly. |
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
| Naive baseline | 0 | The prompt lacks complexity and doesn't have a proper framework or structure. |
| Version 1 | 15 | While it does state the type of framework and structure used, it mainly serves as an outline for the prompt. |
| Final | 100 | Moving from merely describing the BAB framework to fully populating its sections alongside explicit placeholders ([Current resume], [Job Description]) and detailed output requirements made an executable, high-performing prompt. 
---
**What testing showed:**  
When testing the tailored prompt against a basic baseline prompt (such as "Rewrite my resume for this job description"), the baseline produced generic, generic-sounding bullet points that often hallucinated skills or removed important context. In contrast, adding explicit AI roles, the BAB execution framework, and few-shot transformation examples significantly improved performance. 

**What I learned:** 
Prompt design isn't just about setting up a basic template; it's about managing complexity and guiding how the AI processes information. 

---
## Strengths and Limitations
**Works well when:** [The conditions where this prompt performs best.]
**Struggles when:** [Where it breaks down, and why.]
**Would improve next:** [What you would refine with more time.]

# Design Methodology: Resume Tailoring
## Design Goal
Aimed to help those who struggle with building strong resumes.

---
## Design Approach: Structure and Technique
**Structure I used:** BAB (Before-After-Bridge)
**Why this structure fits my task:**
### Before:
- Passive phrasing: Generic words are present such as "like, created, managed."
- Lack of impact or scope: Fails to include career or skill growth.
- Vague skills: Does not specify technical skills.

### After:
- Showing clear, measurable results
- Aligning keywords directly towards the targeted audience
- Including relevant, important information to create a sophisticated resume 

### Bridge: 
- Mapping relevant skills and tools into bullet points
- Explaining scale of achievements and project complexity
- Using frameworks and structure to enhance resume

**Technique I used:** Few-Shot Prompting

**Why this technique fits my task:** Language models may often produce boring or generic bullet points, but by providing a clear Before-After-Bridge example, AI can better generate results based on your needs. 

---
## Part-by-Part Justification
| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Current job experience | Raw candidate data which includes past job titles, companies you worked for, technical skills, and other useful information. | This provides a nice foundation and AI models can use your information to create realistic and truthful resumes instead of generating false facts.|
| Formatting and output rules | Strict guidelines (e.g. 1-2 page, bullet point, headers, diction| This prevents chunky or blocky long texts. The document can be easily read and scanned through, it should not be like an essay. It should be short and concise.|
| Target Audience and Tone | Desired brand voice (e.g. confident, analytical) and including specific details that appeals to your employer | This creates better chances of being accepted into a desired job listing by appealing to a specific employer and making your resume sound confident and professional.|

However, because the actual prompt text is omitted and only the theoretical strategy is provided, the AI cannot execute the task. To complete this prompt, write out the actual instruction set incorporating labeled BAB sections, explicit placeholders like [INSERT RAW RESUME HERE], a worked Few-Shot example, and strict output rules. 
---
## Testing and Iteration
Test your prompt against a naive baseline, a plain version of the same request with
no deliberate structure or technique, and refine it based on what you see.
**Baseline I compared against:**
```
["Aimed to help those who struggle with building strong resumes."
]
```
| Version | Result / score | What changed |
|---------|----------------|--------------|
| Naive baseline | 0 | The prompt lacks complexity and doesn't have a proper framework or structure. |
| Version 1 | 15 | While it does state the type of framework and structure used, it mainly serves as an outline for the prompt. |
| Final | 100 | Moving from merely describing the BAB framework to fully populating its sections alongside explicit placeholders ([Current resume], [Job Description]) and detailed output requirements made an executable, high-performing prompt. 
---
**What testing showed:** When testing the tailored prompt against a basic baseline prompt (such as "Rewrite my resume for this job description"), the baseline produced generic, generic-sounding bullet points that often hallucinated skills or removed important context. In contrast, adding explicit AI roles, the BAB execution framework, and few-shot transformation examples significantly improved performance. 

**What I learned:** 
Prompt design isn't just about setting up a basic template; it's about managing complexity and guiding how the AI processes information. 

---
## Strengths and Limitations
**Works well when:** The input resume and target job description are both detailed, complete, and closely aligned in field. It's efficient at drawing out relevant qualifications, replacing passive phrasing with targeted action verbs, and organizing skills cleanly into job-specific categories.
**Struggles when:** The original resume lacks detail. It also struggles when bridging massive career changes where past responsibilities have virtually no overlap with the target role, or when job descriptions are vague and lack clear skill requirements.
**Would improve next:** I would incorporate strict Applicant Tracking System (ATS) structural rules to ensure bullet points use standard, scannable keywords. I would also add an interactive follow-up step that prompts the user for specific metrics whenever missing quantitative data is detected in the draft.

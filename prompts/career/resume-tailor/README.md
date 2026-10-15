# Resume Tailoring Overview
> *This prompt focuses on building and tailoring resumes. This is just an overview of what the prompt is for, more details about the prompt can be found on [`prompt.md`](./prompt.md). *
## Overview
This prompt produces a well made resume based off work experience and specific job postings you want to apply for. This prompt saves endless amounts of time used on rewriting applications for different jobs. This can be useful for job seekers and career switchers. 
**Best for:**
- Tailoring a professional resume
- Emphasizing transferable skills
- **Structure:** BAB (Before, After, Bridge)
- **Technique:** few-shot 
- **Output:** Short and concise one to two pages resume
---
## Quick Start
Go into [`examples1.md`](./example1.md). 
- **[Current resume]:** Provide your raw resume text. This serves as your baseline, providing the authentic career history, job titles, and past duties that can be used without fabricating data.
- **[Job Description]:** The complete overview of the job listing you are applying for. This is critical because it dictates the specific hard skills and soft skills that must be analyzed and integrated.
3. Paste it into your AI model of choice and run it.
4. Review the output and adapt it to what you need.
---
## Examples
See the [`examples/`](./examples/) folder for filled-in demonstrations showing the
prompt and the resulting output.
---
## Customization Tips
- **Want more detail?** Add prompts like "Provide a step-by-step breakdown" or "Include specific case studies."
- **Want it shorter?** Specify output constraints, such as "Summarize in under 100 words" or "Use bullet points only."
- **Different context?** Swap out domain-specific terminology (e.g., adjust technical jargon for a non-technical corporate audience or a different industry like healthcare/finance).
---
## Technical Details
- **Structure:** BAB
- **Technique:** Few shot
- **Best models:** Advanced LLMs (e.g., GPT-4o, Claude 3.5 Sonnet, Gemini 1.5 Pro)
- **Placeholders:** 3 main placeholders ([Insert Current State], [Insert Desired Outcome], [Insert Target Audience])

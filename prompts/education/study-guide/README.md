# Study Guide Generator 
> *Transforms complex notes, textbook chapters, or topic outlines into structured, exam-ready study guides.*
## Overview
This prompt takes learning materials such as lecture transcripts, reading excerpts, or lists of key terms and organizes them into a clear study guide. It breaks down complex concepts, highlights core definitions, creates practice questions, and suggests study strategies. It is ideal for students, educators, and lifelong learners looking to streamline their exam preparation.
**Best for:**
- Preparing for midterms, finals, or standardized tests.
- Summarizing heavy textbook chapters or lengthy lecture notes.
- Creating self-testing materials (flashcard prompts and practice questions).
**Structure:** CARE (Context, Action, Result, Evaluation)
**Technique:** Chain-of-thought
**Output:** A structured Markdown guide (~800–1,500 words) with key terms, concept breakdowns, summary tables, and practice quizzes with answer keys.
---
## Quick Start
1. Open [`prompt.md`](./prompt.md) and copy the template.
2. Replace the placeholders:
- [SUBJECT_OR_COURSE]: The specific subject (e.g., AP Biology, Organic Chemistry, World History).
- [SOURCE_MATERIAL]: Your notes, chapter text, transcript, or topic outline.
- [TARGET_EXAM_FORMAT]: (Optional) The exam style (e.g., Multiple Choice, Essay, Short Answer).
3. Paste it into your AI model of choice and run it.
4. Review the output and adapt it to what you need.
---
## Examples
See the [`examples/`](./examples/) folder for filled-in demonstrations showing the
prompt and the resulting output.
---
## Customization Tips
- **Want more detail?** Ask the model to add real-world analogies or step-by-step worked solutions for problems.
- **Want it shorter?** Request a 1-page "cheat sheet" focus that includes the material you want to learn.
- **Different context?** Adjust the academic level (e.g., "Explain for a Middle Schooler" vs. "Graduate level depth").
---
## Technical Details
- **Structure:** CARE
- **Technique:** Chain-of-thought]
- **Best models:** GPT-4o, Claude 3.5 Sonnet, Gemini 1.5 Pro.
- **Placeholders:** 3: [SUBJECT_OR_COURSE], [SOURCE_MATERIAL], [ACADEMIC_LEVEL].

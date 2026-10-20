# Code Debugger Template
---
## Overview
**Purpose:** Gives a breakdown of code and explains the errors that occur such as syntax or logic errors while giving the correct context and beginner friendly terms to those who are beginners at programming.

**Structure:**  Context, Task, Constraints, Format

**Technique:** Chain-of-thought 
---
## The Prompt and Framework explained 
This is what you can say to the AI model for each of the components: 

**Context:**
EXAMPLE: I am a student working on a programming assignment in [PROGRAMMING_LANGUAGE] and my code is not working as expected, can you explain why this section of my code isn't working? 

**Task (For AI model):**
- Analyze the provided code snippet and trace its execution step-by-step.
- Identify the syntax error, logic bug, or runtime issue.
- Explain why the bug occurs for beginners.
- provide the corrected code snippet

**Constraints (For AI model):**
- The AI model should keep explanations clear and suitable for beginner programming students 
- Retain original variable names and code structure as much as possible.
- Do not introduce advanced concepts that a beginner has not learned in order to avoid confusion. 

**Format:**
- State the error in a brief paragraph or bullet points.
- Explain the logic behind the code and supply solutions on how to fix the code. 
- Provide an example of what the code would look like if it were fixed. 

---
## Context and Inputs
List the information the user has to supply, written as placeholders:
- **[PLACEHOLDER_1]:** [What goes here and why it matters]
- **[PLACEHOLDER_2]:** [What goes here and why it matters]
- **[PLACEHOLDER_3]:** [What goes here and why it matters]
---
## Output Requirements
**Format:** [How the answer should be structured, for example length, headings,
bullets, or a table.]
**Constraints:** [Rules that keep the AI on scope and protect quality.]
**Tone and Style:** [The voice, reading level, and style you want.]
---
## Additional Instructions (optional)
Anything else the AI should keep in mind that does not fit one of the parts above.
Delete this section if you do not need it

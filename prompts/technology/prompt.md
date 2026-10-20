# Code Debugger Template
---
## Overview
**Purpose:** Gives a breakdown of code and explains the errors that occur such as syntax or logic errors while giving the correct context and beginner friendly terms to those who are beginners at programming.

**Structure:**  Context, Task, Constraints

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

---
## Context and Inputs
List the information the user has to supply, written as placeholders:
- **[PROGRAMMING_LANGUAGE]:** The specific programming language being used. This matters because it tells the AI which syntax rules, language-specific conventions, and compiler behaviors to apply during explanation.
- **[CODE_SNIPPET_OR_ERROR]:** The exact block of broken code. This matters because it provides the input the AI must trace and debug.
---
## Output Requirements
**Format:**  State the error in a brief paragraph or bullet points, explain the logic behind the code and supply solutions on how to fix the code, provide an example of what the code would look like if it were fixed.

**Tone and Style:** Direct, precise, and practical. Brief summary of the bug and detailed step-by-step breakdown depending on your needs.

---

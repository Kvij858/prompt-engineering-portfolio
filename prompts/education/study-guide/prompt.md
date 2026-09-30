# Study Guide Generator
---
## Overview
**Purpose:** Generates comprehensive, structured study guides tailored to specific subjects, topics, or exam formats to help students review and master core concepts efficiently.

**Structure:** CARE framework (Context, Action, Result, Evaluation), This framework excels when the AI needs background information to function correctly, such as your education level and subjects in order to make effective study guide materials.

**Technique:** Chain-of-thought, prompting the model to step-by-step break down the curriculum before drafting the final guide). 

---
## The Prompt
**C- Context:**
- Subject / Topic: Insert Subject or Topic Here, e.g., AP European History - The Industrial Revolution
- Target Audience: Insert Grade Level or Skill Level, e.g., 11th Grade AP Students
- Key Focus Areas: List key themes, textbook chapters, or exam standards
- Prerequisite Knowledge: Briefly note what students should already know
  
**A- Action:**
Your core task is to prompt AI to process the provided subject material and generate a clear, comprehensive study guide that maximizes student retention and mastery. 
1. Analyze the context and break down the primary concepts into logical teaching modules.
2. Extract and define essential domain vocabulary clearly with real-world context.
3. Highlight critical mechanisms, causes and effects, or key principles.
4. Identify high-frequency exam traps, common misconceptions, or easily confused ideas.
5. Formulate targeted comprehension questions with evaluation criteria to test student mastery.

**R- Result:**
Structure the final output using the following template format:
### 1. High-Level Summary
- A 2-3 sentence overview explaining what this topic covers and why it is essential.

### 2. Essential Vocabulary
| Term | Definition | Context / Example |
| :--- | :--- | :--- |
| [Term 1] | [Definition] | [Example] |

### 3. Core Concepts Breakdown
#### [Concept 1]
- **Key Takeaway:** [Main idea]
- **Detailed Explanation:** [In-depth breakdown with bullet points]

#### [Concept 2]
- **Key Takeaway:** [Main idea]
- **Detailed Explanation:** [In-depth breakdown with bullet points]

### 4. Common Misconceptions & Traps
- **Misconception:** [Explain common mistake]
  - **Correction:** [Explain correct understanding]

**E- Evaluation:**
[The content for this part.]
[Add or remove parts so the structure matches your design.]
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
Delete this section if you do not need it.

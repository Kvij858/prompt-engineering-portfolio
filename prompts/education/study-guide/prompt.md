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
Can be found on [`examples/`](./examples/) folder.

**E- Evaluation:**

Conclude the study guide with a self-assessment section that allows students to evaluate their readiness:
Can be found on See the [`examples/`](./examples/) folder. 

---
## Context and Inputs
List the information the user has to supply, written as placeholders:
- **[SUBJECT_OR_COURSE]:** The specific subject (e.g., AP Biology, Organic Chemistry, World History). In order for the study material to be relevant, AI will need the type of subject the study material is for.  
- **[SOURCE_MATERIAL]:** Your notes, chapter text, transcript, or topic outline. Providing source material helps AI generate a study guide fit for your needs, according to your source material. 
- **[TARGET_EXAM_FORMAT]:** The exam style (e.g., Multiple Choice, Essay, Short Answer). Having a structured and easy format to work through can be helpful for learning, especially if the study material is heavy. 
---
## Output Requirements
**Format:** Use bold text for key terms, emphasis, and structural labels, use proper heading, and use tables for specific study material. 
**Constraints:** Rely primarily on the provided `[Source Material]` to prevent factual errors. Do not omit critical foundational definitions required to understand the core concepts.
**Tone and Style:** - Encouraging, clear, authoritative, and academically supportive. 

---

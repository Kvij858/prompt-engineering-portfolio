# Design Methodology: Code Debugger 
## Design Goal
This prompt aims as a helping tool to explain difficult coding concepts and produce solutions to coding errors you may run into. This can be particularly useful towards students who are learning how to code and are struggling with understanding rigorous concepts.

---
## Design Approach: Structure and Technique
**Structure I used:** Context/Task/Constraints/Format layout
**Why this structure fits my task:**
### Context:
- Sets the role for the AI model in order to understand the situation. 
- Prevents the model from giving overly complex answers which may be difficult for beginners to understand. 

### Task:
- Lists specific step actions and explains what is happening with the code. 
- Produces an example of the fixed code block so it can be used as a guide for programmers. 

### Constraints: 
- Sets boundaries that AI must follow. 
- Prevents the AI model from rewriting entire program or introducing concepts the programmer hasn't learned yet.
  
**Technique I used:** Chain-of-thought 

**Why this technique fits my task:**
By using this technique, the AI model can trace the code line by line before producing the corrected output. This can minimize hallucinations, increase bug accuracy, and it can teach similarly to how a CS teacher would teach a student. 

---
## Part-by-Part Justification
Justify each part of your prompt: what it is, what goes in it, and why the prompt
needs it. If your prompt is technique-driven and short (for example zero-shot
chain-of-thought), justify the technique and the few parts you do have instead.
| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Context of code | Context of the topic you are studying and explanation of the code project you are working on | The AI model of your choice can analyze and produce results that relate to the topic, also while giving an explanation of the current programming language you are studying and what concept you're focusing on. |
| Task for model | Gives step by step instructions so that the model can identify the bug, explain why it happened, and provide the corrected code.| The AI model can thouroughly teach you the material you are struggling to understand instead of simply giving you a code for you to copy and paste. You can actively learn and the goal is for you to understand the material in order to produce code on your own. |
| Constraints | Rules that are given to the AI model so that the model can stay within the context and not produce any outputs that confuses the programmer. | This prevents the AI model from rewriting your coding project and simply outputting a coding block for you to copy and paste without giving any explanation. |
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
**Works well when:** This prompt works well in regards to debugging coding errors such as runtime, logic, and syntax errors while also teaching you why the errors occurred. It works well for students who are beginners in coding and don't understand the programming concepts of the language they are learning. 
**Struggles when:** It struggles when given a massive block of code. This prompt is designed to fix portions of code rather than to fix the entire coding project. Struggle can also occur when the user does not give the correct context, leading to the AI model creating their own explanation of topics you may already know without focusing on the topics you don't understand. 
**Would improve next:** The AI model can improve on giving hints to the code instead of simply outputting the answer. The AI is made for teaching, so in order to avoid students copy and pasting the answers, the model will have to give hints and explain the errors rather than just giving the answer right away. 

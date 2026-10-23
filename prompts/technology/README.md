# Code Debugger 
> *This prompt focuses on explaining code errors and concepts. This is just an overview of what the prompt is for, more details about the prompt can be found on [`prompt.md`](./prompt.md).*
## Overview
This prompt produces a step by step breakdown of code and explains any logic or coding errors that may occur. While this can be used as a learning tool similar to the education prompt, this prompt specializes in technology. 
**Best for:**
- Deciphering code and compiling errors  
- Studying or analyzing coding problems 
- Finding and fixing logic bugs 
**Structure:** Context/Task/Constraints layout
**Technique:** Chain-of-thought
**Output:** Short breakdown which includes the corrected code block. 
---
## Quick Start
1. Have the context and code for the project you are stuck on. 
2. Paste it into your AI model of choice and run it.
4. Review the output and learn from it. Examples can be found on [`examples/`](./examples/). Click on 'example1'
and there you will see an example of what the process should look like. 
---
## Customization Tips
- **Want more detail?** Add a constraint asking the AI to explain concepts.
- **Want it shorter?** Specify which code block you want to focus on rather than the entire code. 
- **Different context?** Adjust the prompt for different tasks such as "Explain nested for loops of this specific code block." 
---
## Technical Details
- **Structure:** Context/Text/Constraints layout 
- **Technique:** Chain-of-thought
- **Best models:** Claude 3.5 Sonnet, GPT-4o, Gemini 1.5 Pro
- **Placeholders:** [Number and type]

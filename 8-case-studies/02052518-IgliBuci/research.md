Epoka University  
Subject: Introduction to Software Engineering.  
Class: SWE 1C

# “Real Industry Case Studies”

### Igli Buci

June 1, 2026

## Introduction

Software engineering has always changed throughout the tools that were available for developers, from the introduction of version control systems to the birth of cloud computing. Each technological change has required engineers to adapt by learning new skills, but today artificial intelligence represents  the largest part of the transformations that have been happening over the last decade.

AI in software development has moved beyond theory and now delivers real business value. Yet surprisingly, about two-thirds of organizations haven't started scaling AI across their operations. Change is happening faster than ever. Microsoft's 2025 Work Trend Index reveals that 81% of global leaders anticipate AI agents will blend into their organizations within the next 12-18 months. The numbers tell a compelling story—teams can cut their code generation, refactoring, and documentation time in half. Even more impressive, "frontier firms" have seen 30% more developer efficiency, 40% lower costs, and products reaching markets 50% faster. (Hurkova, 2025)

## 

## Main Findings



### Accelerating AI Development with GitHub Copilot: Real-World Use-Cases

In recent years Microsoft teams have been trying to use AI to improve the productivity of their engineers. The goal was to integrate GitHub in the workflow of their teams in order to speed up tasks such as documentation, code generation, or other basic and repetitive tasks, showing the benefits and the challenges encountered.

**Microsoft's 3-Step Process with Github Copilot**

The workflow we landed on was simple but effective: prepare your documentation, have Copilot follow it, and then validate the results.

1. We began by drafting a structured README for our use case, outlining each step needed to create a new experiment, and then we used Copilot to generate the first version but we kept a human in the loop to test the README manually, refining Copilot’s output by editing what was missing or wrong and trimming unnecessary parts
2. With the documentation ready, we asked Copilot to act on it by making concrete actions, and then the process was initiated. Copilot proceeded to generate the required Python files, configuration files, and even boilerplate test code, and prompting it helps to catch errors and gaps in the documentation. By encouraging Copilot to ask for clarification, we turned failures into opportunities to improve both the documentation and Copilot’s performance
3. Finally, we used Copilot to validate the implementation, so we prompted it to review the code and identify anything that was missing, and it correctly identified missing cases and generated appropriate test functions for our framework.

Copilot can be a great tool to get a head start in building class diagram visualizations; however, it’s important to validate the results thoroughly to ensure accuracy. The following strategies can help you refine your initial results:  
**Start with an Example**  
Be more specific with the desired results of your diagram. Copilot did much better when it started with an example it could pull from.  
**Context matters.**  
Some models may only retrieve partial context of each file, while others might read too much—both can result in a subpar result. When reading through the chat logs or output, make sure that Copilot is reading the entire file or context when generating the diagram and reading the files you need.  
**Experiment with Different Models**  
The Claude Sonnet 3.7 thinking model worked best for generating class diagrams, while GPT 4o needed more instruction. While the Claude models would be our recommendation for this task, continue to test out other models. As newer models get released, they may be even more advanced at creating visualizations.  
**Consider the diagram format.**  
The choice of starting from a graphical tool like pyreverse versus a text-centric format like Mermaid Markdown may have impacted the results. For example, Mermaid Markdown could provide clearer context for models like Sonnet, potentially improving accuracy. GPT-4o may still face context limitations, but Sonnet might benefit from the text-based approach.  
After creating your draft diagram, you will still need to review it extensively to ensure accuracy. (Microsoft ISE Developer Blog, 2025)


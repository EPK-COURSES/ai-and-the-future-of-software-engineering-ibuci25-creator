Epoka University  
Subject: Introduction to Software Engineering.  
Class: SWE 1C

“Real Industry Case Studies”  
Igli Buci
---

June 1, 2026

## Introduction

Software engineering has always changed throughout the tools that were available for developers, from the introduction of version control systems to the birth of cloud computing. Each technological change has required engineers to adapt by learning new skills, but today artificial intelligence represents  the largest part of the transformations that have been happening over the last decade.

AI in software development has moved beyond theory and now delivers real business value. Yet surprisingly, about two-thirds of organizations haven't started scaling AI across their operations. Change is happening faster than ever. Microsoft's 2025 Work Trend Index reveals that 81% of global leaders anticipate AI agents will blend into their organizations within the next 12-18 months. The numbers tell a compelling story—teams can cut their code generation, refactoring, and documentation time in half. Even more impressive, "frontier firms" have seen 30% more developer efficiency, 40% lower costs, and products reaching markets 50% faster. (Hurkova, 2025)

## 

## Main Findings

### **Case 1:** Accelerating AI Development with GitHub Copilot: Real-World Use-Cases

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

### Case 2: AI in software engineering at Google: Progress and the path ahead

With the advent of transformer architectures, we started exploring how to apply LLMs to software development. LLM-based inline code completion is the most popular application of AI applied to software development: it is a natural application of LLM technology to use the code itself as training data. The UX feels natural to developers since word-level autocomplete has been a core feature of IDEs for many years. Also, it’s possible to use a rough measure of impact, e.g., the percentage of new characters written by AI. For these reasons and more, it made sense for this application of LLMs to be the first to deploy.

**Our work so far has taught us several things:**

1. We achieved the highest *impact with UX that naturally blends into users’ workflows*. In all the above examples, a suggestion is presented to the user, taking them to the next step in their workflow with one tab or click. Experiments requiring the user to remember to trigger the feature have failed to scale.
2. We observe that with AI-based suggestions, the *code author increasingly becomes a reviewer*, and it is important to find a balance between the cost of review and added value. We typically address the tradeoff with acceptance rate targets.
3. Quick iterations with *online A/B experiments are key*, as offline metrics are often only rough proxies of user value. By surfacing our AI-based features on internal tooling, we benefit greatly from being able to easily launch and iterate, measure usage data, and ask users directly about their experience through UX research.
4. *High-quality data* from the activities of Google engineers across software tools, including interactions with our features, is essential for our model quality.

An ongoing challenge in this domain is that AI technology is evolving quickly, and it is hard to predict which ideas to explore first. There is often a significant gap between technically feasible demos and successful productization. We approach the deployment of ideas to products with three guidelines:

1. *Prioritize by technical feasibility and impact*: Work on ideas wherein both technical feasibility has already been established and high (measureable) impact on engineers’ workflows is expected.
2. *Learn quickly to improve UX and model quality*: Focus on iterating quickly and extracting lessons learned while safeguarding developer productivity and happiness. User experience is just as important as model quality.
3. *Measure effectiveness*: As our goal is to increase productivity and satisfaction metrics, we need to extensively monitor these metrics. (Chandra \& Tabachnyk, 2024)

An ongoing challenge in this domain is that AI technology is evolving quickly, and it is hard to predict which ideas to explore first. We approach deployment of ideas to products with three guidelines:

1. Prioritize by technical feasibility and impact: Work on ideas wherein both technical feasibility has already been established and high (measureable) impact on engineers’ workflows is expected.
2. Learn quickly to improve UX and model quality: Focus on iterating quickly and extracting lessons learned while safeguarding developer productivity and happiness. User experience is just as important as model quality.
3. Measure effectiveness: As our goal is to increase productivity and satisfaction metrics, we need to extensively monitor these metrics.(Chandra \& Tabachnyk, 2024)


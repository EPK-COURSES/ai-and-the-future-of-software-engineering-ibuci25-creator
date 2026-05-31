Epoka University  
Subject: Introduction to Software Engineering.  
Class: SWE 1C

# “Real Industry Case Studies”

&#x20; 
Igli Buci
---

June 1, 2026

## Introduction

Software engineering has always changed throughout the tools that were available for developers, from the introduction of version control systems to the birth of cloud computing. Each technological change has required engineers to adapt by learning new skills, but today artificial intelligence represents  the largest part of the transformations that have been happening over the last decade.

AI in software development has moved beyond theory and now delivers real business value. Yet surprisingly, about two-thirds of organizations haven't started scaling AI across their operations. Change is happening faster than ever. Microsoft's 2025 Work Trend Index reveals that 81% of global leaders anticipate AI agents will blend into their organizations within the next 12-18 months. The numbers tell a compelling story—teams can cut their code generation, refactoring, and documentation time in half. Even more impressive, "frontier firms" have seen 30% more developer efficiency, 40% lower costs, and products reaching markets 50% faster. (Hurkova, 2025)

## 

## Main Findings

**Case Study 1:** Accelerating AI Development with GitHub Copilot: Real-World Use-Cases

In recent years Microsoft teams have been trying to use AI to improve the productivity of their engineers. The goal was to integrate GitHub in the workflow of their teams in order to speed up tasks such as documentation, code generation, or other basic and repetitive tasks, showing the benefits and the challenges encountered.

**Microsoft's 3-Step Process with Github Copilot**

1. We began by drafting a structured README for our use case, outlining each step needed to create a new experiment, and then we used Copilot to generate the first version but we kept a human in the loop to test the README manually, refining Copilot’s output by editing what was missing or wrong and trimming unnecessary parts
2. With the documentation ready, we asked Copilot to act on it by making concrete actions, and then the process was initiated. Copilot proceeded to generate the required Python files, configuration files, and even boilerplate test code, and prompting it helps to catch errors and gaps in the documentation. By encouraging Copilot to ask for clarification, we turned failures into opportunities to improve both the documentation and Copilot’s performance
3. Finally, we used Copilot to validate the implementation, so we prompted it to review the code and identify anything that was missing, and it correctly identified missing cases and generated appropriate test functions for our framework.

**Findings**  
Be more specific with the desired results of your diagram. Copilot did much better when it started with an example it could pull from. Some models may only retrieve partial context of each file, while others might read too much—both can result in a subpar result. When reading through the chat logs or output, make sure that Copilot is reading the entire file.  
The Claude Sonnet 3.7 thinking model worked best for generating class diagrams, while GPT 4o needed more instruction. While the Claude models would be our recommendation for this task, continue to test out other models. As newer models get released, they may be even more advanced at creating visualizations. The choice of starting from a graphical tool like pyreverse versus a text-centric format like Mermaid Markdown may have impacted the results. For example, Mermaid Markdown could provide clearer context for models like Sonnet, potentially improving accuracy. (Microsoft ISE Developer Blog, 2025)

**Case Study 2:** AI in software engineering at Google: Progress and the path ahead

With the development of transformative architecture, researchers began to explore how large language models could be used in software engineering, where the most common applications were those AI-powered ones that complete code with suggestions to improve it, which led to these LLMs being trained directly on the code being written. It is also natural for programmers, as auto-completion has been a feature in IDEs for many years.

**Our work so far has taught us several things:**

As a start, the greatest success came from features that were a natural fit for the programmers' workflow, where in these AI systems, suggestions are given to help users continue their work with a single click. On the other hand, the features that required manual activation were not widely usable.

Secondly, when AI gives suggestions, developers behave like a controller rather than writing everything themselves, and because of this, we need to balance the use of AI generations with the time we spend reviewing them, and one way to measure the balance is through the acceptance rate or how often users accept AI suggestions.

Thirdly, fast experimentation using online A/B testing, because often offline measurements do not present real user values. Thus, by testing them internally, teams improve features, analyze data usage, and get direct feedback from users.

Finally, the data collected by Google's engineers and their interaction with these software are essential for improving these AI tools.

A continuous challenge in AI for software engineers is that technology changes very quickly, making it difficult to decide which idea to implement first, because creating a demo and turning it into a successful product are two very different things.

Researchers at Google follow three main guidelines:

1. **Prioritize feasibility and impact**  
Focus on ideas that are technically possible and are expected to have a strong, measurable impact on developers’ work and productivity.
2. **Learn quickly and improve continuously**  
Rapid testing and iteration are important for improving both user experience (UX) and AI model quality. Protecting developers’ productivity and satisfaction is also a key priority.
3. **Measure effectiveness**  
Since the main goal is to improve productivity and user satisfaction, it is necessary to closely monitor these metrics and evaluate how effective the AI tools are.

These principles help organizations successfully move AI ideas from experiments into practical products used in real software development environments. (Chandra \& Tabachnyk, 2024)

**Case Study 3:** Shopify — AI-Assisted Engineering at Scale Background

Shopify has integrated AI into the workflow of their engineers, and the company offers engineers access to AI tools, including unlimited AI scalability, large language model systems, and other specialized tools to increase programmers' productivity.

### **How they use AI**

AI is used across the full software development lifecycle:

* Code generation and completion
* Writing and improving documentation
* Supporting general developer productivity

A fundamental change has occurred in the way employees are hired, where interviews in which AI is allowed are used to evaluate candidates based on how they use AI tools in their workflow to improve productivity, with the goal of the interview not being to allow AI to solve problems but rather to see how engineers can solve problems, design solutions, and effectively lead AI systems.  
By offering engineers strong AI support tools and by building sustainable Shopify tool systems, it has improved the speed of development and productivity for engineers, with benefits being fast development and shipping features, more accurate code generation through internal systems, and reduced 'token waste' through optimized tools.  
Despite the benefits, there are still significant concerns, mentioning that AI can generate incorrect code, repeat code, or generate outdated code that may have lost API context, or not all engineers will adapt equally well to AI assistants. Shopify treats AI as a collaborator and not as a replacement for engineers, but the developers still need to adapt and be able to plan solutions carefully, break down big problems, and guide AI to help rather than trust it blindly. (Thawar, 2025; Hello Interview, 2026 )

## 

Case Study 4: Duolingo — Going “AI-First”

Duolingo applies AI in various areas such as creating content for language learning materials, generating new language lessons, and supporting the workflows of engineers and developers, where one of the biggest achievements was the publication of 148 courses in different languages created by AI, which expanded their library in a very short time. Engineers are also involved in AI usage, where around 80% of engineers use AI tools in everyday life, and there are trainings and meetings every Friday where AI successes and failures are shared, and these meetings help distribute information across the teams.

The first use of AI led to significant increases in productivity, where output increased 4-5x while teams were the same size, no one was laid off, and hiring continued alongside AI. Project revenues for 2025 increased by over $1 billion, which is thought to have been related to investments in AI.

Despite the good results, the transition created problems and challenges where, for example, the first AI memo created public backlash and concerns about job losses, which later leaders said was a misunderstanding and taken out of context. Another problem was reducing contractors, increasing external concerns about the impact of system automation on them. There is also a trade-off between speed and quality, where leaders acknowledge that rapid AI integration can sometimes reduce quality.

Duolingo shows how an “AI-first” strategy can significantly increase productivity and content without reducing the number of employees, but it also shows that successful AI transformation is not just technical but relies on communication, trust, and quality management. (HR Grapevine, 2025; Shibu, 2025; IT Brew, 2025; Vanian, 2025 )



\##Cross-Company Analysis

&#x20;

| Company | Primary AI Use | Productivity Gain | Key Challenge |

|---|---|---|---|

| Microsoft/GitHub | Code generation, documentation | 55.8% faster coding | Skill atrophy, systemic risks |

| Google | Code completion, migrations, code review | Improved throughput | Amplifies weak practices too |

| Shopify | Code generation, hiring, custom tooling | Faster delivery | Requires engineers who can direct AI |

| Duolingo | Content creation, engineering workflows | 4–5x content output | Communication, contractor reduction |

&#x20;

\---

## Conclusion

Throughout all the studied cases, a clear form emerges where AI strengthens good workflows and productive teams, but it can make the process weaker and unclear practices more visible and inevitable. In the companies mentioned above, AI is not replacing software engineers, but rather just changing how their work looks, where engineers are supposed to plan and design systems, lead and manage AI tools, review and confirm AI-generated outputs, and make architectural and product-level decisions. Now engineers are not exactly trying to write every line of code themselves, but they become supervisors of AI.


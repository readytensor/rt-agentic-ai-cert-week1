![AAIDC- Tools of the Trade - hero.webp](AAIDC-%20Tools%20of%20the%20Trade%20-%20hero.webp)

--DIVIDER--

---

[⬅️ Previous - Real-World Applications](https://app.readytensor.ai/publications/EbfPXrWQMeCh)
[➡️ Next - Agents Vs. Workflows](https://app.readytensor.ai/publications/Xq3L2HSWLPou)

---

--DIVIDER--

# Tools and Frameworks

The field of Agentic AI offers a variety of tools and frameworks to build agents, from code-based solutions for developers to visual interfaces for non-coders.

---

## Code-Based Frameworks

For developers who want granular control over workflows, memory, and multi-agent collaboration:

1.  **LangGraph**  
     Developed by the team behind LangChain, LangGraph takes things further by letting you design AI workflows as _visual graphs_. Imagine building a customer support system where one agent handles initial queries, another escalates complex issues, and a third schedules follow-ups; all connected like nodes on a flowchart. It’s perfect for multi-step processes that need to "remember" where they are in a task.  
    🔗 [Docs](https://langchain-ai.github.io/langgraph/) | [GitHub](https://github.com/langchain-ai/langgraph)

2.  **Microsoft AutoGen**  
     AutoGen is Microsoft’s answer to collaborative AI. With Microsoft AutoGen, you can have a system where one agent writes code, another reviews it for errors, and a third tests the final script. These agents debate, self-correct, and even use tools like APIS or calculators. It is ideal for coding teams or research projects where multiple perspectives matter.  
    🔗 [Docs](https://microsoft.github.io/autogen/stable/) | [GitHub](https://github.com/microsoft/autogen)

3.  **CrewAI**  
     CrewAI organises agents into specialised roles, like a startup team. For example, a "Researcher" agent scours the web for data, a "Writer" drafts a report, and an "Editor" polishes it. They pass tasks back and forth, refining their work until it’s ready to ship with no micromanaging required.  
    🔗 [Docs](https://docs.crewai.com/introduction) | [GitHub](https://github.com/crewAIInc/crewAI)

4.  **LlamaIndex**  
     Formerly called GPT Index, LlamaIndex acts like a librarian for your AI agents. If you need your agent to reference a 100-page PDF, a SQL database, and a weather API, LlamaIndex is the framework to go to. It helps it fetch and connect data from all these sources, ensuring responses are informed and accurate.  
    🔗 [Docs](https://docs.llamaindex.ai/en/stable/) | [GitHub](https://github.com/run-llama/llama_index)

5.  **Pydantic AI**  
     This is one of my best frameworks for building Agents because it makes it very easy and allows you to have a structured output easily. It was built by the same people behind Pydantic. We will still dive deeper into it in the coming sections.
    🔗 [Docs](https://ai.pydantic.dev/) | [GitHub](https://github.com/pydantic/pydantic-ai)

6.  **OpenAI Swarm**  
     OpenAI’s experimental Swarm framework explores how lightweight AI agents can solve tasks collaboratively. One agent gathers data, another analyses it, and a third acts on it. It’s not ready for production yet but it's worth mentioning.
    🔗 [GitHub](https://github.com/openai/swarm)

---

## Visual (GUI) Frameworks

1.  **Rivet**  
     Rivet is like digital LEGO for AI. You just have to drag and drop nodes to connect ChatGPT to your CRM, add a "send email" action, and voilà, you’ve built an agent that auto-replies to customer inquiries. Perfect for business teams who want automation without coding.  
    🔗 [Website](https://rivet.ironcladapp.com/)

2.  **Vellum**  
     Vellum is the Swiss Army knife for prompt engineers. It allows you to test 10 versions of a prompt side-by-side, see which one gives the best results, and deploy it to your agent, all through a clean interface. It’s like A/B testing for AI workflows.  
    🔗 [Website](https://www.vellum.ai/)

3.  **Langflow**  
     Langflow is the drag-and-drop alternative to LangChain. You can just drag a "web search" node into your workflow, link it to a "summarize" node, and watch your agent turn a 10-article search into a crisp summary. It is great for explaining AI logic to your CEO.  
    🔗 [Website](https://www.langflow.org/)

4.  **Flowise AI**  
     Flowise AI is the open-source cousin of Langflow. You can use it to build a chatbot that answers HR questions by just linking your company handbook to an LLM—no coding, just drag, drop, and deploy.  
    🔗 [Website](https://flowiseai.com/)

5.  **Chatbase**  
     Chatbase lets you train a ChatGPT-like assistant on your own data. Upload your FAQ PDFs, tweak the design to match your brand, and embed them on your website. It’s like having a 24/7 customer service rep who actually reads the manual.  
    🔗 [Website](https://www.chatbase.co/)

---

--DIVIDER--

# Factors for choosing a Framework

**1. Use Case**: What's your agent's primary purpose? Different frameworks excel at different tasks.

**2. Level of Abstraction:** Do you want full control over prompts, memory, and workflows, or a higher-level framework that handles those under the hood?

**3. Criticality**: Is this a mission-critical system? Choose battle-tested tools for essential applications.

**4. Team Skills**: Do you have Python experts, or would no-code tools be more appropriate?

**5. Time/Budget**: Need a quick solution or have resources for a more custom approach?

**6. Integration Requirements**: Will you need to connect with external systems like Slack, Jira, etc.?

**7. Scalability Considerations**: Think about monitoring, logging, and auto-scaling if you'll serve many users.

---

--DIVIDER--

# 🎥 A Perspective on Picking the Right Framework

Watch this short video to clarify how to approach framework choices in Agentic AI, whether you're building a quick personal project or laying the foundation for long-term enterprise code.

You’ll explore how personal projects benefit from speed and flexibility, while company decisions demand maturity, support, and long-term thinking. Featuring real examples from industry and startup experience.

:::youtube[Title]{#bzz_VGmOwfo}

--DIVIDER--

---

[⬅️ Previous - Real-World Applications](https://app.readytensor.ai/publications/EbfPXrWQMeCh)
[➡️ Next - Agents Vs. Workflows](https://app.readytensor.ai/publications/Xq3L2HSWLPou)

---

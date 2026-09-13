Agentic AI Interview Preparation — Complete Syllabus & Question Bank

A practical interview-focused guide covering fundamentals, architecture, tools, memory, RAG, multi-agent systems, MCP, Azure, .NET, security, evaluation, production and scenario-based questions.

1. AI, GenAI and Agentic AI Fundamentals
• What is AI, ML, Deep Learning, Generative AI and Agentic AI?
• What is the difference between a traditional AI application and a GenAI application?
• What is the difference between an LLM application, an AI assistant, an AI agent and an agentic system?
• What exactly makes a system agentic?
• What is an AI agent?
• What are the core components of an AI agent?
• What is the agent loop?
• Explain perception → reasoning → planning → action → observation.
• What is autonomous vs semi-autonomous AI?
• When should you use an agent instead of a deterministic workflow?
• What are the advantages and disadvantages of Agentic AI?
• What are common real-world use cases for Agentic AI?
• When should you NOT use Agentic AI?
2. LLM Fundamentals Required for Agents
• What is an LLM?
• What is a foundation model?
• What are tokens?
• What is a context window?
• What are parameters?
• What is inference?
• What is training vs fine-tuning?
• What is temperature?
• What are top-p and top-k?
• What are embeddings?
• What is attention?
• What is self-attention?
• What is a Transformer?
• Encoder vs decoder vs encoder-decoder models?
• What causes hallucination?
• Why do LLMs sometimes produce different answers for the same input?
• What is structured output and why is it useful for agents?
3. Agent Architecture
• Design a basic AI agent architecture.
• What is the role of the LLM in an agent?
• What is an orchestrator?
• What is a planner?
• What is an executor?
• What is an agent state?
• What is short-term memory?
• What is long-term memory?
• What is working memory?
• How does an agent maintain context across multiple steps?
• How does an agent decide when to stop?
• How do you prevent an agent from entering an infinite loop?
• How do you handle maximum iterations?
• How do you design retry and timeout policies for agents?
• How do you make agent actions idempotent?
• How do you persist agent state?
4. Tool Calling and Function Calling
• What is function calling?
• What is tool calling?
• How does an LLM decide which tool to call?
• How do you define a tool schema?
• How does your application execute the tool?
• Does the LLM directly call your database/API?
• How do you validate tool arguments?
• What happens if a tool returns an error?
• How do you implement retries?
• How do you handle tool timeouts?
• How do you prevent dangerous tool calls?
• How do you handle duplicate tool execution?
• How do you audit tool calls?
• How would you expose a .NET API as an agent tool?
• How would you allow an agent to query SQL safely?
5. Planning and Reasoning
• What is planning in Agentic AI?
• Planning vs reasoning vs execution?
• What is task decomposition?
• What is ReAct?
• What is plan-and-execute?
• What is reflection/self-critique?
• What is chain-of-thought and why should applications generally avoid exposing private reasoning?
• How can an agent recover when a plan fails?
• How do you constrain an agent's reasoning?
• When should planning be deterministic rather than LLM-driven?
• How do you evaluate whether an agent's plan is good?
6. Agent Patterns
• Single-agent architecture
• Router agent
• Supervisor agent
• Planner-executor pattern
• Reflection pattern
• Evaluator-optimizer pattern
• Sequential workflow
• Parallel workflow
• Human-in-the-loop workflow
• Event-driven agent architecture
• State-machine-based agent
• Hierarchical agents
• Multi-agent collaboration
• Debate/critic pattern
• Manager-worker pattern
• For each pattern: explain when to use it, trade-offs, failure modes and an example.
7. Multi-Agent Systems
• What is a multi-agent system?
• When should you use multiple agents instead of one?
• How do agents communicate?
• Shared state vs message-based communication?
• Supervisor vs peer-to-peer agents?
• How do you assign responsibilities to agents?
• How do you prevent agents from duplicating work?
• How do you prevent circular communication?
• How do you handle agent failures?
• How do you trace a multi-agent workflow?
• How do you control cost in multi-agent systems?
• Design a multi-agent system for research, document analysis or customer support.
8. Memory
• What is memory in an AI agent?
• Short-term vs long-term memory?
• Conversation memory vs semantic memory?
• Episodic vs semantic memory?
• How do you store memories?
• When should you use a vector database for memory?
• When should you use SQL/Redis instead?
• How do you retrieve relevant memories?
• How do you prevent irrelevant memories from polluting context?
• How do you handle memory deletion and privacy?
• How do you control memory growth?
• How do you summarize long conversations?
9. RAG for Agentic AI
• What is RAG?
• Why does an agent need RAG?
• RAG vs fine-tuning?
• Explain the complete RAG pipeline.
• What is document ingestion?
• What is chunking?
• How do you choose chunk size and overlap?
• What are embeddings?
• What is a vector database?
• What is semantic search?
• What is hybrid search?
• What is reranking?
• What is metadata filtering?
• What is query rewriting?
• What is contextual retrieval?
• What is multi-query retrieval?
• How do you prevent irrelevant documents from reaching the LLM?
• How do you reduce hallucinations in RAG?
• How do you evaluate RAG quality?
• How does an agent decide when to use RAG?
• Design an agentic RAG system.
10. MCP — Model Context Protocol
• What is MCP?
• Why was MCP introduced?
• What problem does MCP solve?
• What are MCP hosts, clients and servers?
• What are MCP tools?
• What are MCP resources?
• What are MCP prompts?
• How does an MCP client communicate with an MCP server?
• MCP vs traditional function calling?
• MCP vs REST API?
• How would you build an MCP server?
• How would you connect a .NET application to an MCP server?
• How would you secure an MCP server?
• What are the risks of giving an agent access to many MCP tools?
• How would you use MCP with databases, GitHub, files or email?
11. Azure Agentic AI
• What Azure services can be used to build Agentic AI systems?
• What is Azure OpenAI?
• What is Azure AI Foundry?
• How would you build an agent using Azure services?
• What is Azure AI Search?
• How does Azure AI Search support RAG?
• How would you use Azure Functions as agent tools?
• How would you use Azure Service Bus in an agent workflow?
• When would you use Service Bus vs synchronous HTTP?
• How would you use Azure Storage for agent state?
• How would you use Cosmos DB?
• How would you use Redis?
• How would you secure Azure OpenAI?
• What is Microsoft Entra ID?
• How do managed identities help?
• How do you manage secrets with Azure Key Vault?
• How would you monitor an agent using Azure Monitor/Application Insights?
• How would you deploy an agent on AKS?
• How would you design an Azure architecture for 1M agent requests?
12. .NET Implementation
• How would you build an AI agent in ASP.NET Core?
• How do you call an LLM from .NET?
• How do you implement streaming responses?
• How do you implement tool/function calling?
• How do you register tools using dependency injection?
• How do you manage agent state?
• How do you implement retries using Polly?
• How do you handle cancellation tokens?
• How do you handle concurrent agent executions?
• How do you use async/await correctly in agent applications?
• How do you persist conversation state?
• How do you implement background agent processing?
• How would you use Azure Service Bus with a .NET agent?
• How would you expose internal .NET services as agent tools?
• How do you test an agent application?
13. Security and Responsible AI
• What are the major security risks in Agentic AI?
• What is prompt injection?
• What is indirect prompt injection?
• What is data exfiltration through an agent?
• What is tool poisoning?
• What is excessive agency?
• How do you implement least privilege for agents?
• How do you validate tool inputs?
• How do you restrict tools by user/role?
• How do you protect sensitive customer data?
• How do you prevent an agent from sending unauthorized emails or transactions?
• When should human approval be mandatory?
• How do you implement PII protection?
• How do you prevent secrets from entering prompts?
• How do you secure RAG documents?
• How do you implement tenant isolation?
• How do you audit agent decisions and actions?
• What are guardrails?
• Input guardrails vs output guardrails vs tool guardrails?
14. Reliability, Scalability and Production
• How do you make an agent production-ready?
• What are the main failure modes of agents?
• How do you handle LLM downtime?
• How do you implement fallback models?
• How do you handle rate limits?
• How do you handle transient Azure/API failures?
• How do you cache agent responses?
• When is caching unsafe?
• How do you control token consumption?
• How do you control latency?
• How do you handle concurrent requests?
• How do you scale agent workers?
• How do you design asynchronous agents?
• How do you implement circuit breakers?
• How do you implement dead-letter queues?
• How do you maintain idempotency?
• How do you monitor cost per agent task?
15. Observability and Evaluation
• What should you log for an AI agent?
• How do you trace an agent across multiple tool calls?
• What is distributed tracing?
• What metrics would you monitor?
• Latency, token usage, cost, tool success rate, failure rate and task completion rate?
• How do you evaluate hallucination?
• How do you evaluate RAG retrieval quality?
• What are precision, recall and relevance in retrieval?
• What is groundedness?
• What is answer correctness?
• What is an evaluation dataset?
• Offline vs online evaluation?
• How do you perform regression testing for an LLM application?
• How do you detect prompt/model changes that degrade quality?
• How do you evaluate an autonomous agent?
16. Prompt Engineering for Agents
• What is a system prompt?
• System vs user vs developer instructions?
• What makes a good agent system prompt?
• How do you define tool-use instructions?
• How do you constrain an agent?
• What is few-shot prompting?
• What is zero-shot prompting?
• What is prompt injection?
• How do you separate trusted instructions from untrusted retrieved content?
• How do you version prompts?
• How do you test prompts?
• Prompt engineering vs fine-tuning?
17. Human-in-the-Loop
• What is human-in-the-loop?
• When should an agent ask for approval?
• How do you design approval workflows?
• What actions should always require approval?
• How do you handle approval timeout?
• How do you resume an agent after approval?
• How do you audit approvals?
• Design a financial/tax/accounting agent with human approval.
18. Agentic AI vs Alternatives
• Agent vs workflow
• Agent vs microservice
• Agent vs chatbot
• Agent vs RAG
• Agent vs fine-tuned model
• Agent vs traditional automation/RPA
• Agent vs API orchestration
• LLM-based planner vs deterministic state machine
• When is an agent overengineering?
19. System Design Questions
• Design an AI customer-support agent.
• Design an agent that reads documents and answers questions.
• Design an agentic RAG platform for enterprise documents.
• Design a research agent that searches multiple sources and produces a report.
• Design an agent that reads emails and creates tasks.
• Design an invoice-processing agent.
• Design a tax research assistant.
• Design a financial compliance agent.
• Design a multi-agent software development assistant.
• Design an agent that uses SQL, APIs and RAG.
• Design an agent platform serving millions of users.
• Design a secure enterprise agent platform with tenant isolation.
• For each design: explain components, data flow, APIs, state, queues, storage, security, observability, failure handling, scalability and cost.
20. Scenario-Based Interview Questions
• An agent keeps calling the same tool repeatedly. How do you fix it?
• The LLM generates invalid JSON. What do you do?
• The agent hallucinates despite RAG. How do you troubleshoot?
• Retrieval returns irrelevant documents. What would you change?
• Agent latency is 15 seconds. How would you reduce it?
• LLM costs have increased 5x. How would you control cost?
• A tool API is down. How should the agent behave?
• Two agents disagree. How do you resolve the result?
• An agent sends an email without approval. How would you prevent this?
• A malicious document contains instructions telling the agent to leak secrets. What happens and how do you defend against it?
• The same payment/transaction is executed twice. How do you prevent it?
• Users from tenant A can retrieve tenant B documents. How do you fix it?
• Your vector database is unavailable. What is your fallback?
• The model provider changes behavior after an upgrade. How do you detect it?
• How would you migrate from one LLM provider to another?
• How would you roll out a new agent safely?
21. Practical Project Questions
• Explain an Agentic AI project you have built.
• What business problem did the agent solve?
• Why did you choose an agent instead of a normal workflow?
• What tools did the agent use?
• How did you implement RAG?
• How did you manage state?
• How did you handle failures?
• How did you secure the system?
• How did you evaluate the agent?
• What was the biggest production challenge?
• What would you redesign if you built it again?
• How did you monitor cost and latency?
• How did you handle hallucination?
• How did you handle prompt injection?
• How did you implement human approval?
22. Questions You Should Be Able to Answer Without Memorizing
• Explain Agentic AI to a non-technical person in 30 seconds.
• Explain an agent to a backend developer.
• Explain the difference between RAG and Agentic RAG.
• Explain how an LLM chooses a tool.
• Explain the complete lifecycle of an agent request.
• Draw an agent architecture on a whiteboard.
• Design one agent using .NET and Azure.
• Explain one production failure and how you would recover from it.
• Explain the security model of an enterprise agent.
• Explain when you would reject Agentic AI and use deterministic code instead.
Recommended Preparation Order
1. Agentic AI fundamentals and agent loop

2. LLM fundamentals

3. Tool/function calling

4. Planning and agent patterns

5. RAG + Agentic RAG

6. Memory and state

7. MCP

8. Azure architecture

9. .NET implementation

10. Security and guardrails

11. Reliability, scalability and observability

12. System design and scenario questions


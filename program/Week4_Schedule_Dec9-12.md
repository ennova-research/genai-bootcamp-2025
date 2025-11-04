# 🧠 Generative AI Bootcamp – Week 4
**Dates:** December 9–12, 2025 (Tuesday–Friday)  
**Theme:** *Generative AI Paradigms (II): LLM Agents & Tool Use*  
**Goal:** Develop autonomous AI agents using LangChain, LangGraph, and tool-invocation frameworks. Learn memory management, MCP-based communication, and agent evaluation.  
**Format:** Six 1-hour sessions per day, alternating between **theoretical** and **practical**.  

---

## **Day 1 – Tuesday, December 9**  
**Theme:** *From LLMs to Agents*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **LLMs as Agents: Concepts and Motivation** | Distinguish LLMs as reasoning engines vs. autonomous agents. Introduce routing, planning, and tool use paradigms. |
| **10:45–11:45** | Practical | **Agent Warm-Up Lab** | Build a minimal Python agent loop (prompt → response → action → memory). Use LangChain core components. |
| **12:00–13:00** | Theoretical | **Agent Architectures & Frameworks** | Compare LangChain, LangGraph, CrewAI, and AutoGen. Discuss multi-step reasoning and task decomposition. |
| **14:30–15:30** | Practical | **LangChain Agents Lab 1: Tool Definition & Invocation** | Implement tools for search, calculation, and file reading. Connect via LLM chains and analyze tool calls. |
| **15:45–16:45** | Theoretical | **Routing and Query Analysis** | Learn how agents parse user intents and select tools. Study router chains and decision graphs. |
| **17:00–18:00** | Practical | **LangGraph Router Lab** | Design a multi-route graph for query classification and tool selection using LangGraph. |

---

## **Day 2 – Wednesday, December 10**  
**Theme:** *Memory and Context in Agents*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **Memory Models for LLM Agents** | Explore types of memory: buffer, summary, vector, and episodic. Learn context persistence strategies. |
| **10:45–11:45** | Practical | **Memory Integration Lab** | Implement short-term and long-term memory modules with LangChain `ConversationBufferMemory` and FAISS stores. |
| **12:00–13:00** | Theoretical | **Tool Use Patterns and Orchestration** | Examine Retriever–Writer–Reviewer and ReAct patterns for multi-tool coordination. |
| **14:30–15:30** | Practical | **ReAct Agent Implementation Lab** | Build a ReAct-style agent combining reasoning steps and tool invocations for multi-hop tasks. |
| **15:45–16:45** | Theoretical | **Model Context Protocol (MCP)** | Introduce MCP standards for agent-to-agent communication and tool discovery protocols. |
| **17:00–18:00** | Practical | **MCP Demo Lab** | Simulate two agents communicating via a shared context protocol; exchange queries and responses. |

---

## **Day 3 – Thursday, December 11**  
**Theme:** *Multi-Agent Systems and Evaluation*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **Designing Multi-Agent Workflows** | Study collaborative and hierarchical agent structures (e.g., Manager → Worker). |
| **10:45–11:45** | Practical | **Multi-Agent Collaboration Lab** | Implement a Manager–Reviewer system where agents divide and validate tasks. |
| **12:00–13:00** | Theoretical | **Evaluation of Agent Reasoning** | Learn traceability, chain-of-thought logging, and self-critique methods. |
| **14:30–15:30** | Practical | **Agent Evaluation Lab** | Use LangSmith or custom logging to analyze agent decisions and tool use accuracy. |
| **15:45–16:45** | Theoretical | **Scaling Agents & Ethical Concerns** | Discuss looping failures, tool misuse, and autonomy boundaries. Introduce guardrail strategies. |
| **17:00–18:00** | Practical | **Mini Challenge: Traceable Agent Pipeline** | Build an agent workflow with trace visualization and error reporting. |

---

## **Day 4 – Friday, December 12**  
**Theme:** *Applied Agent Systems & Capstone Preparation*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **Enterprise Use Cases for Agents** | Explore real-world applications: customer support, data retrieval, and code assistants. |
| **10:45–11:45** | Practical | **Agent Integration Lab** | Connect agents with external APIs (Google Search, BigQuery, Watson X) through LangChain tools. |
| **12:00–13:00** | Theoretical | **Designing End-to-End Agentic Systems** | Architect RAG + Agent + Tool chains with evaluation loops. Plan deployment for Week 5. |
| **14:30–15:30** | Practical | **Capstone Kickoff: Agent Blueprints** | Define use-cases and design blueprints for cloud deployment next week. |
| **15:45–16:45** | Theoretical | **Best Practices & Failure Modes** | Summarize lessons from Weeks 1–4. Discuss debugging and observability for agents. |
| **17:00–18:00** | Practical | **Showcase: Autonomous Agent Demo** | Present a functioning LLM agent demonstrating tool use, memory, and evaluation features. Peer review session. |

---

### ✅ **Outcomes by End of Week 4**
- Ability to **design and deploy autonomous LLM agents**  
- Hands-on experience with **LangChain, LangGraph, and MCP**  
- Understanding of **memory models, multi-agent coordination, and traceability**  
- Prototype of an **LLM agent workflow** ready for cloud deployment in Week 5  

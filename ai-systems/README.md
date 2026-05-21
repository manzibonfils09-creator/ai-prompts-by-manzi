# 🤖 AI Systems Prompts

Prompts for prompt engineering, agent design, automation logic, and LLM workflows.

---

## 1. System Prompt — Custom AI Agent

**When to use:** Building a custom AI agent for a client or internal tool.

```
You are [agent name], an AI assistant for [company/use case].
Your job is to [primary function].
You always [key behavior 1].
You never [key behavior 2].
When you don't know something, you [fallback behavior].
Tone: [professional / casual / warm / direct].
Always respond in [language].
```

---

## 2. Workflow Automation Brief

**When to use:** Designing an n8n or Make.com automation from scratch.

```
Act as an automation architect.
Design a workflow for the following use case: [describe the task].
List the trigger, each step, the tools/APIs involved, and the output.
Identify potential failure points and how to handle them.
Keep it practical — assume I'll build this in n8n.
```

---

## 3. Prompt Refinement

**When to use:** You have a prompt that's not giving great results.

```
Here is a prompt I'm using: [paste your prompt]
Here is what I'm getting: [paste the output]
Here is what I actually want: [describe ideal output]
Rewrite the prompt to get better results.
Explain what you changed and why.
```

---

## 4. Multi-Agent Architecture Design

**When to use:** Planning a system with multiple AI agents working together.

```
Act as an AI systems architect.
Design a multi-agent system for: [describe the problem].
Define each agent's role, inputs, outputs, and how they hand off to each other.
Identify which agent is the orchestrator.
Suggest which LLMs or tools are best suited for each agent.
Keep it implementable — not theoretical.
```

---

## 5. RAG System Design

**When to use:** Building a retrieval-augmented generation system for a client.

```
Act as an AI engineer.
Design a RAG (Retrieval-Augmented Generation) system for [use case].
Specify: document ingestion strategy, chunking approach, embedding model, vector DB, retrieval method, and prompt structure.
Optimize for [accuracy / speed / cost].
Assume the tech stack is: [your stack].
```

---

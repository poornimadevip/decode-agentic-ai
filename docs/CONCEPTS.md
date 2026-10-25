# Concepts and Terminology

## Concepts

| Concept | Meaning | Example |
|---|---|---|
| Agentic AI | AI systems that can plan, act, and complete tasks with some autonomy. | An assistant breaks a project into steps and uses tools to finish it. |
| Large Language Model (LLM) | A model trained on large text data to understand and generate human language. | GPT-style models used for reasoning and writing. |
| Prompt | The instruction or question sent to the model. | "Summarize this document in 3 bullet points." |
| Context Window | The amount of information the model can consider in one interaction. | The current conversation plus recent files and instructions. |
| Tool Calling | When an agent invokes external capabilities such as search, code execution, or APIs. | Looking up a file or running a command. |
| Retrieval-Augmented Generation (RAG) | Combining a model with document retrieval to ground responses in data. | Asking a model to answer using a knowledge base. |
| Planning | Breaking a task into smaller steps to achieve a goal efficiently. | Deciding which tasks to do first in a project. |
| Memory | Stored context that helps an agent recall important information over time. | Remembering a user preference across sessions. |
| Workflow | A predefined sequence of steps for a task. | A CI/CD pipeline. |
| Agent | A system that can make decisions and take actions based on goals and tools. | A coding agent that edits files and tests code. |
| Multi-Agent System | Multiple agents working together on different tasks or roles. | One agent for research and another for implementation. |
| Guardrails | Safety constraints and checks to keep AI behavior aligned and reliable. | Limiting actions to approved tools and validating outputs. |
| Evaluation | Measuring if the AI system is performing correctly or meeting expectations. | Comparing generated answers to a quality rubric. |

This table gives a quick view of the main concepts used in agentic AI and related workflows.

## Terminology

| Term | What it is |
|---|---|
| LangChain | A framework for building applications powered by Large Language Models, connecting them with tools, data sources and memory |
| LangGraph | Built on top of LangChain. Allows you to design AI workflows as graph, enabling agents to plan, loop, branch and make decisions dynamically|
| Databricks | Cloud native data and AI platform that provides a unified workspace for data engineering, machine learning and analytics workloads| 
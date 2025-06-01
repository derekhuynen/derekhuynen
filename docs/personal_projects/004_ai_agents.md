# Dual-Agent LLM System

## Role

**Solo Developer**

## Project Description

A C# application demonstrating multi-agent LLM collaboration using Azure Functions and Semantic Kernel. The system features two specialized AI agents working together to solve complex tasks through a coordinated workflow, leveraging Azure OpenAI models for research and writing.

## Project Timeline

- **Start Date:** 2025-05-11
- **End Date:** 2025-05-12

## Team Size

1

## Client

Personal

## Keywords

Azure OpenAI, Semantic Kernel, Azure Functions, C#, Multi-Agent, LLM, GPT-4o, GPT-4.1, Research, Content Generation, Plugins

---

## Tech Stack

- **Backend:** C# (.NET 8), Azure Functions
- **AI:** Azure OpenAI (gpt-4o, gpt-4.1)
- **Framework:** Semantic Kernel
- **Other:** Extensible plugin system

---

## Full Description

The Dual-Agent LLM System is a modular C# solution that showcases advanced multi-agent collaboration for AI-powered research and content generation. It uses Azure Functions as an HTTP API entry point, orchestrates two specialized agents (Research and Writing) via Semantic Kernel, and integrates with Azure OpenAI for both fast research (gpt-4o) and high-quality writing (gpt-4.1). The architecture is extensible, supporting custom plugins and new agent types for domain-specific workflows.

**Repository:** [github.com/derekhuynen/AI_Agents](https://github.com/derekhuynen/AI_Agents)

---

## What I Worked On

- Designed and implemented the dual-agent architecture and workflow.
- Developed Azure Functions for API access and agent coordination.
- Integrated Semantic Kernel for robust LLM orchestration.
- Built Research and Writing agents using different Azure OpenAI deployments.
- Enabled extensibility with a plugin system and agent interface abstraction.
- Authored documentation and setup instructions for local and cloud deployment.

---

## Challenges & Solutions

- **Challenge:** Coordinating multiple agents with different LLM deployments and roles.
  - **Solution:** Used Semantic Kernel and a clear agent interface for modular orchestration.
- **Challenge:** Ensuring high-quality, contextually relevant content output.
  - **Solution:** Implemented a research-to-writing pipeline with structured data handoff.
- **Challenge:** Supporting extensibility for future agent and plugin additions.
  - **Solution:** Designed the system with interfaces and plugin support for easy expansion.

---

## Key Takeaways

- Gained experience with multi-agent LLM systems and orchestration patterns.
- Improved skills in Azure Functions, Semantic Kernel, and Azure OpenAI integration.
- Learned best practices for modular, extensible AI backend solutions.
- Built a foundation for advanced content generation and knowledge workflows.

---

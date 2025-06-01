# AI RAG Demo Solution

## Role

**Solo Developer**

## Project Description

A modular Retrieval-Augmented Generation (RAG) demo solution built with C#, Semantic Kernel, Azure OpenAI, and Azure Functions. The project demonstrates a modern, agent-based approach to conversational AI, project ingestion, and hybrid search using Azure AI Search.

## Project Timeline

- **Start Date:** 2025-05-17
- **End Date:** 2025-05-18

## Team Size

1

## Client

Personal

## Keywords

RAG, Azure OpenAI, Semantic Kernel, Azure Functions, C#, AI Search, Conversational AI, Hybrid Search, Agent Architecture

---

## Tech Stack

- **Backend:** C# (.NET 8), Azure Functions (Isolated Worker)
- **AI:** Semantic Kernel, Azure OpenAI
- **Search:** Azure AI Search (pluggable)
- **Other:** Modular agent architecture, DTOs, and shared interfaces

---

## Full Description

The AI RAG Demo Solution is a comprehensive demonstration of Retrieval-Augmented Generation (RAG) using a modular, agent-based architecture. The backend is organized into several projects: core AI logic and agent orchestration (AIServices), an Azure Function API for chat (RagChatBotAPI), a document ingestion and embedding generation function (DocumentIngestion), and shared DTOs/interfaces (Shared). The solution leverages Semantic Kernel for orchestrating LLM calls and agent workflows, Azure OpenAI for both embeddings and completions, and Azure AI Search for hybrid search scenarios. Example project data is provided for ingestion and testing.

**Repository:** [github.com/derekhuynen/AI_RAG](https://github.com/derekhuynen/AI_RAG)

---

## What I Worked On

- Designed and implemented modular agent architecture for RAG workflows.
- Developed Azure Functions for chat API and document ingestion.
- Integrated Semantic Kernel for LLM orchestration and agent coordination.
- Connected Azure OpenAI for embeddings and completions.
- Enabled hybrid search with Azure AI Search.
- Authored documentation and setup instructions for each project component.

---

## Challenges & Solutions

- **Challenge:** Orchestrating multiple agents and services for flexible RAG workflows.
  - **Solution:** Leveraged Semantic Kernel and modular service interfaces for extensibility.
- **Challenge:** Efficiently ingesting and embedding large project datasets.
  - **Solution:** Built a dedicated Azure Function for bulk ingestion and embedding generation.
- **Challenge:** Supporting hybrid search and pluggable search backends.
  - **Solution:** Designed the system to be search-provider agnostic with clear interfaces.

---

## Key Takeaways

- Gained experience with advanced RAG architectures and agent-based design.
- Improved skills in Azure Functions, Semantic Kernel, and Azure OpenAI integration.
- Learned best practices for modular, extensible backend solutions in conversational AI.
- Built a foundation for future enhancements, such as multi-modal search and analytics.

---

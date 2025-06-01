# GenAI ChatBot

## Role

**AI Developer**

## Project Description

GenAI-powered chatbot for internal staff at a major gas and electric company, providing conversational access to regulatory documents, internal articles, and claims reports. Includes chat history, citations, and advanced Retrieval Augmented Generation (RAG) workflows.

## Project Timeline

- **Start Date:** 2024-11-04
- **End Date:** 2024-12-20

## Team Size

4–5

## Client

Gas and Electric Company

## Keywords

GenAI, RAG, Chatbot, Regulatory Compliance, Azure OpenAI, Semantic Search, Citations, Document Automation, Utilities, Enterprise AI

---

## Tech Stack

- **Frontend:** React, Tailwind, Redux
- **Backend:** C#, .NET, Azure Functions, Semantic Kernel, WebSocket (streaming), TypeScript
- **Database:** Azure CosmosDB (NoSQL), Azure PostgresDB
- **Other:** Azure App Service, Azure API Gateway, Azure API Management, Azure Private Endpoints, Azure Event Hub, Azure AI Search, Azure OpenAI, Azure DevOps

---

## Full Description

GenAI ChatBot is an enterprise-grade AI chatbot developed for internal use at a Gas and Electric Company. The system ingests, chunks, and vectorizes both internal documents (claims reports, articles) and government regulatory materials. All data is indexed in Azure AI Search, enabling semantic retrieval and conversational queries with real-time citations and references.

The chatbot leverages RAG architecture to provide grounded, reliable responses by retrieving the most relevant content and combining it with generative answers from Azure OpenAI models. Staff can ask about specific regulatory changes, cross-reference policies, and verify compliance directly within the chat interface. Key features include chat history, accurate citations, and the ability to "redline" internal documents by matching them to up-to-date regulations.

The backend, built in C# with .NET and Semantic Kernel, streams responses to a modern React frontend via WebSockets for real-time interactivity. Azure Functions support additional processing, including managing pub/sub messaging and background document ingestion. Robust API management and private endpoints ensure secure access and integration across the enterprise.

---

## What I Worked On

- Led the ingestion and vectorization of internal claims reports and regulatory documents, including data chunking and metadata extraction.
- Developed and optimized the RAG workflow, combining Azure AI Search with Azure OpenAI for context-aware answers.
- Implemented citation and reference mechanisms for transparent, traceable responses in the chat interface.
- Integrated Semantic Kernel with C#/.NET for advanced orchestration of AI and retrieval flows.
- Designed and supported chat history management and user context handling via Azure PostgresDB and CosmosDB.
- Supported the build-out of a streaming chat interface using React, Redux, and WebSockets.
- Assisted with API gateway, private endpoint setup, and Azure DevOps pipelines for enterprise deployment.

---

## Challenges & Solutions

- **Challenge:** Combining regulatory and internal data for accurate, context-rich responses.
  - **Solution:** Built multi-index RAG pipelines and fine-tuned metadata handling for effective filtering, retrieval, and grounding.
- **Challenge:** Ensuring reliability, transparency, and traceability of AI-generated responses.
  - **Solution:** Implemented real-time citations, integrated chat history, and enabled audit trails for regulatory compliance.
- **Challenge:** Delivering a scalable, secure solution within a large enterprise environment.
  - **Solution:** Leveraged Azure API Management, private endpoints, and role-based access control; built robust streaming and background processing workflows.

---

## Key Takeaways

- Deepened expertise in large-scale RAG architectures and enterprise AI chatbot solutions.
- Gained practical experience in metadata-driven search optimization and semantic query workflows.
- Improved understanding of integrating AI, retrieval, and compliance in highly regulated industries.
- Enhanced skills in secure, cloud-native solution delivery using advanced Azure services and DevOps best practices.
- Recognized the importance of citations, transparency, and data traceability in critical enterprise AI applications.

---

## Links / Demo / Repo

- N/A

---

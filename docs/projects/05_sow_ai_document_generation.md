# SOW AI Document Generation

## Role

**Lead, AI Developer, Architect**

## Project Description

Proof of concept leveraging AI to generate Statement of Work (SOW) documents from user-uploaded files and structured templates.

## Project Timeline

- **Start Date:** 2024-03-11
- **End Date:** 2024-03-29

## Team Size

1

## Client

Internal, POC

## Keywords

AI, SOW Generation, Document Automation, LLM, Azure OpenAI, Document Processing, Proof of Concept, React, Node.js

---

## Tech Stack

- **Frontend:** React, Tailwind, React Hook Form, React Query, Zustand, Typescript
- **Backend:** Node.js, Azure Functions
- **Database:** CosmosDB (NoSQL)
- **Other:** Azure OpenAI, Zod, Azure Static Web App, Azure Blob Storage, Azure Storage Queues

---

## Full Description

The SOW Document Generation with AI project is an internal proof of concept created to streamline and automate the process of generating Statement of Work documents. Users upload various supporting documents for a sales engagement—including client information, meeting notes, and call transcripts—via a React-based web interface.

Uploaded files are processed, stored in CosmosDB, and then passed through a workflow that leverages Azure OpenAI's large language models. These models analyze the source material and generate structured SOW sections according to strict company formats. The generated content is then compiled into both PDF and Word documents, which are automatically sent to the sales agent leading the engagement.

The backend utilizes Azure Functions for event-driven processing, including blob storage triggers and queue-based workflows. The proof of concept demonstrates the feasibility of end-to-end document automation using AI, and highlights lessons learned in prompt engineering, document parsing, and scalable architecture.

---

## What I Worked On

- Solely architected and developed the entire solution from frontend to backend.
- Built a React web interface for document uploads and workflow management, styled with Tailwind CSS.
- Developed backend services in Node.js with Azure Functions to handle file processing, data storage, and integration with Azure OpenAI.
- Designed and implemented data flows to CosmosDB and Azure Blob Storage, leveraging queues and triggers for automation.
- Engineered AI prompts and workflows for generating SOW content sections from diverse, unstructured documents.
- Automated PDF and Word document generation and email delivery to end users.
- Documented architecture and processes for internal stakeholders and future iterations.

---

## Challenges & Solutions

- **Challenge:** Parsing and processing diverse, unstructured documents for AI input.
  - **Solution:** Built robust file handling and preprocessing with Azure Blob Storage, storage queues, and custom Node.js logic.
- **Challenge:** Generating accurate, formatted SOW sections using large language models.
  - **Solution:** Iterated on prompt engineering and document templates to maximize consistency and quality of outputs.
- **Challenge:** Automating document creation and delivery end-to-end.
  - **Solution:** Leveraged Azure Functions to orchestrate file ingestion, AI processing, PDF/Word generation, and email notifications.

---

## Key Takeaways

- Developed hands-on expertise in AI-driven document generation and prompt engineering with Azure OpenAI.
- Gained experience architecting scalable, event-driven workflows using Azure serverless technologies.
- Improved skills in end-to-end application delivery, including file storage, processing, and automated communications.
- Demonstrated ability to rapidly deliver proof of concept projects with significant business impact potential.

---

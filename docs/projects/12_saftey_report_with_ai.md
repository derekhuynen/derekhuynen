# Safety Report Generation with AI

## Role

**AI Developer**

## Project Description

Process and ingest PDF documents using RAG patterns to enable an AI-powered chatbot and automated generation of safety reports in a strict, standardized format.

## Project Timeline

- **Start Date:** 2025-03-10
- **End Date:** 2025-03-31

## Team Size

4

## Client

IBM (POC)

## Keywords

Safety Reports, RAG, PDF Ingestion, AI Chatbot, Document Intelligence, Azure OpenAI, OCR, Vector Search, Automation

---

## Tech Stack

- **Frontend:** React, Tailwind, Typescript, Material UI
- **Backend:** Azure Function, Node.js, Typescript
- **Database:** Azure CosmosDB (NoSQL)
- **Other:** Azure Document Intelligence (OCR), Azure OpenAI, Azure AI Search, Azure Blob Storage

---

## Full Description

The Safety Report Generation with AI project was a proof of concept engagement in partnership with IBM, aimed at automating the extraction and analysis of safety-related content from PDF documents. The system utilizes Azure Document Intelligence (OCR) to extract structured text from incoming PDFs. Extracted text is chunked and vectorized, then stored in Azure AI Search to support retrieval-augmented generation (RAG) and chatbot functionality.

A key deliverable was generating detailed safety reports from ingested content, using advanced prompt engineering and Azure OpenAI. The reports are generated in a strict format, with different sections created by separate models and then compiled into a complete document. Generated reports are stored in Azure Blob Storage and presented in a React web application, where users can review, edit, and interact with them. A built-in AI chatbot enables staff to ask questions about the reports or request on-the-fly updates and edits, with AI-powered inline editing.

Collaboration between IBM and Neudesic developers ensured robust architecture, efficient processing, and iterative prompt refinement for optimal results.

---

## What I Worked On

- Developed the pipeline for ingesting and parsing PDFs with Azure Document Intelligence and extracting structured data.
- Implemented chunking, vectorization, and storage of document content in Azure AI Search and CosmosDB for efficient retrieval.
- Engineered AI prompt workflows to generate multi-section safety reports using Azure OpenAI, dividing responsibilities among multiple models for scalability and quality.
- Built and integrated the React frontend for browsing, reviewing, and editing safety reports, with Material UI and Tailwind styling.
- Developed chatbot integration to allow users to ask questions and make inline edits to safety reports using LLM-based responses.
- Participated in prompt engineering experimentation, model selection, and combining section outputs for cohesive, token-efficient reports.

---

## Challenges & Solutions

- **Challenge:** Parsing and standardizing unstructured safety information from varied PDF formats.
  - **Solution:** Leveraged Azure Document Intelligence for OCR and designed robust chunking/vectorization logic for effective storage and retrieval.
- **Challenge:** Generating comprehensive, well-structured safety reports within token limits and model constraints.
  - **Solution:** Split the report generation into sections handled by different models, then used an additional model to combine and refine the final report.
- **Challenge:** Providing interactive editing and AI support within the report management UI.
  - **Solution:** Developed a React-based UI with inline editing and an AI-powered chatbot to handle user queries and generate on-demand updates.

---

## Key Takeaways

- Strengthened experience with end-to-end RAG pipelines, document OCR, and AI-based report generation.
- Gained insights into prompt engineering and multi-model orchestration for complex, multi-section outputs.
- Improved skills in collaborative POC delivery and requirements iteration with enterprise partners.
- Recognized best practices for combining automated document processing with user-driven AI workflows for compliance and efficiency.

---

# Contract Redlining

## Role

**Developer**

## Project Description

Proof of concept Word plugin leveraging AI to assist legal teams in contract review and redlining by suggesting edits and highlighting key issues directly within Microsoft Word documents.

## Project Timeline

- **Start Date:** 2024-10-14
- **End Date:** 2024-10-31

## Team Size

3–5

## Client

Law Firm (POC)

## Keywords

Contract Review, Redlining, Word Plugin, Legal Tech, AI, Azure OpenAI, Document Automation, LLM, Proof of Concept

---

## Tech Stack

- **Frontend:** Word Plugin (React, Typescript, HTML), Tailwind, Angular (for document management UI)
- **Backend:** Azure Function, C#, .NET
- **Database:** Azure CosmosDB (NoSQL)
- **Other:** Azure Static Web App, Azure OpenAI

---

## Full Description

Contract Redlining is a proof of concept developed for a Law Firm, a client in the legal and contract management space. The solution is a Microsoft Word plugin designed to streamline the process of contract review and redlining using AI. The plugin extracts the full text of a contract from a Word document and sends it to an Azure OpenAI-powered backend, which uses tailored prompts and reference documentation to analyze and suggest edits, highlight issues, and identify important clauses that may need attention.

Alongside the Word plugin, an Angular-based frontend was created for users to manage, view, and organize their documents and review AI-generated suggestions before making edits. This central hub allows users to select a document, open it in Word (either in-browser or desktop), and interact with the plugin for seamless AI-powered contract review.

The backend, built with Azure Functions and C#, handles the processing, calls to Azure OpenAI, and returns actionable feedback to the plugin. While this project was executed quickly as part of a sales pitch, the proof of concept successfully demonstrated the core capabilities and laid the groundwork for future, more robust solutions.

---

## What I Worked On

- Developed components of the Microsoft Word plugin using React and Typescript to extract and display contract content.
- Integrated the frontend plugin with backend Azure Functions for AI-powered content analysis and suggestions.
- Contributed to the Angular-based UI for document management and visualization of AI suggestions.
- Assisted in designing the backend workflow for processing contract documents and interacting with Azure OpenAI.
- Participated in architecture diagramming and rapid prototyping to meet tight deadlines for the sales demo.

---

## Challenges & Solutions

- **Challenge:** Rapidly building a functional proof of concept within a short timeline.
  - **Solution:** Focused on core workflows—Word plugin integration, AI analysis, and document management—prioritizing MVP features and clear architecture documentation.
- **Challenge:** Ensuring AI suggestions were relevant and actionable given varied contract language.
  - **Solution:** Used targeted prompt engineering and incorporated company-provided documentation to improve the relevance of LLM suggestions.
- **Challenge:** Seamless user experience moving between document management and in-Word review.
  - **Solution:** Developed an Angular dashboard for organizing and previewing documents, and ensured smooth interoperability with the Word plugin.

---

## Key Takeaways

- Gained experience building Office plugins and integrating them with modern web and AI technologies.
- Learned best practices for rapid prototyping, architecture documentation, and demo-driven development.
- Developed understanding of legal contract workflows and the practical application of LLMs in legal tech.
- Enhanced skills in cross-team collaboration and delivering client-focused proof of concept solutions.

---

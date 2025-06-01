# IT Copilot Chat

## Role

**Lead, AI Developer**

## Project Description

Custom Copilot chatbot proof-of-concept (POC) for IT, leveraging Azure Copilot Studio, SharePoint, and RAG to provide context-aware support and information retrieval from internal IT knowledge bases.

## Project Timeline

- **Start Date:** 2024-06-17
- **End Date:** 2024-07-12

## Team Size

3–4

## Client

Internal, POC

## Keywords

Copilot, AI Chatbot, IT Support, SharePoint, Azure OpenAI, RAG, Document Retrieval, AI Copilot Studio, Knowledge Base

---

## Tech Stack

- **Frontend:** N/A
- **Backend:** N/A
- **Database:** N/A
- **Other:** Azure Copilot Studio, Azure OpenAI, SharePoint, RAG

---

## Full Description

IT Copilot Chat is an internal proof-of-concept project focused on building a custom Copilot chatbot for the IT team using the new Azure Copilot Studio. The objective was to evaluate the feasibility of grounding a conversational AI agent with organization-specific IT knowledge stored in SharePoint. This would allow employees to receive automated support and solutions tailored to the company's unique IT environment.

To enable this, I developed a Node.js script that automated the download and upload of IT support articles from the company website to a SharePoint server. Using Azure Copilot Studio, I then created a custom Copilot agent connected to this SharePoint data source. I developed several custom skills and agentic flows to guide the chatbot's behavior, focusing on responding to internal support queries using the uploaded documentation. The solution was deployed for testing on the internal IT portal, where we conducted trial runs to assess its usefulness and quality of responses.

Although the project was ultimately not adopted due to insufficient answer quality and limitations of the current AI Copilot tooling, it provided valuable insight into the capabilities and limitations of Microsoft's latest AI stack and emerging Copilot technologies.

---

## What I Worked On

- Led the initiative to design and develop a custom Copilot chatbot for IT support use cases.
- Automated the ingestion of internal IT articles from the company website to SharePoint via Node.js scripting.
- Configured Azure Copilot Studio to ground the chatbot with SharePoint knowledge and develop custom agent flows.
- Designed and tested custom Copilot skills and conversational flows tailored to IT support scenarios.
- Deployed the POC to the internal IT site and conducted extensive user testing and feedback collection.
- Provided technical evaluation and recommendations on the viability of Microsoft Copilot Studio for future production use.

---

## Challenges & Solutions

- **Challenge:** Connecting and grounding Copilot with SharePoint data to ensure relevant and accurate answers.
  - **Solution:** Developed a script to automate knowledge ingestion and configured data connectors within Copilot Studio for seamless integration.
- **Challenge:** Navigating and building with rapidly evolving, early-stage AI Copilot tools.
  - **Solution:** Invested time in learning new paradigms, adapting to frequent changes, and iterating quickly with hands-on trial and error.
- **Challenge:** Achieving high-quality, production-ready answers from the Copilot agent.
  - **Solution:** Experimented with custom skills, prompt flows, and feedback loops, ultimately concluding current limitations prevented production use.

---

## Key Takeaways

- Gained first-hand experience with Microsoft’s new Azure Copilot Studio and agentic AI workflows.
- Learned about best practices and challenges for grounding conversational AI agents with enterprise knowledge bases like SharePoint.
- Developed new skills in automating content ingestion and data integration for AI projects.
- Recognized the current maturity level of Copilot Studio and its potential future role in enterprise AI solutions.
- Provided technical recommendations for future adoption and standardization of Copilot tooling.

---

# AI Chatbot for Book Publishing Company

## Role

**AI Developer**

## Project Description

AI Chatbot using Retrieval Augmented Generation (RAG) for searching and querying a large collection of books, enabling advanced semantic search and conversational responses for marketing and business use cases.

## Project Timeline

- **Start Date:** 2024-04-08
- **End Date:** 2024-06-14

## Team Size

4–5

## Client

Book Publishing Company

## Keywords

AI Chatbot, RAG, Book Ingestion, Semantic Search, Azure OpenAI, Embeddings, Vector Search, Node.js, React, Publishing, Marketing, Azure AI Search

---

## Tech Stack

- **Frontend:** React, Redux, Typescript, Material UI, Tailwind, React Router, Axios
- **Backend:** Node.js, Azure Functions
- **Database:** CosmosDB (NoSQL)
- **Other:** Azure App Service, Azure API Management, Azure AI Search, RAG, Embeddings, Azure OpenAI

---

## Full Description

The AI Chatbot for Book Publishing Company is a Retrieval Augmented Generation (RAG) solution developed to unlock the value of the publisher’s extensive book catalog. The system ingests the full text of books, chunking and vectorizing each page along with associated metadata such as genre, summary, chapter, page number, and other relevant details. All this data is indexed in Azure AI Search to enable powerful, semantic search capabilities.

The chatbot enables marketing and business users to enter queries related to any subject, event, or keyword—for example, finding all books that mention “Taylor Swift” in connection to a local event. The RAG pipeline searches the vectorized book data to find the most relevant pages, combines them with classic metadata filtering (by genre, year, etc.), and generates concise, context-aware responses via Azure OpenAI models.

The backend, developed in Node.js with Azure Functions, handles the ingestion, chunking, vectorization, and orchestration of queries and model calls. The React frontend offers an intuitive chat interface for users to interact with the system, view matched results, and refine their searches with additional filters.

---

## What I Worked On

- Led the ingestion pipeline for processing books: parsing, chunking pages, extracting metadata, and vectorizing content.
- Designed and implemented the RAG workflow, integrating Azure AI Search and OpenAI models for semantic search and response generation.
- Developed backend logic in Node.js and Azure Functions to manage book data, metadata, embeddings, and query orchestration.
- Collaborated on data modeling in CosmosDB for efficient storage and retrieval of book chunks and metadata.
- Assisted with integrating the backend APIs with the React-based chatbot frontend.
- Implemented advanced filtering mechanisms to combine vector search results with classic metadata filters (e.g., by year, genre, chapter).

---

## Challenges & Solutions

- **Challenge:** Parsing, chunking, and extracting rich metadata from diverse book formats for ingestion.
  - **Solution:** Developed robust text extraction and metadata parsing routines to capture all relevant data for each book and page, ensuring high-quality search and filtering.
- **Challenge:** Combining traditional metadata-based search (year, genre, etc.) with semantic, vector-based search.
  - **Solution:** Engineered backend logic to blend classic filters with AI-driven vector similarity, enabling complex, multi-faceted queries and highly relevant results.
- **Challenge:** Ensuring scalability and performance for searching across a massive collection of book data.
  - **Solution:** Leveraged Azure AI Search and CosmosDB for optimized indexing, retrieval, and filtering.

---

## Key Takeaways

- Deepened expertise in RAG architectures and large-scale data ingestion for AI-powered search applications.
- Learned effective strategies for metadata extraction, document chunking, and combining traditional and AI-based search.
- Gained hands-on experience with Azure AI Search, vector embeddings, and semantic query workflows.
- Enhanced skills in collaborating on multi-disciplinary AI/ML product teams and delivering business value for large enterprise clients.

---

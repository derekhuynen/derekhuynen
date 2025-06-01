# Document Processing for Hospitals

## Role

**Lead Developer, Architect**

## Project Description

System to parse and standardize rate sheets from multiple hospitals, extracting structured data from a variety of PDF formats and storing it in a unified database.

## Project Timeline

- **Start Date:** 2024-08-05
- **End Date:** 2024-10-11

## Team Size

2

## Client

IBM, Hospital Consultant Company

## Keywords

Document Processing, OCR, PDF Parsing, Healthcare Data, Azure Document Intelligence, Data Standardization, Node.js, Hospital Rate Sheets

---

## Tech Stack

- **Frontend:** Vite
- **Backend:** Node.js, TypeScript
- **Database:** Azure CosmosDB (NoSQL)
- **Other:** Azure Blob Storage, Azure Document Intelligence (OCR), PDF Processing, Jest (Testing)

---

## Full Description

Document Processing for Hospitals was a proof-of-concept engagement between IBM, and Hospital Consultant Company. The project’s goal was to automate the extraction and standardization of hospital rate sheets, which exist in numerous PDF formats and structures across hospitals nationwide. These rate sheets contain complex tables outlining pricing, insurance rates, and various hospital-specific metrics.

The solution ingests PDFs from different hospitals, classifies the origin and structure of each document, and then uses Azure Document Intelligence (OCR) to extract tables and key information. Custom parsing functions—dynamically selected based on document classification—transform the extracted data into a standardized format, ready for storage in Azure CosmosDB. Robust testing (with Jest) and careful code organization ensured accuracy and scalability, even as requirements evolved and new hospital formats were added.

Collaboration involved direct interaction with client teams at IBM and Hospital Consultant Company, focusing on technical delivery and iterative improvements.

---

## What I Worked On

- Architected and developed the end-to-end PDF ingestion, classification, and parsing pipeline.
- Implemented document classification logic to identify hospitals and select appropriate parsing routines for each PDF.
- Developed custom table extraction and data normalization functions using Azure Document Intelligence and Node.js.
- Automated the upload, storage, and backup of large volumes of PDF documents via Azure Blob Storage.
- Designed and maintained a unified schema for rate sheet data in Azure CosmosDB.
- Built reusable parsing modules to maximize maintainability and reduce redundant code across varying hospital formats.
- Wrote and maintained Jest tests to ensure data integrity and catch regressions as the parsing engine expanded.
- Coordinated with IBM and Hospital Consultant Company to refine requirements and address client feedback in real-time.

---

## Challenges & Solutions

- **Challenge:** Handling a vast array of differing PDF formats and evolving rate sheet templates.
  - **Solution:** Developed a robust classification and modular parsing architecture, enabling dynamic selection of parsing strategies and easy code reuse.
- **Challenge:** Maintaining organization and data integrity while managing hundreds of PDFs across hospitals, years, and document types.
  - **Solution:** Implemented strict file organization, automated backups, and comprehensive testing to ensure reliability and scalability.
- **Challenge:** Ensuring updates to one hospital’s parsing logic did not break others.
  - **Solution:** Focused on code modularity, reusable utility functions, and maintained a thorough suite of tests for all supported document types.

---

## Key Takeaways

- Learned advanced techniques for OCR, PDF parsing, and large-scale document standardization.
- Improved project organization and code reuse practices for complex, data-driven applications.
- Gained experience leading direct technical communications with multiple enterprise clients.
- Enhanced testing strategies to maintain reliability as the codebase and supported formats expanded.
- Recognized the critical role of flexible, modular architectures in rapidly evolving data extraction projects.

---

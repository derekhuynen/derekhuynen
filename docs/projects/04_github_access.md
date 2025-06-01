# Github Access Hub

## Role

**Lead, Architect, Developer**

## Project Description

Web application enabling employees to log in with their company email and request access to company GitHub organizations.

## Project Timeline

- **Start Date:** 2024-02-05
- **End Date:** 2024-03-08

## Team Size

1

## Client

Internal, IT

## Keywords

GitHub Access, Onboarding, IT Automation, Azure, Authentication, GraphQL, Self-Service Portal, DevOps, Internal Tools

---

## Tech Stack

- **Frontend:** Angular, TypeScript, Azure Static Web App
- **Backend:** C#, .NET, Azure Function
- **Database:** N/A
- **Other:** GitHub GraphQL API, GitHub Auth, Azure Entra ID, MSAL, GitHub Actions

---

## Full Description

Github Access Hub is an internal tool designed to streamline onboarding and access management for company GitHub organizations. The application allows any employee to securely log in with their company email via Azure Entra ID, view available GitHub organizations, and request access with a few clicks.

This self-service portal reduces the workload for IT and onboarding teams by automating the invitation and approval process for GitHub organizations, leveraging the GitHub GraphQL API. The solution retrieves user information, current organization memberships, and manages access requests efficiently. The entire application was architected, developed, and deployed as a solo project, with a focus on maintainability and future scalability.

The app is hosted as an Azure Static Web App, with the backend logic implemented via Azure Functions in C#. All deployments were automated using GitHub Actions, ensuring a robust CI/CD pipeline and minimal manual intervention.

---

## What I Worked On

- Solely architected and developed the application from the ground up.
- Designed and implemented the Angular frontend for user authentication, organization listing, and access requests.
- Developed C# Azure Functions to interface with the GitHub GraphQL API and handle business logic.
- Integrated Azure Entra ID and MSAL for secure, company-only authentication.
- Automated deployments to Azure using GitHub Actions and maintained project documentation for future scalability.
- Set up GitHub Auth for secure API access and managed permissions for organization invitations.
- Deployed and published the solution on the internal IT portal for company-wide use.

---

## Challenges & Solutions

- **Challenge:** Securing authentication to ensure only employees can access the portal.
  - **Solution:** Integrated Azure Entra ID (Microsoft Identity Platform) with MSAL for robust, secure authentication and authorization.
- **Challenge:** Automating organization membership requests through GitHub's API.
  - **Solution:** Built serverless Azure Functions in C# to interface directly with the GitHub GraphQL API for reliable data retrieval and automated invitation workflows.
- **Challenge:** Ensuring the project was maintainable for future handoff.
  - **Solution:** Focused on clear, thorough documentation and modular architecture for easy onboarding by future developers.

---

## Key Takeaways

- Gained full-lifecycle experience as a solo architect, developer, and DevOps engineer on a business-critical internal tool.
- Learned best practices for authentication and authorization using Azure Entra ID and MSAL.
- Improved knowledge of GitHub’s GraphQL API and integration patterns with Azure serverless architecture.
- Enhanced ability to document, organize, and automate deployment workflows for better maintainability and knowledge transfer.
- Appreciated the importance of designing solutions that reduce repetitive IT workloads and improve onboarding efficiency.

---

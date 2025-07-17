# 🌐 Cloud-Native Integration Project: Full SDLC Learning Plan

**Goal**: Build a cloud-native, end-to-end integration project on Microsoft Azure using Node.js, Terraform, GitHub Actions, and Azure Logic Apps. The project will consume a free public API (REST Countries) to demonstrate real-world orchestration, automation, and CI/CD workflows. This plan also simulates the full software development lifecycle (SDLC) for hands-on project management experience.

---

## 📌 Milestone-Based Learning Plan

### 1. 🧭 Project Inception & Planning
**Objective**: Understand the problem, define scope, and plan delivery.

- Define business goal and project vision
     Build a backend service that automates the retrieval of global country data—including names, capitals, currencies, population, area, languages, and timezones—from a public API. This data will be stored in a relational database and made accessible for internal dashboards, reporting tools, and data-driven decision-making.

- Identify stakeholders (simulated)
    Me, you and other learners and contributors
  
- Write a Project Charter
- Create a high-level timeline and milestone plan
- Tools: Notion, Trello, Azure DevOps Boards

---

### 2. 📝 Requirements Gathering
**Objective**: Capture what the system should do.

- Write Business Requirements Document (BRD)
- Translate into Functional Requirements
- Define Non-Functional Requirements (performance, security, etc.)
- Tools: Markdown, Word, Confluence

---

### 3. 🧱 Technical Design
**Objective**: Architect the solution.

- Create System Architecture Diagram
- Define API contracts (OpenAPI/Swagger)
- Plan Azure resources (App Service, Logic App, etc.)
- Write Technical Design Document (TDD)
- Tools: Draw.io, Lucidchart, Markdown

---

### 4. ⚙️ Infrastructure Setup (Terraform)
**Objective**: Provision Azure infrastructure as code.

- Write Terraform scripts for:
  - Resource Group
  - App Service Plan
  - App Service
  - Logic App
- Test locally with `terraform plan` and `apply`
- Tools: Terraform CLI, Azure CLI

---

### 5. 🛠️ Backend Development (Node.js)
**Objective**: Build the core application logic.

- Create Express.js app
- Integrate REST Countries API
- Add endpoint to trigger Logic App
- Write unit tests
- Tools: Node.js, Postman, Jest

---

### 6. 🔄 Workflow Automation (Logic Apps)
**Objective**: Orchestrate a workflow using Azure Logic Apps.

- Create Logic App with HTTP trigger
- Process or enrich data
- Send email or log to Azure Monitor
- Test with backend integration

---

### 7. 🚀 CI/CD Pipeline (GitHub Actions)
**Objective**: Automate deployment and testing.

- Create GitHub Actions workflows for:
  - Linting and testing Node.js
  - Terraform deployment
  - App Service deployment
- Store secrets in GitHub
- Tools: GitHub Actions, Azure CLI

---

### 8. ✅ Testing Phases
**Objective**: Validate the system end-to-end.

- **SIT (System Integration Testing)**: Test backend + Logic App
- **UAT (User Acceptance Testing)**: Simulate user scenarios
- Write test cases and test reports
- Tools: Postman, Excel/TestRail

---

### 9. 🚦 Cutover & Go-Live
**Objective**: Deploy to production (or simulate it).

- Create a cutover plan
- Simulate a go/no-go meeting
- Deploy final version
- Tools: GitHub Actions, Azure Portal

---

### 10. 🛡️ Hypercare & Handover
**Objective**: Monitor and support post-deployment.

- Set up monitoring/logging (Azure Monitor, App Insights)
- Create a runbook or support guide
- Document lessons learned

---

## 📁 Bonus: Artifacts You’ll Create

- Project Charter
- BRD & TDD
- Architecture Diagram
- Terraform scripts
- Node.js app
- Logic App workflow
- GitHub Actions workflows
- Test cases and reports
- Cutover plan
- Handover documentation


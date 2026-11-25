# IncidentIQ - Autonomous Operations Platform

An enterprise-grade, agentic incident investigation and remediation platform built with Java, Spring Boot, and modern operations tooling.

---

## 📌 Deliverables & Links

- 🎥 **Project Video Demo (Google Drive):**
  > **[Click Here to Watch Video Demo](https://drive.google.com/drive/folders/1XU0303bslIzol6O14QkZffUG5-9ESq-U)**  
  *(Also documented in [VIDEO.md](VIDEO.md))*

- 📄 **Project Report & Documentation:**
  > **[View IncidentIQ Project Report (PDF)](./IncidentIQ_Project_Report.pdf)**

---

## 📁 Repository Structure

``text
IncidentIQ/
├── IncidentIQ_CODE/                  # Complete backend source code and services
│   ├── agentops/                     # Spring Boot application (Controllers, Services, Models, Repositories)
│   ├── DESIGN.md                     # Architecture and system design specifications
│   ├── PRODUCT.md                    # Product overview and requirement details
│   ├── PROJECT_SPEC.md               # Technical project specification
│   ├── start_backend.bat             # Windows script to launch Spring Boot backend
│   ├── start_backend.ps1             # PowerShell backend startup script
│   ├── start_ui.bat                  # Frontend UI launcher
│   └── test_suite.ps1                # Integration test runner
├── IncidentIQ_Project_Report.pdf     # Final project report document (PDF)
├── VIDEO.md                          # Video demonstration links and walkthrough details
├── .gitignore
└── README.md                         # Main project overview and deliverable links
``

---

## 🚀 Getting Started

To run the project locally, navigate into the source directory:

``bash
cd IncidentIQ_CODE
``

### 1. Prerequisites
- **Java**: JDK 17 or higher
- **Maven**: 3.8+ (or bundled wrapper)
- **Database**: MySQL 8.0+

### 2. Start the Backend Service
Using PowerShell:
``powershell
.\start_backend.ps1
``
Or via standard Maven:
``bash
cd agentops
./mvnw spring-boot:run
``

The REST API will be accessible at: `http://localhost:8080/api`

### 3. Run Automated Tests
``powershell
.\test_suite.ps1
``

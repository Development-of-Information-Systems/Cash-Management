<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

---

<p align="center">
  <strong>Design and Development of Information Systems</strong>
</p>

<h1 align="center">
  Development of a Unified Information System to Support Operational Operations of Health Units: Cash Management Subsystem
</h1>

<p align="center">
  <strong>Vasileios Evangelos Athanasiou</strong><br>
  Student ID: 19390005
</p>

<p align="center">
  <a href="https://github.com/Ath21" target="_blank">GitHub</a> ·
  <a href="https://www.linkedin.com/in/vasilis-athanasiou-7036b53a4/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Supervisor: Elias Dritsas, Senior Researcher<br>
</p>

<p align="center">
  <a href="https://www.isi.gr/people/dr-elias-dritsas" target="_blank">UNIWA Profile</a> ·
  <a href="https://gr.linkedin.com/in/elias-dritsas-7997b2159" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Athens, January 2025
</p>

---

# Project Overview

This project involves the development of a **Unified Information System** designed to support the operational functions of health units within the **National Health System**. The focus of this specific work is the **Cash Management Subsystem**, commissioned by the **Electronic Governance of Social Security (EDIKA) S.A.**

The subsystem is designed to manage financial transactions with suppliers, monitor open liabilities, and execute payments, ensuring interoperability with the **General Accounting** and **Budget** modules.

---

## Table of Contents


| Section | Folder / File | Description |
|------:|---------------|-------------|
| 1 | `assign/` | Assignment and competition material |
| 1.1 | `assign/Announcement of Competition.pdf` | Competition announcement (English) |
| 1.2 | `assign/WORK STATEMENT.pdf` | Work statement and project requirements (English) |
| 1.3 | `assign/Διακήρυξη Διαγωνισμού.pdf` | Competition announcement (Greek) |
| 1.4 | `assign/ΕΚΦΩΝΗΣΗ ΕΡΓΑΣΙΑΣ.pdf` | Assignment description (Greek) |
| 2 | `docs/` | Project and information system documentation |
| 2.1 | `docs/IS-Cash-Management-ESY.pdf` | Information System for Cash Management – ESY (English) |
| 2.2 | `docs/ΠΣ-Ταμειακής-Διαχείρισης-ΕΣΥ.pdf` | Cash Management Information System – ESY (Greek) |
| 3 | `Gantt/` | Project scheduling and planning |
| 3.1 | `Gantt/Gantt_Diagram.mpp` | Gantt diagram (English – MS Project file) |
| 3.2 | `Gantt/Διάγραμμα_Gantt.mpp` | Gantt diagram (Greek – MS Project file) |
| 3.3 | `Gantt/Chart/` | Gantt charts (PNG format) |
| 3.4 | `Gantt/Time/` | Project timelines and schedules |
| 3.5 | `Gantt/Resources/` | Resource allocation diagrams |
| 3.6 | `Gantt/CashFlow/` | Cash flow analysis diagrams |
| 4 | `WBS/` | Work Breakdown Structure documentation |
| 4.1 | `WBS/WBS_Diagram.png` | Work Breakdown Structure diagram (English) |
| 4.2 | `WBS/Διάγραμμα_WBS.png` | Work Breakdown Structure diagram (Greek) |
| 5 | `Zachman/` | Zachman Framework models and diagrams |
| 5.1 | `Zachman/Data/` | Data perspective (ER & logical models) |
| 5.2 | `Zachman/Function/` | Functional perspective (BPMN, workflows, flowcharts) |
| 5.3 | `Zachman/People/` | Organizational structure, RACI matrix, use cases |
| 5.4 | `Zachman/Time/` | Time perspective (PERT charts, roadmap diagrams) |
| 5.5 | `Zachman/Zachman_Framework.png` | Zachman Framework overview diagram |
| 6 | `README.md` | Repository overview and usage instructions |
---


## Key Features

- **Supplier Invoice Entry:** Processing and validation of supplier invoices.  
- **Obligations Monitoring:** Tracking open liabilities, overdue debts, and providing tools for liquidity planning.  
- **Payment Management:** Issuance of payment orders and automatic integration with the General Accounting subsystem.  
- **Reporting:** Generation of balance sheets, supplier statements, and financial reports.  
- **Interoperability:** Continuous data synchronization with Budgeting and Accounting subsystems.

## Development Methodology

The project follows the **SCRUM** methodology, an agile framework selected for its flexibility and suitability for complex, interoperable systems.

### Key Methodology Benefits
- **Short Sprints:** Functional deliverables produced every 2–4 weeks, reducing overall project risk.  
- **Risk Management:** Daily stand-ups and sprint reviews enable early identification and resolution of issues.  
- **Stakeholder Collaboration:** Continuous feedback ensures compliance with evolving regulatory and operational requirements.

## Project Structure & Budget

The project is structured into four primary phases according to the **Work Breakdown Structure (WBS)**:

| Phase | Description               | Duration (Man-Days) | Estimated Budget |
|------:|---------------------------|---------------------:|------------------:|
| 1 | Project Initiation        | 35 MDS | $20,000 |
| 2 | Subsystem Development     | 84 MDS | $52,000 |
| 3 | Testing & Validation      | 35 MDS | $30,000 |
| 4 | Delivery & Training       | 49 MDS | $17,000 |
| **Total** | **Entire Project** | **203 MDS** | **$119,000** |

## System Design Framework

The architectural design is based on the **Zachman Framework**, addressing multiple views and abstraction levels:

- **Views:**  
  - Data (*What*)  
  - Function (*How*)  
  - People (*Who*)  
  - Time (*When*)

- **Levels:**  
  - Contextual  
  - Conceptual  
  - Logical

- **Modeling Tools:**  
  - **BPMN** for business process modeling  
  - **UML** for user roles and system interactions  
  - **ERD** for data structure and relationships

---

# Installation & Setup Guide

This repository contains a **documentation-centric Information System project** developed in the context of the **Development of Information Systems** course.  
The project focuses on the **Cash Management Subsystem** of a Unified Information System for health units of the **National Health System (ESY)** and is based on **analysis, modeling, and project planning artifacts**, not on executable source code.

---

## Prerequisites

This project **does not require a runtime environment or software stack** (no backend, frontend, or database server).  
However, to properly **view, edit, and evaluate** the contents, the following tools are recommended.

### 1. Operating System
- Windows (recommended, due to MS Project files)
- Linux
- macOS

---

### 2. Document & Diagram Viewing Tools

#### PDF Reader
Required for assignment texts and system documentation:
- Adobe Acrobat Reader
- Foxit Reader
- Any modern browser (Chrome, Firefox, Edge)

#### Image Viewer
Required for diagrams and models:
- Default OS image viewer
- Any graphics viewer/editor

---

### 3. Project Planning Tools

#### Microsoft Project (Recommended)
Required to fully open and edit:
- `Gantt/*.mpp`

Alternative (read-only or limited support):
- ProjectLibre
- GanttProject

---

### 4. Modeling & Diagram Tools (Optional but Recommended)

For understanding or extending the system design:

- **BPMN / UML**
  - draw.io (diagrams.net)
  - Visual Paradigm
  - StarUML

- **ER / Data Models**
  - draw.io
  - MySQL Workbench (diagram mode only)
  - Lucidchart

---

### 5. Knowledge Prerequisites

To fully understand the project, basic familiarity with the following concepts is recommended:

- Information Systems Analysis & Design
- SCRUM / Agile methodology
- Work Breakdown Structure (WBS)
- Gantt Charts & Project Scheduling
- BPMN workflows
- UML diagrams
- Zachman Framework
- Public sector financial processes (conceptual level)

---

## Installation / Setup

### 1. Clone the Repository

Using Git:

```bash
git clone https://github.com/Development-of-Information-Systems/Cash-Management.git
```

#### Alternative (Without Git)

- Open the repository URL in your browser
- Click Code → Download ZIP
- Extract the ZIP file to a local directory

### 2. Explore Project Structure
After extraction, the project can be explored directly:
- `assign/` → Official competition and assignment texts
- `docs/` → Information System documentation (EN / GR)
- `Gantt/` → Project schedule, timelines, and resource planning
- `WBS/` → Work Breakdown Structure diagrams
- `Zachman/` → System architecture and modeling views

No build or execution step is required.

### 3. Open Key Artifacts
Recommended starting points:
1. System Overview
- `docs/IS-Cash-Management-ESY.pdf`
- `docs/ΠΣ-Ταμειακής-Διαχείρισης-ΕΣΥ.pdf`
2. Project Planning
- `Gantt/Gantt_Diagram.mpp`
- `WBS/WBS_Diagram.png`
3. Architecture & Design
- `Zachman/Zachman_Framework.png`
- Subfolders under `Zachman/` (Data, Function, People, Time)

---

## Open the Documentation
1. Navigate to the `docs/` directory
2. Open the report corresponding to your preferred language:
    - English: `IS-Cash-Management-ESY.pdf`
    - Greek: `ΠΣ-Ταμειακής-Διαχείρισης-ΕΣΥ.pdf`
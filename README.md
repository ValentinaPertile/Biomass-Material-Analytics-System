# BioMechanalyze: Mechanical Testing Analysis & Visualization System 

> **Collaboration with CONICET** > This system was developed as a specialized solution for **CONICET** to automate the processing and analysis of biodegradable materials derived from biomass.

---

##  Table of Contents
1. [Overview](#-overview)
2. [Problem Statement](#-problem-statement)
3. [System Objectives](#-system-objectives)
4. [Key Features](#-key-features)
5. [Tech Stack](#-tech-stack)
6. [Installation & Setup](#-installation--setup)
7. [Project Structure](#-project-structure)
8. [Academic Context](#-academic-context)

---

##  Overview
**BioMechanalyze** is an advanced software platform designed to assist researchers in evaluating the mechanical properties of eco-friendly materials. By automating the data pipeline—from raw machine output to graphical visualization—the system ensures high precision and efficiency in scientific research.

##  Problem Statement
Researchers at CONICET previously faced significant bottlenecks in processing data from mechanical testing machines. 
- **Manual Labor:** Hundreds of daily tests produced files in **Excel and CSV** formats that required manual reorganization.
- **Human Error:** Manual calculation of variables (Stress, Strain, etc.) increased the risk of inaccuracies.
- **Lack of Centralization:** No unified system existed to store, consult, or trace previous analyses, hindering scientific progress.

##  System Objectives

### General Objective
To develop an integrated system that automates the processing and analysis of mechanical tests, allowing for personalized calculations, data editing, dynamic visualization, and secure user management.

### Specific Objectives
- **Multi-Format Ingestion:** Intuitive interface for loading Excel, CSV, and TC2 files.
- **Analytical Module:** Implement specific mechanical property calculations with customizable specimen variables.
- **Data Editing:** Enable table reorganization and data cleaning before final export.
- **Dynamic Visualization:** Integrate a system for real-time graphical representation of results.
- **Secure Export:** Allow results to be exported in professional **Excel and PDF** formats.
- **User Management:** Incorporate an authentication system to control access and ensure data traceability.

##  Key Features
- **Smart Parsing:** Automates the extraction of data from testing machines, eliminating manual entry.
- **Dynamic Charting:** Interactive stress-strain curves that update in real-time.
- **CRUD Operations:** Full control over test data, allowing researchers to edit or delete records before final analysis.
- **Secure Authentication:** Protected access to sensitive research data via an integrated login system.
- **Scientific Reporting:** High-quality PDF and Excel generation for research documentation.

## Tech Stack
- **Frontend:** React 19 + Vite (Modern, high-performance UI).
- **Backend:** Node.js + Express (Robust API handling).
- **Database:** SQLite (managed via `database.db`) for secure, local data persistence.
- **Styling:** CSS3 with a focus on responsive, laboratory-oriented design.
- **Standardization:** ESLint for maintaining code quality and scientific software standards.

##  Installation & Setup

Follow these steps to run the project locally:

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/ValentinaPertile/Biomass-Material-Analytics-System.git]
2. Install Dependencies:
  npm install
  Database Initialization: The project includes a pre-configured database.db. Ensure the backend has permissions to read/write in the root directory.

3. Launch the Development Environment:

  Start the Backend Server:
    node server.js

  Start the Frontend (Vite):
    npm run dev

## Academic Context
This project constitutes the Final Integrative Seminar for the Systems Analyst and Developer degree. It represents the culmination of academic training, applying software engineering methodologies to solve a complex, real-world scientific problem in a prestigious institution like CONICET.


Target Title: Systems Analyst and Developer

Year: 2026

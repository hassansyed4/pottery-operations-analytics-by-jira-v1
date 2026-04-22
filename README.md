# Pottery Operations Analytics through JIRA – Version 1

A client-demo-ready analytics project that simulates how operational data can be organized, cleaned, validated, and prepared for business reporting. This Version 1 repository documents the full workflow from project planning to dataset preparation and dashboard prototyping.

## Project Summary

This project was designed as a structured analytics engagement for a client demo. The goal was to show how raw operational data can be transformed into useful business insight through a disciplined workflow that includes:

- data source identification
- schema design
- data extraction
- data cleaning and transformation
- data validation
- schema and pipeline review
- initial dataset loading
- dashboard prototyping

The project was managed in a Jira-style board workflow and organized into sprint-based delivery stages. The demo outcome was strong because the work was not only technical, but also presented in a way that non-technical stakeholders could understand.

## Project JIRA Desktopn Screenshot:

<img width="1461" height="642" alt="image" src="https://github.com/user-attachments/assets/cddda0e4-d447-493b-80ac-0f67208ba7c7" />


## Business Goal

The business need was to convert raw operational data into a clean and decision-ready analytical layer that could support:

- trend analysis
- process monitoring
- data quality checks
- business reporting
- leadership-friendly dashboarding

# Jira Project Structure and Agile Workflow

## This project was designed using a Jira-style Agile workflow to simulate a real IT delivery environment. The work was structured using Epics, Tasks, and a Kanban board to track progress across multiple stages.

Project Management Approach
Agile methodology (lightweight implementation)
Kanban board for workflow visualization
Sprint-based execution (Sprint 1, Sprint 2)
Task tracking with status movement across stages
Epic Structure

## The project was divided into high-level Epics representing major phases of the analytics workflow:

Epic 1: Data Acquisition & Understanding
Data Source Identification
Data Schema Design
Epic 2: Data Engineering & Processing
Data Extraction Implementation
Data Cleaning & Transformation
Epic 3: Data Validation & Quality Assurance
Missing Metadata Clarification
Data Quality Validation
Epic 4: Analytics & Visualization
Initial Dataset Loaded
Dashboard Prototype Created
Task Breakdown

## Each Epic was broken down into actionable tasks:

Tasks were created to represent specific deliverables
Each task included:
owner (simulated)
due date
sprint assignment
status tracking

Example:

Task: Data Cleaning & Transformation
Sprint: Sprint 1
Status: In Progress
Kanban Board Workflow

The project used a Kanban-style board to track progress:

To Do → Tasks planned but not started
In Progress → Active development
Waiting for Info → Blocked tasks requiring clarification
In Review → Validation and quality checks
Done → Completed deliverables

This helped visualize the workflow and ensure structured progress.

Sprint Planning

## The project was divided into two sprints:

Sprint 1
Data source identification
Schema design
Data extraction
Initial cleaning
Sprint 2
Data validation
Pipeline review
Dataset loading
Dashboard prototype
Jira Concepts Applied

## This project demonstrates practical understanding of:

Epics → High-level business objectives
Tasks → Individual work units
Kanban → Workflow visualization
Sprints → Time-boxed execution
Status tracking → Work progress monitoring
Backlog → Planned tasks before execution
Why This Matters

## Using Jira-style structuring allowed the project to:

simulate real IT project delivery
improve task organization and clarity
track progress across stages
identify bottlenecks (e.g., waiting for info)
align technical work with business outcomes

## Project Context

This repository represents Version 1 of the requirement. In this version, the focus was on:

1. project planning and delivery workflow
2. dataset preparation and validation
3. dashboard prototype creation
4. clear communication for client review

The work was built as a client demo, and the client was satisfied with the structure, clarity, and business-oriented presentation of the solution.

## Delivery Workflow

The project followed a staged workflow similar to a real Jira board:

### To Do
- Data Source Identification
- Data Schema Design

### In Progress
- Data Extraction Implementation
- Data Cleaning and Transformation

### Waiting for Info
- Missing Metadata Clarification
- Data Quality Validation Pending

### In Review
- Database Schema Review
- ETL Pipeline Review

### Done
- Initial Dataset Loaded
- Dashboard Prototype Created

This workflow shows that the project was approached as a real delivery effort rather than just a one-time dataset exercise.

## Tools and Technologies Used

Version 1 was built using the following tools and concepts:

- Jira-style project workflow for delivery tracking
- Excel for data inspection, cleaning, transformation, and quick analysis
- CSV-based data handling for structured file exchange
- ETL thinking for data preparation and movement
- Data validation methods for completeness and consistency checks
- Dashboard prototyping for stakeholder communication
- GitHub for project documentation and version control

## What I Built From the Beginning

I created this project from the beginning with a structured analytics mindset. My work included:

- understanding the project scope and business need
- planning the workflow in a sprint-style board structure
- identifying likely data sources and mapping requirements
- defining the expected schema for analytics
- simulating extraction and preparation steps
- cleaning and transforming data into a usable format
- validating records and checking for missing or inconsistent values
- reviewing data design and pipeline logic
- loading the prepared dataset for reporting
- designing an initial dashboard prototype for the client demo

## Explanation

### Situation
The client needed a structured way to move from raw operational data to meaningful reporting. The challenge was not only technical preparation, but also making the work understandable and presentable for a business audience.

### Task
My task was to build a demo-ready analytics solution from the beginning, organize the workflow clearly, prepare the dataset, validate quality, and create a dashboard prototype that could communicate value to the client.

### Action
I broke the work into delivery stages and managed it in a Jira-style board. I defined the expected schema, designed extraction and cleaning steps, reviewed data quality requirements, and prepared the dataset for reporting. After the data pipeline and validation logic were reviewed, I loaded the initial dataset and created a dashboard prototype focused on business usability.

### Result
The final Version 1 demo showed a clear, end-to-end process from raw data planning to business-facing analytics. The client was satisfied with the clarity of the workflow, the structured execution, and the way the output was presented for decision-making.

## Why This Project Is Strong for GitHub

This project is strong for GitHub because it demonstrates more than technical execution. It shows:

- project planning
- workflow management
- analytics thinking
- data quality awareness
- business communication
- demo-ready presentation

That makes it useful for roles in:
- Data Analytics
- Business Analytics
- IT Analytics
- Operations Analytics
- Reporting and Dashboard Development
- Entry-level Data Engineering support

## Recommended GitHub Repository Structure

```text
pottery-operations-analytics-v1/
│
├── README.md
├── .gitignore
│
├── data/
│   ├── raw/
│   │   └── sample_input.csv
│   └── processed/
│       └── cleaned_dataset.csv
│
├── docs/
│   └── screenshots/
│       └── jira-board-demo.png
│
├── reports/
│   └── client-demo-summary.md
│
└── src/
    └── notes.md
```

## Folder Purpose

### `data/raw/`
Store the raw input files here. In a real business workflow, these would be CSV exports, source extracts, or initial client files.

### `data/processed/`
Store cleaned or transformed files here. This helps show the difference between source data and analytics-ready data.

### `docs/screenshots/`
Store project screenshots here, such as:
- Jira board view
- dashboard mockups
- schema diagrams
- validation snapshots

### `reports/`
Store business summaries, findings, or presentation notes for the client demo.

### `src/`
For Version 1, this can contain logic notes, transformation notes, or later scripts if the project evolves into Python or SQL-based processing.

## Suggested Files to Add

### `.gitignore`
Use this to exclude temporary files such as:
- Excel temp files
- Power BI temp files
- system-generated files

### `reports/client-demo-summary.md`
This should contain:
- project purpose
- business need
- delivery steps
- outcome
- recommendation for next phase

### `src/notes.md`
This can describe:
- schema assumptions
- data cleaning logic
- metadata questions
- validation notes
- pipeline review notes

## This repository represents Version 1 of the requirement. In Version 2, I completed the reporting workflow through Excel and Power BI, where I fetched Jira data in CSV format, transformed the data in Excel, and built visuals in both Excel and Power BI to support business needs and make insights easier for non-technical clients to understand.

## Version 2 Statement:

> Version 1 focused on workflow design, dataset preparation, validation, and dashboard prototyping. In Version 2, I advanced the solution by working with Jira-exported CSV data, performing transformation and structuring in Excel, and developing business-friendly visuals in Excel and Power BI. This helped translate operational ticket data into insights that leadership and non-technical stakeholders could quickly understand and use for decision-making.

## Resume / GitHub Highlights
- Designed and managed an end-to-end analytics workflow using a Jira-style delivery board
- Structured raw operational data into a validated, reporting-ready format
- Built a dashboard prototype to support business reporting and client demonstration
- Applied data validation, transformation, and schema review concepts
- Presented analytics work in a stakeholder-friendly format


## Final Note

This repository is intentionally positioned as Version 1 of the requirement. The next version extends the work into Excel- and Power BI-based reporting, using Jira CSV data extraction, transformation, and business-focused visualization for stakeholder communication.

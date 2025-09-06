# 🧠 Project Summary: Self-Hosted Budget Tracker

## 1. Project Overview
This project aims to build a modular, self-hosted personal finance tracker inspired by YNAB (You Need A Budget). It will allow manual import of bank transactions, apply zero-based budgeting logic, and generate customizable dashboards—initially in Excel, with optional migration to a browser-based UI.

The system is designed for autonomy, flexibility, and extensibility, with a focus on local-first architecture and personal control over data and logic.

## 2. Objectives

### Strategic Objectives
- Eliminate reliance on YNAB subscription and US-based integrations
- Enable tailored budgeting views and logic for South African and Dubai banking contexts
- Create a frictionless, enjoyable learning path for Python and system design

### Technical Objectives
- Build a Python–Excel hybrid MVP for transaction import, categorization, and budget tracking
- Implement version control and modular architecture for future upgrades
- Design assistant prompt files for AI agent handoff and role-based support

## 3. Key Outcomes
- ✅ MVP Python script to clean and categorize bank CSVs
- ✅ Excel dashboard with budget summaries and visualizations
- ✅ GitHub-hosted repo with structured folders and README
- 🧪 Optional Streamlit/Flask dashboard for browser-based access
- 🧠 Assistant prompt file for agent setup and role definition

## 4. Scope & Constraints
- Manual bank file uploads only (no API integrations)
- Local execution preferred; cloud hosting optional
- Excel remains primary dashboard format until browser UI is ready
- Modular design to support future agent roles and logic extensions

## 5. Technical Stack

| Layer         | Tool/Library         | Purpose                          |
|---------------|----------------------|----------------------------------|
| Data Input    | CSV/Excel            | Bank exports                     |
| Processing    | Python + pandas      | Cleaning, categorization         |
| Output        | Excel via openpyxl   | Budget summaries                 |
| UI (optional) | Streamlit or Flask   | Browser dashboard                |
| Versioning    | Git + GitHub         | Code and logic tracking          |

## 6. AI Assistant Setup

### Primary Agent
- Role: Strategic partner and technical architect
- Personality: Modular, proactive, context-aware
- Prompt file: `/prompts/assistant-setup.md`

### Future Agents (To Be Defined)
- Categorization bot: Refines transaction tagging logic
- Dashboard bot: Designs and updates visual layouts
- Tax logic bot: Applies jurisdiction-specific rules

## 7. Update Protocol
- All updates logged in section 8 below
- Major milestones tagged in Git commits
- Assistant prompt file updated separately and versioned independently
- User may request updates via: “Update the summary file with today’s progress”

## 8. Progress Log

### [2025-09-06]
- Installed Homebrew, Git, Python
- Resolved shell configuration issues
- Defined project scope and summary structure
- Planned assistant setup and versioning strategy
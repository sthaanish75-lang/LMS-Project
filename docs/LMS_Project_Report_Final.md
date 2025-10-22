# LMS Project Report (Final Draft)

This final draft is ready for screenshots and export to PDF. Replace the placeholder image paths with the actual screenshots saved under `docs/screenshots/` before exporting.

## 1. Introduction
The project aims to develop and deploy a Learning Management System (LMS) within a 12-week timeline. This report documents the project plan, configuration management, risk and change strategies, and artifacts produced.

## 2. Report Layout
Formatted in Arial 12pt. Screenshots and the Gantt chart are included where indicated.

## 3. Task 1: Project Plan
### Scope Statement
Objective: Develop and deploy an LMS by Dec 23, 2025. Deliverables: Functional LMS, documentation, deployment, report, presentation.

### Gantt Chart
Include the Gantt chart image here:

![Gantt Chart](gantt_chart.svg)

### Risks & Issues
- Code bugs — Mitigation: unit tests.
- Time overruns — Mitigation: buffer and prioritisation.

### Change Request Process
Log change in Jira, evaluate impact, implement on a feature branch and PR.

## 4. Task 2: Configuration Management
### GitHub
Repository structure:
- `public/` — static pages (index.html, login.html)
- `server.js` — demo server
- `docs/` — reports, gantt, slides

Insert GitHub screenshots:

![GitHub commits](docs/screenshots/github_commits.png)

### Jira
Insert Jira board screenshot:

![Jira board](docs/screenshots/jira_board.png)

## 5. Prototype Demo
Open the demo at `http://localhost:3000` and show the login page screenshot:

![Login page](docs/screenshots/login_page.png)

## 6. Conclusion
Summarise readiness for submission and presentation.

## 7. References
[1] PMI PMBOK 7th ed.
[2] Atlassian Jira docs
[3] GitHub docs

---
Instructions to export to PDF:
- Open this markdown in VS Code and use the Markdown PDF extension, or use Pandoc:

pandoc docs/LMS_Project_Report_Final.md -o docs/LMS_Project_Report.pdf --from markdown

Ensure all referenced images exist in `docs/screenshots/` before exporting.

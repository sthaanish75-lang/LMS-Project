# LMS-Project

A minimal Learning Management System (LMS) demo and project artifacts for the "Development and Deployment of a Learning Management System" assessment.

Prerequisites
- Node.js (LTS) installed and available on PATH
- Git (for version control)

Quickstart (PowerShell)
1. Open PowerShell and go to the project folder:

```powershell
cd C:\Users\sthaa\LMS-Project
```

2. Install dependencies and start the demo server:

```powershell
npm install
npm start
```

3. Open the demo in your browser:

- http://localhost:3000  (index)
- http://localhost:3000/login  (login page)

Project layout
- `public/` — static demo pages (index.html, login.html)
- `server.js` — minimal Express server to serve `public/`
- `docs/` — project plan, Gantt chart, presentation outline and report drafts

Branches
- `main` — primary branch
- `develop` — integration branch (create PRs into this branch)
- `feature/*` — feature branches (e.g. `feature/login-page`)

Add screenshots
- Save screenshots to `docs/screenshots/` (e.g., `login_page.png`, `github_commits.png`) and commit them for inclusion in the final report.

If you need help running the server or generating the final report/PPTX, tell me what step you want me to do next.

This repository contains the demo and project artifacts for the "Development and Deployment of a Learning Management System (LMS) for Online Education" individual assessment.

Contents:
- public/: static demo pages (index.html, login.html)
- server.js: minimal Express server to serve demo pages
- docs/: project plan, Gantt CSV, and report draft

Quickstart (local):
1. Install Node.js (LTS) from https://nodejs.org/ and ensure `node` and `npm` are on your PATH.
2. From the repository root, install dependencies and start the server:

```powershell
npm install
npm start
```

3. Open your browser and go to http://localhost:3000 for the demo index page, or http://localhost:3000/login for the login page.

Project artifacts and next steps:
- docs/gantt_chart_data.csv — CSV used to generate the Gantt chart.
- docs/Project_Plan.md — Project plan and scope statement.
- docs/LMS_Project_Report.md — Draft report ready for screenshots and finalization.

If you want, I can:
- Generate a Gantt chart PNG from the CSV and add it to docs/.
- Create the PPTX slides and a finished PDF report.

Contact: Work through the todo list in the repository root or ask me to continue with the next step.
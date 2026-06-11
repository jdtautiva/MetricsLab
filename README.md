# MetricsLab — Innovation Metrics Decision Simulator

> **Interactive managerial economics simulator focused on innovation metrics, business model evaluation, and financial decision-making.**  
> Developed for the **Managerial Economics** course by **Julián Díaz Tautiva, PhD**

---

## Overview

**MetricsLab** is a browser-based pedagogical simulation tool designed for undergraduate innovation and managerial economics courses. Students work in teams and take the role of managers evaluating an innovation-based venture. Across four decision rounds, they must select a business case, define a business model, choose validation metrics, make operational and commercial decisions, and evaluate whether the project should be scaled, pivoted, or abandoned.

The simulator emphasizes the managerial use of economic and financial indicators in innovation contexts. Students practice how business model choices, actionable metrics, cost structures, pricing, validation experiments, and investment indicators interact in the evaluation of an entrepreneurial project.

The simulator runs entirely as a single self-contained HTML file — no backend, no installation, and no external dependencies are required beyond a modern web browser. It can be served from any web server, uploaded to GitHub Pages, or opened locally.

---

## Learning Objectives

By completing the simulation, students are able to:

- Evaluate the internal coherence of a business model by connecting customer segment, value proposition, and revenue logic
- Distinguish between **actionable metrics** and **vanity metrics** in innovation and startup decision-making
- Select validation experiments according to their business purpose, scope, and expected managerial learning
- Analyze how pricing, marketing, product development, support, retention, analytics, capacity, and partnerships affect business viability
- Calculate and interpret break-even point, contribution margin, operating profit, and benefit-cost ratio
- Apply traditional financial indicators such as **NPV**, **IRR**, and **payback period**
- Apply advanced decision criteria such as **Equivalent Annual Value (EAV/VAE)** and **NPV Index (IVAN)**
- Justify managerial decisions using written economic reasoning
- Interpret dashboards and financial projections to recommend whether to scale, pivot, or abandon an innovation project

---

## Key Features

**Six differentiated cases** — teams select among six innovation contexts, enabling variation across groups while preserving a common decision framework.

**Team registration** — students enter the team name and the names of all participants before beginning the simulation. This information is included in the final report.

**Business model evaluation** — students choose among B2C Freemium, B2B Institutional, and Marketplace models, connecting the revenue model with a priority segment and value proposition.

**Metrics selection** — students select three metrics and must distinguish between vanity metrics and actionable metrics. The simulator rewards stronger managerial learning when teams prioritize actionable indicators such as retention, conversion, CAC, activation, and margin.

**Eight validation experiments** — students select from multiple validation approaches, including landing page tests, pilots, interviews, A/B pricing tests, concierge MVPs, smoke tests, onboarding tests, and pre-sales or letters of intent. Each experiment includes a brief explanation of its scope and potential business objective.

**Operational and commercial decision grid** — the third round includes 10 decisions presented in a two-column, five-row structure. These decisions affect adoption, CAC, fixed costs, variable costs, conversion, retention, operating profit, and break-even point.

**Mandatory managerial rationale** — after each decision round, teams must write a rationale of at least 300 characters explaining the logic behind their choices. These written responses are stored and included in the final report.

**Financial dashboard** — the simulator automatically calculates operating and financial indicators, including revenue, costs, operating profit, contribution margin, break-even point, benefit-cost ratio, NPV, IRR, payback period, VAE/EAV, and IVAN.

**Internal financial line chart** — the financial projection in Round 4 includes a native SVG line chart showing the evolution of projected cash flows and cumulative cash flows over time. No external charting library is required.

**Final report** — at the end of the simulation, teams receive a complete closing report showing selected case, participants, all decisions, written rationales, performance score, dashboard indicators, financial projections, and discussion questions.

**PDF export** — the final report can be exported to PDF using the browser’s native print functionality. Print-specific CSS is included to produce a clean report format.

## Technical Details

| Attribute | Detail |
|---|---|
| Format | Single `.html` file, fully self-contained |
| Dependencies | None |
| Backend required | None |
| External libraries | None |
| Chart rendering | Native SVG generated inside the HTML |
| PDF export | Browser-native print/export to PDF |
| Storage | Runtime state handled in JavaScript |
| Browser support | Any modern browser: Chrome, Firefox, Safari, Edge |
| Screen | Desktop optimized; responsive down to tablet |
| Language | Spanish |
| Estimated duration | 15–20 minutes |
| Course context | Managerial Economics |
| Instructor attribution | Julián Díaz Tautiva, PhD |

---
## Suggested Citation

Díaz Tautiva, J.A. (2026). *MetricsLab — Innovation Metrics Decision Simulator*. Managerial Economics teaching simulator.

---
## License
This project is intended for educational use. Add the preferred license for your course, institution, or repository before publication.

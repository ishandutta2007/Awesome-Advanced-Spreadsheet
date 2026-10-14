# Awesome-Advanced-Spreadsheet

## Top Advanced Spreadsheet Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Relational Data, Collaboration & Programmable Spreadsheets*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Advanced Spreadsheets**. These tools go beyond traditional grid-based calculation — offering relational data models, API access, automation, and programmable cells for building applications on top of spreadsheet interfaces.



**Examples** include Google Sheets, Microsoft Excel, Airtable, Smartsheet, Coda, Rows, Equals, GRID, Clay, and Quadratic (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, relational data modeling, and open spreadsheet infrastructure — ideal for teams seeking transparent, vendor-independent spreadsheet-database hybrids.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Google Sheets](https://workspace.google.com/products/sheets/)**  

  Cloud-based spreadsheet with real-time collaboration, Google Apps Script automation, and extensive add-on ecosystem. Free with Google account; Workspace plans add enterprise controls.



- **[Microsoft Excel](https://www.microsoft.com/microsoft-365/excel)**  

  Industry-standard spreadsheet with Power Query, Power Pivot, VBA, and Copilot AI. Desktop, web, and mobile versions. Microsoft 365 subscription required for full features.



- **[Airtable](https://www.airtable.com/)**  

  Spreadsheet-database hybrid with relational links, multiple view types (grid, kanban, calendar, gallery), automations, and API access. Popular for project tracking and lightweight apps.



- **[Smartsheet](https://www.smartsheet.com/)**  

  Work management platform with spreadsheet interface, Gantt charts, resource tracking, and portfolio rollups. Targets enterprise project management.



- **[Coda](https://coda.io/)**  

  Doc-platform hybrid blending documents with tables, buttons, and formulas. Known as "docs that can do things" with automation and integrations.



- **[Rows](https://rows.com/)**  

  Spreadsheet with built-in data integrations (APIs, databases) and sharing. Focuses on making data connections native to the grid.



- **[Equals](https://equals.com/)**  

  Spreadsheet built for finance and analytics teams. Features SQL, Python, and database connections directly in cells. Version control and audit trails.



- **[GRID](https://grid.is/)**  

  Spreadsheet platform for publishing interactive models and calculators. Turns spreadsheets into web apps with formulas hidden.



- **[Clay](https://clay.com/)**  

  Data enrichment and outreach automation spreadsheet. Combines 100+ data providers into a single interface for GTM teams. Credit-based pricing.



- **[Quadratic](https://quadratichq.com/)**  

  Source-available spreadsheet supporting Python, SQL, and Formulas. Built for technical users needing code and grid in one interface .



## Open-Source GitHub Projects



- **[Grist](https://github.com/gristlabs/grist-core)**  

  Modern relational spreadsheet (Apache-2.0) combining spreadsheet UI with database structure. 5,000 rows free, 150,000 paid. Python formulas in cells, granular RBAC, and SQLite storage for data portability. Self-hostable. Positioned as open-source Smartsheet alternative .



- **[Baserow](https://github.com/baserow/baserow)**  

  Open-source no-code database platform (MIT) and Airtable alternative. Spreadsheet-database hybrid with automations, dashboards, and AI assistant (Kuma). 150,000+ users. GDPR, HIPAA, and SOC 2 Type II compliant. Docker deployment. Full data ownership with no vendor lock-in .



- **[NocoDB](https://github.com/nocodb/nocodb)**  

  Open-source Airtable alternative (AGPL-3.0) that turns any database into a smart spreadsheet. Grid, gallery, kanban, form views, and auto-generated REST/GraphQL APIs. Scales to millions of rows. Self-hosted with PostgreSQL/MySQL backends .



- **[LibreOffice Calc](https://github.com/LibreOffice/core)**  

  Full-featured open-source spreadsheet (MPL-2.0) for Windows, Linux, BSD, and macOS. Excel-compatible with .xlsx read/write, formula support, pivot tables, and macros. Part of the LibreOffice suite .



- **[Gnumeric](https://github.com/GNOME/gnumeric)**  

  Lightweight open-source spreadsheet (GPL-2.0) for GNOME desktop. Reasonably lightweight but with advanced features including statistical analysis and accurate numerical computation .



- **[Apache OpenOffice Calc](https://github.com/apache/openoffice)**  

  Open-source spreadsheet (Apache-2.0) started as StarOffice. Excel-compatible with macro support. Note: has not received major updates since 2014 .



- **[SimpleSpread](https://github.com/baudehlo/SimpleSpread)**  

  Native macOS spreadsheet app (open-source) written entirely in Swift. XLSX native with formula engine covering Google Sheets' core feature set (157 functions). Pivot tables, CSV handling, and launch performance 2.6-2.7× faster than Apple Numbers in benchmarks .



- **[pyspread](https://gitlab.com/pyspread/pyspread)**  

  Non-traditional spreadsheet (GPL-3.0) that expects Python expressions in grid cells. Each cell returns a Python object accessible from other cells. Can represent lists or matrices. The most Pythonic spreadsheet .



- **[SoloSheet](https://github.com/sologrove/solosheet)**  

  Local, private spreadsheet (GPL-3.0) built on the open `.sheet` format — clean JSON that any person, program, or AI can parse. Wiki-linked sheets with formulas like `=[[sales]]!B4`. 100% offline, zero telemetry, no accounts. Lean by design .



- **[JamAIBase](https://github.com/EmbeddedLLM/JamAIBase)**  

  Collaborative spreadsheet for AI (open-source). Chain cells into powerful pipelines, experiment with prompts and models, and evaluate LLM responses in real-time .



- **[Worklenz](https://github.com/Worklenz/worklenz)**  

  Open-source project management tool (AGPL-3.0) with spreadsheet-like task tracking, extended Kanban board, recurring tasks, and custom fields. Node.js, PostgreSQL, and S3-compatible storage. Docker deployment .



### Additional Strong Open-Source Options



- **[EtherCalc](https://github.com/audreyt/ethercalc)** — Open-source web spreadsheet (CPAL) for real-time collaborative editing .

- **[ONLYOFFICE Community Server](https://github.com/ONLYOFFICE/CommunityServer)** — Open-source office suite (AGPL-3.0) with spreadsheet editor compatible with Excel formats .

- **[Collabora Online Calc](https://github.com/CollaboraOnline/online)** — Enterprise-ready LibreOffice for cloud (MPL-2.0) .

- **[HyperFormula](https://github.com/handsontable/hyperformula)** — Headless TypeScript spreadsheet calculation engine (GPL-3.0 or commercial). ~420 built-in functions for embedding spreadsheet logic in apps .

- **[SheetJS](https://github.com/SheetJS/sheetjs)** — Spreadsheet data toolkit (Apache-2.0) for parsing and writing Excel files. 35k+ GitHub stars .

- Community **n8n** workflows for spreadsheet automation and data enrichment pipelines.



**Frameworks for building custom systems**: Combine **Grist** or **Baserow** as the relational spreadsheet-database core with **NocoDB** for API-first data access, **HyperFormula** for embedded calculation engines, **SheetJS** for Excel file interoperability, and **PostgreSQL/SQLite** for persistence — creating a fully self-hosted, enterprise-grade advanced spreadsheet platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Advanced spreadsheets handling business data must comply with data protection regulations (GDPR, CCPA, etc.).

- Self-hosted open-source solutions require proper security hardening, backup strategies, and ongoing maintenance. Relational spreadsheet-database hybrids introduce database administration responsibilities that traditional spreadsheets do not.



---



**Made for operations teams, data analysts, builders, and developers seeking transparent spreadsheet solutions.**  

Let's make Advanced Spreadsheets more open, data-driven, and relational.

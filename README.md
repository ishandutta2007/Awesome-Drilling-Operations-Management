# Awesome-Drilling-Operations-Management

# Top Drilling Operations Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Well Planning, Real-Time Monitoring & Drilling Performance Optimization*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Drilling Operations Management**. These tools manage well planning, real-time drilling data, non-productive time (NPT) analysis, and operational performance optimization for oil & gas operators, drilling contractors, and service companies.

**Examples** include SLB DrillPlan, NOV WellData, Halliburton DecisionSpace, Corva, RigER, Pason, WellDatabase, Peloton WellView, Seeq, and Weatherford Centro (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom well trajectory planning, and transparent drilling data management — ideal for drilling engineers, data scientists, and developers building vendor-independent drilling solutions. The open-source ecosystem is anchored by **welleng** (trajectory planning), **Witsml Explorer** (WITSML data management), and **witskit** (WITS data processing), with strong coverage in drilling analytics, NPT calculation, and directional drilling web applications.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[SLB DrillPlan](https://www.slb.com/)**  
  Cloud-based well planning and drilling engineering software covering trajectory design, casing design, hydraulics, and wellbore stability. Part of the SLB digital drilling ecosystem.

- **[NOV WellData](https://www.nov.com/)**  
  Real-time drilling data aggregation and management platform providing WITSML connectivity, data visualization, and operational dashboards.

- **[Halliburton DecisionSpace](https://www.halliburton.com/)**  
  Integrated exploration and production software suite with drilling operations modules for well planning, real-time monitoring, and performance analysis.

- **[Corva](https://www.corva.ai/)**  
  Real-time drilling and completions analytics platform with AI-powered performance monitoring, NPT detection, and operational optimization for operators and service companies.

- **[RigER](https://www.riger.com/)**  
  Cloud-based drilling and well servicing management software with scheduling, reporting, and invoicing for drilling contractors.

- **[Pason](https://www.pason.com/)**  
  Real-time drilling data monitoring and reporting platform providing rig instrumentation, electronic drilling recorder (EDR) data, and operational dashboards.

- **[WellDatabase](https://www.welldatabase.com/)**  
  Cloud-based well data management and drilling reporting platform with daily reports, NPT tracking, and performance analytics.

- **[Peloton WellView](https://www.peloton.com/)**  
  Industry-standard well data management and drilling reporting software covering the full well lifecycle from planning through completion. Tracks daily drilling reports, NPT, and operational performance.

- **[Seeq](https://www.seeq.com/)**  
  Advanced analytics and time-series data platform widely used in oil & gas for drilling performance analysis, NPT investigation, and operational optimization.

- **[Weatherford Centro](https://www.weatherford.com/)**  
  Real-time drilling optimization platform with automated drilling control, performance monitoring, and NPT reduction capabilities.

## Open-Source GitHub Projects

- **[welleng](https://github.com/jonnymaserati/welleng)**  
  The most widely adopted open-source collection of well engineering tools, focused on well trajectory planning and anti-collision analysis. Python-based with 110+ stars on GitHub . Features survey management, well trajectory calculation, ISCWSA standard well paths, collision detection using exact Mahalanobis separation factor, kick-tolerance engine, and tortuosity index calculation. Includes a curve-hold-curve point-to-target solver using analytical methods. MIT-licensed with extensive academic citations and validation against published methods.

- **[Witsml Explorer](https://github.com/equinor/witsml-explorer)**  
  Open-source data management tool from Equinor for browsing and editing data directly on WITSML servers. Runs in the browser or as a local desktop application with a simple installer. Connects to any WITSML server running version 1.4.1.1 . Supports comprehensive WITSML objects including wells, wellbores, bharuns, changelogs, fluidsreports, formation markers, log objects, curves, messages, mudlogs, geology intervals, rigs, risks, trajectories, tubulars, and wbgeometries . Features copy objects between different servers, URL deep linking, WITSML query editor, and QA/QC jobs on logs and curves (edit, splice, compare, analyze gaps, trim, offset) . Apache-2.0 licensed.

- **[witskit](https://github.com/Critlist/witskit)**  
  Comprehensive Python SDK for processing WITS (Wellsite Information Transfer Standard) data in the oil & gas drilling industry. Parses raw WITS frames into structured, validated Python objects with 724 symbols across 20+ record types auto-parsed from the spec . Features CLI tools for symbol search, frame decoding, and validation. Production-ready SQL storage for SQLite, PostgreSQL, or MySQL databases. Time-series analysis for querying historical drilling data with time-based filtering. Modular architecture with plug-and-play transports (serial, TCP) and outputs (SQL, JSON). Type-checked with pydantic for data integrity .

- **[directional_drilling](https://github.com/faridrafati/directional_drilling)**  
  Web-based directional drilling application built with TypeScript, React, Three.js, Fastify, and Prisma. Ported from ~19k lines of Delphi/Pascal trajectory math and UI . Features 30+ profile types including CH→D3DS chained profiles with min-DLS hints on failure. 3D wellbore viewer with tubular mesh rendering, field scene with grid visualization, and compass markers. Field map support with `.grd` parser (Petrel ASCII grid format), coloured raster display, marching-squares contours, and volume calculator. Reports export to PDF (multi-page A4 via pdfmake) and XLSX (via SheetJS) with columns for MD, Incl, Azm, TVD, VSEC, NS, EW, DLS, TF, BR, TR, DMD . Undo/redo with 50-deep history, debounced autosave, and CSV import for bulk data loading.

- **[well_profile](https://github.com/pro-well-plan/well_profile)**  
  Python tool for well trajectory calculation with 82+ stars on GitHub . Part of the pro-well-plan organization providing open-source well engineering tools. Includes related repositories for torque and drag calculations (torque_drag) and temperature analysis (pwptemp) .

- **[drilling_mcp_server](https://github.com/ridhadev/drilling_mcp_server)**  
  MCP (Model Context Protocol) server for oil and gas drilling data analysis. Provides tools, resources, and prompt templates for analyzing drilling data from CSV files, with support for Rate of Penetration (ROP), Mechanical Specific Energy (MSE), Non-Productive Time (NPT) calculations, and data visualization . Features tools for listing wells, inspecting headers, calculating ROP/MSE/NPT, plotting data, and filtering by time or depth windows. Designed for integration with AI clients like Claude Desktop .

- **[Drill AI Intelligence Platform](https://github.com/ahmadaijaz1030/Drill-AI-Platform)**  
  Comprehensive AI-powered oil drilling data management platform built with React, Node.js, and AWS services. Automates data processing from Excel/CSV uploads, provides real-time visualization of rock composition, DT, and GR data . Features an intelligent chatbot for drilling-related queries, voice interaction capabilities, file attachment support, and secure cloud storage. Responsive design for desktop, tablet, and mobile access .

- **[Oil Field Integrated Reservoir & Operations Dashboard](https://github.com/sattar-almohsin/Oil-Field---Integrated-Reservoir-Operations-Dashboard)**  
  Streamlit-based web application for reservoir surveillance and well operations analysis using the Volve field production dataset . Features field-level KPIs, individual well production analysis, performance comparisons with rolling averages, intervention candidate ranking with weighted scoring, decline curve analysis (Arps exponential and hyperbolic), configurable alerts, and PDF report generation . Python, Streamlit, Pandas, Plotly stack.

- **[Drilling Management Studio](https://github.com/gewazy/DrillingManagementStudio)**  
  Postgraduate project for organizing and controlling the work of a drilling team on seismic projects . Demonstrates database systems design for drilling operations management.

### Additional Strong Open-Source Options

- **DCDM (Drilling Data Collection and Management)** — Node.js-based system for collecting and visualizing digital information from well construction contractors. Features web interface, user access separation, retrospective viewing, geological section building in 3D/2D, WITS0 and WITSXML protocol data reception, and computed variable support .
- **wellbrief** — Offline-first RAG system for drilling engineers that ingests well files, provides answers with verbatim-verified citations, and generates pre-spud offset-well risk briefs with NPT cost and mitigations quoted from end-of-well reports .
- **welltrajconvert** — Calculate directional survey metadata points along the wellbore. Python-based .
- **WellTrajectoryCalculator** — C++ implementation for directional well trajectory calculation based on drillingmanual.com methodologies .
- **OpenGeoPlotter** — PyQt5 application for visualizing geologic drill hole data with cross-sections, 3D views, strip logs, and downhole line plots .

**Frameworks for building custom drilling operations solutions**: Combine **welleng** for well trajectory planning and anti-collision analysis, **Witsml Explorer** for WITSML data management and QA/QC, and **witskit** for WITS data decoding and time-series storage. Use **directional_drilling** for a complete web-based directional drilling application with 3D visualization and PDF/XLSX export. Integrate **drilling_mcp_server** for AI-assisted drilling data analysis with ROP, MSE, and NPT calculations. Note that true enterprise drilling operations platforms with real-time rig instrumentation, automated drilling control, and integrated NPT analytics remain primarily commercial territory; open-source stacks provide strong trajectory planning, data management, and analytics foundations that require integration for complete operations management.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Drilling operations tools must comply with industry standards (IADC, API), safety regulations, and environmental requirements.
- Self-hosted open-source solutions require proper infrastructure, petroleum engineering expertise, and ongoing maintenance. Well trajectory calculations and anti-collision analysis should be validated against industry-standard methods before field deployment.
- The open-source ecosystem provides strong trajectory planning, WITSML/WITS data management, and drilling analytics foundations, but real-time rig instrumentation, automated drilling control, and enterprise NPT analytics remain primarily a commercial offering.

---

**Made for drilling engineers, well planners, drilling contractors, and petroleum data scientists.**  
Let's make drilling operations management more open, transparent, and data-driven.

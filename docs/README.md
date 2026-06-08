# OctoAcme Project Management Docs

This folder contains the core process documentation for managing projects at OctoAcme.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured five-phase project lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. The Initiation phase validates business need through a lightweight One-pager that captures the problem statement, success metrics, stakeholders, and resource needs—serving as a decision gate before committing to planning. Once approved, the Planning phase transforms the initiative into an actionable backlog broken into shippable increments, with clear acceptance criteria, dependency mapping, and a defined Definition of Done. This sequential approach ensures stakeholder alignment and measurable outcomes before execution begins, while maintaining flexibility through iterative delivery of small, testable increments.

OctoAcme operates with clear ownership across four core personas: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes and prioritize the backlog; **Developers** implement features and collaborate on design; and **QA/Testing** validates quality against acceptance criteria. Communication is structured through a consistent cadence—daily standups (15 minutes) focus on progress and blockers, weekly syncs between PM and Product Lead ensure alignment, twice-weekly standups keep the delivery team synchronized, and monthly stakeholder updates maintain transparency. Risk escalation follows a tiered model: Level 1 triage happens in daily standups, Level 2 involves PM escalation to Product Leadership and dependent teams, and Level 3 reaches sponsor-level for business-impacting issues.

During execution, teams use GitHub Projects with a standardized workflow (Backlog → Ready → In Progress → In Review → QA → Done) and maintain small PRs (≤400 lines) with automated CI testing and linting before review. Quality assurance is comprehensive—unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI—supported by velocity and burndown tracking. For releases, OctoAcme follows a pre-release checklist ensuring all acceptance criteria are met, CI and security scans pass, and rollback plans are documented. Post-deployment, the team verifies success metrics and communicates updates to stakeholders. The lifecycle closes with retrospectives that capture learnings and convert them into actionable improvements, creating a continuous feedback loop that refines processes iteratively.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Documentation Index

- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to our approach, roles, and key artifacts
- [Project Initiation Guide](./octoacme-project-initiation.md) — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- [Project Planning Guide](./octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog for delivery
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Guidance for managing day-to-day execution and tracking progress toward project milestones
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks and dependencies
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardized processes to reduce release risk and improve observability
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements
- [Roles & Personas](./octoacme-roles-and-personas.md) — Definitions of core roles and responsibilities across projects

---

**Add new documents as needed to grow our project operations knowledge base.**

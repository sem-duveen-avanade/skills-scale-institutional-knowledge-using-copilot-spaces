# OctoAcme Project Management Docs

This README provides a quick overview of OctoAcme's project management approach and links to the core process documentation. Use it as the starting point for understanding how projects are initiated, planned, executed, released, reviewed, and continuously improved.

## Project Management Process Overview

OctoAcme follows a structured five-phase lifecycle that moves projects from **Initiation** through **Planning**, **Execution**, **Release**, and finally **Close & Retrospective**. The process begins with validation and stakeholder alignment through a lightweight Project One-pager that captures the problem statement, success metrics, and resource needs. Once approved, the team enters Planning, where work is broken into shippable increments with clear acceptance criteria, dependencies are identified, and a release plan is established. During Execution, the team maintains a disciplined rhythm of daily standups, weekly delivery syncs, and demos at sprint milestones, using a project board with defined workflow columns (Backlog → Ready → In Progress → In Review → QA → Done). This iterative approach emphasizes delivering small, testable increments while maintaining transparency through consistent documentation and status reporting.

OctoAcme operates with clear role ownership: a **Project Manager** coordinates delivery, manages risks and timelines, and facilitates cross-team communication; a **Product Manager** defines outcomes, prioritizes the backlog, and measures success; **Developers** implement features with quality and maintainability in mind; and **QA/Testing** validates acceptance criteria. The communication cadence includes weekly syncs between PM and Product Manager, twice-weekly standups for the delivery team, monthly stakeholder updates, and ad-hoc escalations as needed. Risk escalation follows a structured path: team-level triage in standups → PM escalation to Product Lead and dependent teams → sponsor-level escalation for business-impacting issues. This clear governance ensures stakeholders remain informed and aligned while enabling the team to surface and resolve blockers quickly.

Quality is embedded throughout OctoAcme's execution model through mandatory unit tests, integration tests where applicable, end-to-end smoke tests for critical flows, and CI-integrated security scanning. Pull requests are kept small (≤400 lines when possible), require at least one approval, and include issue links and acceptance criteria in their descriptions. Before any release—whether patch, minor, or major—the team verifies that all acceptance criteria are met, passing CI and security scans, and has prepared release notes and a rollback plan. Post-deployment verification and stakeholder announcements complete the release process. This rigor is reinforced through regular retrospectives after sprints and releases, where the team captures learnings, prioritizes 2–3 actionable improvements, and tracks their impact—creating a continuous improvement culture grounded in psychological safety and data-informed decision-making.

## Core Principles

OctoAcme projects use a collaborative, iterative approach:
- **Customer-first**: Prioritize customer value and usability.
- **Iterative delivery**: Deliver small, testable increments.
- **Clear ownership**: Each project has a named Project Manager and Product Lead.
- **Data-informed decisions**: Measure impact and iterate based on evidence.
- **Psychological safety**: Encourage feedback and learning.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — Concise introduction to roles, principles, key artifacts, and the high-level lifecycle.
- [Project Initiation Guide](octoacme-project-initiation.md) — Initial steps to validate work, align stakeholders, and create a lightweight plan.
- [Project Planning](octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and prioritized backlog.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Manage day-to-day execution, team rhythm, quality standards, and progress tracking.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies; stakeholder communication templates.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardize releases to production with pre-release requirements, deployment checklist, and rollback procedures.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements.
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed definitions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities.

## Getting Started

1. **New to OctoAcme projects?** Start with [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction to roles and lifecycle.
2. **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) to validate the idea and align stakeholders.
3. **Planning a project?** Use [Project Planning](octoacme-project-planning.md) to create your backlog and release plan.
4. **Executing a project?** Refer to [Execution & Tracking](octoacme-execution-and-tracking.md) for workflows, quality standards, and team rhythm.
5. **Releasing to production?** Follow the [Release & Deployment Guide](octoacme-release-and-deployment.md) for pre-release checks and deployment procedures.
6. **Wrapping up?** Use [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to capture learnings and drive improvements.

## Contributing

Additions or improvements to these docs are welcome via pull request or by using the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) in this repository.

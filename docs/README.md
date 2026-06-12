# OctoAcme Project Management Docs

This README provides a quick overview of OctoAcme's project management approach and links to the core process documentation. Use it as the starting point for understanding how projects are initiated, planned, executed, released, reviewed, and continuously improved.

## Project Management Process Overview

OctoAcme follows a structured five-phase lifecycle that moves projects from **Initiation** through **Planning**, **Execution**, **Release**, and finally **Close & Retrospective**. The process begins with validation and stakeholder alignment through a lightweight Project One-pager that captures the problem statement, success metrics, and resource needs. Once approved, the team enters Planning, where work is broken into shippable increments with clear acceptance criteria, dependencies are identified, and a release plan is established.

During Execution, the team maintains a disciplined rhythm of daily standups, weekly delivery syncs, and demos at sprint milestones, using a project board with defined workflow columns (Backlog → Ready → In Progress → In Review → QA → Done). This iterative approach emphasizes delivering small, testable increments while maintaining transparency through consistent documentation and status reporting.

### Roles & Communication

OctoAcme operates with clear role ownership: a **Project Manager** coordinates delivery, manages risks and timelines, and facilitates cross-team communication; a **Product Manager** defines outcomes, prioritizes the backlog, and measures success; **Developers** implement features with quality and maintainability in mind; and **QA/Testing** validates acceptance criteria. The communication cadence includes weekly syncs between PM and Product Manager, twice-weekly standups for the delivery team, monthly stakeholder updates, and ad-hoc escalations as needed. Risk escalation follows a structured path: team-level triage in standups → PM escalation to Product Lead and dependent teams → sponsor-level escalation for business-impacting issues.

### Quality & Release Excellence

Quality is embedded throughout OctoAcme's execution model through mandatory unit tests, integration tests where applicable, end-to-end smoke tests for critical flows, and CI-integrated security scanning. Pull requests are kept small (≤400 lines when possible), require at least one approval, and include issue links and acceptance criteria in their descriptions. Before any release—whether patch, minor, or major—the team verifies that all acceptance criteria are met, passing CI and security scans, and has prepared release notes and a rollback plan. This rigor is reinforced through regular retrospectives after sprints and releases, where the team captures learnings, prioritizes improvements, and tracks their impact.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — Concise introduction to OctoAcme's approach, roles, and key artifacts
- [Project Initiation Guide](octoacme-project-initiation.md) — Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan
- [Project Planning](octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog for delivery
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Guidance for managing day-to-day execution and tracking progress toward milestones
- [Risk Management & Communication](octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks and dependencies
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardize how OctoAcme releases features to production to reduce risk and improve observability
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements
- [Roles & Personas](octoacme-roles-and-personas.md) — Typical roles and responsibilities used in OctoAcme project docs and exercises

## Getting Started

1. **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md) for a high-level understanding.
2. **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) to validate the idea and align stakeholders.
3. **Ready to build?** Use [Project Planning](octoacme-project-planning.md) to structure your work and backlog.
4. **In progress?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md) during delivery.
5. **Preparing to ship?** Review the [Release & Deployment Guide](octoacme-release-and-deployment.md) before going live.
6. **Project complete?** Conduct a retrospective using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).

## Contributing

Additions or improvements to these docs are welcome. To suggest updates:

- **Small improvements?** Submit a pull request directly with your changes.
- **Significant additions or new docs?** Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to discuss and align on the change.

All process docs are versioned and tracked in this repository. Please keep them updated as OctoAcme's practices evolve.

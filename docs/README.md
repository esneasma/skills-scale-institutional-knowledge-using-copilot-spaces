# OctoAcme Project Management Docs

Welcome to the central documentation for how OctoAcme manages projects. This space gives you access to all process guidance, templates, and best practices.

## Project Management Process Overview

OctoAcme follows a structured, lifecycle-driven approach to project management grounded in clear ownership, iterative delivery, and data-informed decision-making. The organization operates across five distinct phases:

1. **Initiation** — Validate business need and stakeholder alignment through a Project One-pager, ensuring success metrics are clear before moving forward
2. **Planning** — Break work into shippable increments with prioritized backlogs, acceptance criteria, and identified dependencies
3. **Execution & Tracking** — Deliver through sprints using daily standups, weekly syncs, and project boards to maintain visibility and manage blockers
4. **Release** — Standardize deployment with pre-release requirements, smoke tests, and documented rollback plans
5. **Close & Retrospective** — Capture learnings and convert them into actionable improvements for continuous process enhancement

Key principles underlying this approach include customer-first delivery, iterative improvement, clear ownership (each project has a named Project Manager and Product Lead), and collaboration across cross-functional teams.

### Core Roles & Responsibilities

- **Project Managers** — Coordinate delivery, manage schedules, risks, and communications; ensure consistent documentation and stakeholder alignment
- **Product Managers** — Define outcomes, prioritize the backlog, measure success, and validate solutions through data and research
- **Developers** — Implement features, write tests, collaborate on design, and help identify technical risks
- **QA/Testing** — Validate quality and acceptance criteria
- **Stakeholders** — Provide inputs, approvals, and business context

### Communication & Risk Management

OctoAcme maintains a disciplined communication cadence: daily standups (15 minutes), weekly PM + Product Manager syncs, twice-weekly delivery team standups, and monthly stakeholder updates. Risks are actively tracked in a Risk Register and escalated through a three-level path (team-level → PM → Product Lead → Sponsor), ensuring visibility and proactive mitigation.

### Quality & Continuous Improvement

Quality gates are embedded throughout execution: small pull requests (≤400 lines), automated CI testing and security scans, manual QA for feature acceptance, and retrospectives after each sprint or milestone. This creates a continuous cycle of learning and incremental process improvement.

---

## Process Documentation

### Getting Started
- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, core roles, key artifacts, and lifecycle

### Project Lifecycle
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- **[Project Planning](./octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day execution, track progress, and handle blockers and escalations
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production safely and predictably

### Cross-Cutting Processes
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies; maintain stakeholder alignment
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings after sprints, releases, or incidents; convert them into actionable improvements
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Detailed definitions of typical roles, responsibilities, goals, and communication patterns

---

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a high-level introduction, then explore process docs as needed.
- **Starting a new project?** Follow the [Initiation Guide](./octoacme-project-initiation.md) → [Planning](./octoacme-project-planning.md) → [Execution & Tracking](./octoacme-execution-and-tracking.md) path.
- **Preparing a release?** See the [Release & Deployment Guide](./octoacme-release-and-deployment.md).
- **Reflecting on a project?** Use the [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) guide.

## Contributing to Process Docs

To request updates or add content to these process documents:
- **Create an issue** using the "Add Content to Project Management Process Docs" template (found in `.github/ISSUE_TEMPLATE/`)
- **Submit a pull request** with proposed changes
- Reference related discussions or learnings from your project

Keep these docs living and relevant by sharing feedback and improvements with your team.

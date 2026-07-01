# OctoAcme Project Management Docs

This README provides a single place to find OctoAcme's project management process documents and a comprehensive overview of the processes used across all projects.

## OctoAcme Project Management Overview

OctoAcme operates on a structured yet iterative project lifecycle designed to deliver customer value with clear ownership and data-driven decisions. The organization emphasizes five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. At initiation, teams validate business needs and align stakeholders around a lightweight Project One-pager that captures the problem statement, success metrics, and key milestones. Once approved, the team moves into planning, where work is broken into shippable increments with clear acceptance criteria, dependencies are mapped, and a risk register is established. This approach ensures that every project has both a **Project Manager** (who coordinates delivery, schedules, and communications) and a **Product Manager** (who defines outcomes, prioritizes the backlog, and measures success), creating clear accountability and alignment across functions.

### Execution, Quality, and Team Rhythm

During execution, OctoAcme teams follow a disciplined cadence of daily standups (15 minutes), weekly delivery syncs, and sprint-based planning cycles. Work flows through a project board with columns spanning Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are kept small (≤400 lines when possible), include issue links and acceptance criteria, and require at least one approval before merging. Quality is baked into the process through unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows. Security scanning runs in CI before any code review, and manual QA validates feature acceptance as needed. This layered approach to quality—combining automated testing, code review, and strategic manual validation—ensures that teams ship reliable code while maintaining reasonable cycle times.

### Risk Management, Communication, and Continuous Improvement

OctoAcme treats risks and dependencies as first-class concerns, maintaining a risk register that tracks ID, description, impact, likelihood, owner, and mitigation status. Risks are monitored weekly during syncs and escalated through a clear three-level path: team-level triage → Product Manager escalation → sponsor-level escalation for business-impacting issues. Stakeholder communication is structured around weekly status templates that highlight progress, next steps, risks, blockers, and decisions needed, ensuring transparency across engineering, product, sales, and support teams. After each sprint, release, or milestone, the team conducts a blameless retrospective to capture what went well, identify improvements, and convert learnings into actionable backlog items with clear owners and due dates. This closed-loop approach to feedback and improvement reinforces a culture of psychological safety, continuous learning, and iterative refinement of both product and process.

## Project Management Processes (Summary)

- **Initiation**: Define project goals, scope, stakeholders, and initial success criteria; create a project charter and one-pager.
- **Planning**: Develop schedules, resource plans, risk registers, and communication plans; create milestones and deliverables with clear acceptance criteria.
- **Execution & Tracking**: Coordinate work, track progress with status updates, and maintain a single source of truth for tasks and decisions through project boards.
- **Risks & Communication**: Identify and escalate risks, maintain stakeholder communication channels, and document mitigation actions with clear escalation paths.
- **Release & Deployment**: Define release checklists, run release rehearsals, smoke tests, and coordinate deployments with rollback and incident playbooks.
- **Retrospective & Continuous Improvement**: Conduct post-release retrospectives, record action items with owners and due dates, and update processes based on learnings.
- **Roles & Personas**: Define responsibilities for Project Managers, Product Managers, Developers, QA/Testing, and Stakeholders.

## Documentation (Links)

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, artifacts, and lifecycle
- [Project Initiation](./octoacme-project-initiation.md) — Steps to validate business need, align stakeholders, and authorize work
- [Project Planning](./octoacme-project-planning.md) — Breaking work into shippable increments with dependencies and risk management
- [Execution and Tracking](./octoacme-execution-and-tracking.md) — Day-to-day execution, team rhythm, quality practices, and blocker escalation
- [Risks and Communication](./octoacme-risks-and-communication.md) — Risk register management, stakeholder communication, and escalation paths
- [Release and Deployment](./octoacme-release-and-deployment.md) — Release types, pre-release requirements, deployment checklist, and rollback procedures
- [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Running retrospectives and converting learnings into action items
- [Roles and Personas](./octoacme-roles-and-personas.md) — Detailed role definitions for Developers, Product Managers, and Project Managers

## Getting Started

**New team members**: Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand OctoAcme's core principles and roles.

**Starting a new project**: Follow the [Project Initiation](./octoacme-project-initiation.md) guide to validate the project and get stakeholder alignment.

**Planning a project**: Use the [Project Planning](./octoacme-project-planning.md) guide to break work into actionable items and identify dependencies.

**During execution**: Reference the [Execution and Tracking](./octoacme-execution-and-tracking.md) guide for team rhythm, quality practices, and escalation procedures.

**Managing risks**: Consult the [Risks and Communication](./octoacme-risks-and-communication.md) guide to identify, assess, and communicate risks and dependencies.

**Preparing for release**: Use the [Release and Deployment](./octoacme-release-and-deployment.md) guide to ensure quality and coordinate deployments.

**After project completion**: Run a retrospective using the [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) guide to capture learnings.

## Contributing to Process Docs

To propose updates or additions to these process documents, use the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).

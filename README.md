# OctoAcme Project Management Docs

This README is the central entry point for OctoAcme's project-management documentation. Use it to quickly find the right process guide and to understand how OctoAcme moves work from project intake through planning, delivery, release, and retrospective improvement.

## Documentation Map

- [Project Management Overview](docs/octoacme-project-management-overview.md) - high-level principles, lifecycle, roles, artifacts, and communication cadence
- [Project Initiation](docs/octoacme-project-initiation.md) - one-pager, stakeholder alignment, initial risks, resource needs, and go/no-go decision
- [Project Planning](docs/octoacme-project-planning.md) - kickoff, backlog creation, estimation, Definition of Done, dependencies, and milestone planning
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md) - team rhythm, project-board workflow, pull-request expectations, reporting, and escalation
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md) - risk register, stakeholder updates, status templates, and escalation paths
- [Release & Deployment](docs/octoacme-release-and-deployment.md) - release types, pre-release requirements, deployment checklist, rollback guidance, and release notes
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md) - retrospective structure, improvement tracking, and follow-up expectations
- [Roles & Personas](docs/octoacme-roles-and-personas.md) - responsibilities and communication patterns for developers, product managers, and project managers

## Process Summary

OctoAcme uses a structured, iterative project lifecycle: initiation, planning, execution, release, and retrospective improvement. Work begins with a lightweight one-pager that defines the problem, goals, success metrics, stakeholders, timeline, initial risks, and resource needs. Once success metrics, priority, and team availability are clear, the team moves into planning to create a prioritized backlog, define acceptance criteria and Definition of Done, map milestones, and document dependencies and release expectations.

Delivery is coordinated through clear ownership across core roles. Project Managers coordinate schedules, risks, dependencies, documentation, and stakeholder communication. Product Managers define outcomes, prioritize work, and measure success. Developers implement and test features, contribute to estimates, and surface technical risks, while QA and testing support validates quality and acceptance criteria. Stakeholders and sponsors provide inputs, approvals, and escalation support when needed.

Execution relies on a consistent operating rhythm and shared artifacts. Teams use daily standups, weekly delivery syncs, and sprint or milestone demos to review progress, blockers, dependencies, and risks. Work is tracked on a project board that moves items through Backlog, Ready, In Progress, In Review, QA, and Done. Risks are managed through a risk register with named owners, mitigation plans, and regular review during weekly syncs, while stakeholder communication uses regular updates and a single source of truth for status.

Quality assurance and release readiness are built into delivery rather than deferred to the end. Pull requests should link to the relevant issue and acceptance criteria, stay small when possible, and pass CI testing, linting, and security scanning before review and merge approval. Teams use unit, integration, end-to-end smoke, and manual QA practices as appropriate. Before release, acceptance criteria must be complete, release notes and rollback plans prepared, and smoke tests ready for staging and production verification. After each sprint, release, milestone, or incident, the team captures learnings in a retrospective and tracks a small set of owned improvement actions.

## Recommended Reading Path

1. Start with the [Project Management Overview](docs/octoacme-project-management-overview.md).
2. Read the lifecycle guides in order: [Initiation](docs/octoacme-project-initiation.md), [Planning](docs/octoacme-project-planning.md), [Execution & Tracking](docs/octoacme-execution-and-tracking.md), [Release & Deployment](docs/octoacme-release-and-deployment.md), and [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md).
3. Use [Risk Management & Communication](docs/octoacme-risks-and-communication.md) and [Roles & Personas](docs/octoacme-roles-and-personas.md) alongside the lifecycle guides for role-specific and cross-cutting practices.

# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Executive Sponsors

### Role Summary
Executive Sponsors provide strategic sponsorship for an initiative. They ensure that the project remains aligned with business goals, has appropriate funding and support, and can receive timely decisions when delivery trade-offs need senior leadership involvement.

### Responsibilities
- Confirm the strategic outcome, investment rationale, and success measures
- Secure funding, staffing support, and organizational alignment
- Decide on material scope, timeline, budget, and priority trade-offs that exceed the delivery team's authority
- Remove escalated organizational blockers and advocate for the initiative with leadership
- Review major risks, milestones, and outcomes without directing day-to-day delivery work

### Interaction with existing roles
Executive Sponsors work with Product Managers to validate that the product direction supports business strategy. They rely on Project Managers for concise status, risk, dependency, and escalation reporting, and they support Developers by removing organizational constraints rather than assigning implementation work directly.

### Typical Communication
- Sponsor check-ins at key milestones and decision points
- Escalation summaries and decision logs from the Project Manager
- Outcome and investment reviews with the Product Manager

---

## Engineering Leads / Tech Leads

### Role Summary
Engineering Leads own technical direction for the delivery team. They translate product intent into a feasible technical approach, guide architectural decisions, and ensure that technical risks, quality, and delivery constraints are visible early.

### Responsibilities
- Define or validate architecture, technical standards, and implementation approach
- Lead technical estimation, sequencing, and dependency identification
- Surface and mitigate technical risks, including maintainability and operational concerns
- Mentor Developers and facilitate design and code reviews
- Partner on technical acceptance criteria, readiness decisions, and incident learning

### Interaction with existing roles
Engineering Leads guide Developers on design and implementation while incorporating their estimates and feedback. They work with Product Managers to evaluate feasibility and trade-offs, and with Project Managers to plan dependencies, communicate technical risks, and keep delivery milestones realistic.

### Typical Communication
- Technical design documents and architecture reviews
- Estimation, planning, and risk-management sessions
- Engineering updates in standups, demos, and release-readiness reviews

---

## UX / Product Designers

### Role Summary
UX / Product Designers represent user needs through research, workflows, prototypes, and design validation. They make the intended experience understandable and usable before and during implementation.

### Responsibilities
- Conduct or synthesize user research and translate findings into user journeys and workflows
- Produce and maintain interaction designs, prototypes, and design specifications
- Validate designs with users or stakeholders and incorporate feedback
- Define usability considerations and collaborate on accessible, implementable experiences
- Support design quality checks through implementation and release

### Interaction with existing roles
Designers partner with Product Managers to turn desired outcomes into validated user experiences. They collaborate with Developers to make designs practical to build, and with Project Managers to plan research, review, and design handoffs alongside delivery milestones.

### Typical Communication
- User journeys, prototypes, and design specifications
- Design critiques and implementation handoffs
- Usability findings shared in planning and demo sessions

---

## QA / Test Leads

### Role Summary
QA / Test Leads define the project test approach and make quality risks visible. They coordinate validation so the team can make evidence-based readiness and release decisions.

### Responsibilities
- Define test strategy, coverage expectations, environments, and test data needs
- Review acceptance criteria for clarity, testability, and completeness
- Coordinate functional, regression, exploratory, and non-functional validation as appropriate
- Report defects, quality trends, and residual risks
- Advise on release readiness and verify that agreed quality checks are complete

### Interaction with existing roles
QA / Test Leads work with Developers to build testable software and investigate defects. They partner with Product Managers to clarify acceptance criteria and validate intended outcomes, and provide Project Managers with quality status and risks for planning, escalation, and release decisions.

### Typical Communication
- Test plans, test results, and defect reports
- Acceptance-criteria and release-readiness reviews
- Quality-risk updates in project status reporting

---

## Security / Privacy Partners

### Role Summary
Security / Privacy Partners advise the team on security, privacy, compliance, and incident requirements. They help address material risks early and verify that required controls are considered before release.

### Responsibilities
- Identify applicable security, privacy, and compliance requirements
- Facilitate threat, privacy, or risk reviews for material changes
- Recommend controls, secure design practices, and evidence needed for approval
- Review security findings and help prioritize remediation
- Contribute incident-response, notification, and post-incident improvement requirements

### Interaction with existing roles
Security / Privacy Partners collaborate with Developers on secure implementation and remediation, with Product Managers on data use and customer-impact trade-offs, and with Project Managers on risk tracking, required reviews, and release gates.

### Typical Communication
- Threat models, privacy assessments, and control recommendations
- Security-risk entries in the shared risk register
- Release approvals or exceptions documented with the Project Manager

---

## Operations / SRE / Release Managers

### Role Summary
Operations / SRE / Release Managers own operational readiness and coordinate safe deployment. They ensure that teams can observe, support, roll back, and learn from production changes.

### Responsibilities
- Define operational readiness expectations for monitoring, alerting, support, and rollback
- Coordinate deployment sequencing, change communications, and release checklists
- Validate post-release behavior and lead operational response during incidents
- Maintain or advise on service-level objectives, capacity, and reliability risks
- Feed operational lessons into planning and retrospectives

### Interaction with existing roles
Operations / SRE / Release Managers work with Developers and Engineering Leads to make services deployable and observable. They coordinate with Product Managers on release impact and timing, and with Project Managers on readiness milestones, dependencies, communications, and rollback decisions.

### Typical Communication
- Release plans, checklists, and change notices
- Monitoring dashboards and post-release verification updates
- Incident records and reliability improvement actions

---

## Customer Support / Service Owners

### Role Summary
Customer Support / Service Owners represent the customer experience after release. They prepare support channels for change, identify recurring customer impact, and close the feedback loop between operations and product delivery.

### Responsibilities
- Provide customer-impact insights, recurring issues, and service trends
- Prepare support guidance, known-issue content, and escalation paths for releases
- Coordinate customer communications for material changes or incidents
- Track post-release issues and confirm that support needs are addressed
- Contribute customer feedback to prioritization and retrospectives

### Interaction with existing roles
Customer Support / Service Owners partner with Product Managers to share customer needs and measure whether a release resolves them. They work with Project Managers to plan support readiness and communications, and give Developers actionable issue context, reproduction details, and customer-impact information.

### Typical Communication
- Support-readiness checklists and knowledge-base updates
- Customer-impact summaries and known-issue reports
- Feedback and escalation updates during releases and incidents

---

## Business Analysts / Subject-Matter Experts

### Role Summary
Business Analysts / Subject-Matter Experts clarify domain rules, workflows, and constraints. They help convert business needs into clear, testable work while ensuring that delivery decisions reflect the operating context.

### Responsibilities
- Elicit and document business rules, workflows, terminology, and exceptions
- Refine requirements, acceptance criteria, and process impacts with the delivery team
- Validate that proposed solutions meet domain and stakeholder needs
- Identify process, policy, data, and dependency risks
- Support demos, training, and retrospective learning with domain context

### Interaction with existing roles
Business Analysts / Subject-Matter Experts support Product Managers in defining the right problem and acceptance criteria. They help Developers understand domain behavior and edge cases, and work with Project Managers to surface dependencies, coordinate stakeholder validation, and keep decisions documented.

### Typical Communication
- Requirements notes, workflow maps, and business-rule documentation
- Backlog-refinement and acceptance-criteria sessions
- Domain validation during demos, testing, and retrospectives

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

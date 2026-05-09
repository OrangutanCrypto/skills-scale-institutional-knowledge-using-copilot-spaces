````markdown
# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process documentation. This folder contains the complete set of guides and best practices for managing projects at OctoAcme, from initiation through retrospective and continuous improvement.

## Quick Start

New to OctoAcme project management? Start here:
1. Read the [Project Management Overview](./octoacme-project-management-overview.md) for core principles, roles, and the project lifecycle
2. Explore the [Roles & Personas](./octoacme-roles-and-personas.md) guide to understand team members' responsibilities
3. Follow the phase-specific guides linked below as you progress through your project

## Project Management Process Overview

OctoAcme operates a structured, lifecycle-based project management approach designed for cross-functional delivery of product features, services, and integrations. The methodology is grounded in five core principles:

- **Customer-first**: Prioritize customer value through a customer-first lens
- **Iterative delivery**: Deliver small, testable increments through iterative releases
- **Clear ownership**: Establish clear ownership with named Project Managers and Product Leads
- **Data-informed decisions**: Make decisions based on measurable evidence and metrics
- **Psychological safety**: Foster psychological safety to encourage feedback and learning

The project lifecycle follows five distinct phases—**Initiation, Planning, Execution, Release, and Close & Retrospective**—each with specific deliverables and decision gates that ensure alignment before progressing to the next stage.

### Key Roles

OctoAcme defines four primary personas:

- **Project Managers**: Coordinate delivery, manage schedules, risks, and communications
- **Product Managers**: Own the product vision, prioritize the backlog, and measure outcomes
- **Developers**: Implement features while maintaining high quality and test coverage
- **QA/Testing**: Validate acceptance criteria and quality standards

### Living Artifacts

OctoAcme maintains a suite of living artifacts that remain accessible to the entire team:

- Project Charters or One-pagers (capturing problem, goal, and success metrics)
- Risk Registers (tracking identified threats with mitigation plans)
- Prioritized backlogs with acceptance criteria
- Definition of Done standards
- Retrospective notes and action items

These artifacts are stored in the project repository and `.copilot/` folder to ensure accessibility and continuity across team transitions.

### Execution & Quality Assurance

Daily execution is managed through a structured team rhythm:

- **Daily standups** (15 min): Focus on progress and blockers
- **Weekly delivery syncs**: Show progress and flagged risks
- **Sprint/milestone demos and reviews**: Validate delivery

Quality is embedded throughout the workflow via:

- Unit and integration tests
- End-to-end smoke tests before release
- Security scanning in CI pipelines
- Manual QA for feature acceptance when needed

Pull Requests follow strict conventions (≤400 lines when possible, issue links, acceptance criteria) with automated CI validation and at least one approval required before merging.

### Communication & Risk Management

Communication flows through multiple channels:

- **Weekly syncs** between PM and Product Manager
- **Twice-weekly standups** for delivery team
- **Monthly stakeholder updates**
- **Clear escalation hierarchy** (Team → PM → Product Lead → Sponsor) for managing blockers and risks

The approach prioritizes transparency through single sources of truth, blameless retrospectives after incidents, and consistent status reporting that tracks velocity, burndown, and key success metrics.

---

## Process Documentation by Phase

### 1. [Project Initiation](./octoacme-project-initiation.md)
Define the initial steps to validate and authorize work, align stakeholders, and create a lightweight plan.
- **Deliverables**: Project One-pager, stakeholder list, high-level timeline, initial risk list
- **Decision gate**: Move to planning when success metrics are clear and stakeholders align

### 2. [Project Planning](./octoacme-project-planning.md)
Turn an approved initiative into an actionable plan and backlog for delivery.
- **Activities**: Kickoff meeting, create prioritized backlog, estimate scope, define Definition of Done
- **Outputs**: Release plan, milestone map, risk register with dependencies

### 3. [Execution & Tracking](./octoacme-execution-and-tracking.md)
Manage day-to-day execution and track progress toward project milestones.
- **Team rhythm**: Daily standups, weekly delivery syncs, sprint demos
- **Quality gates**: PR workflows, CI/CD, automated testing, manual QA
- **Escalation**: Multi-level blocker escalation (Team → PM → Product Lead → Sponsor)

### 4. [Risk Management & Communication](./octoacme-risks-and-communication.md)
Identify, manage, and communicate risks and dependencies throughout the project.
- **Risk lifecycle**: Identify → Assess → Mitigate → Monitor
- **Stakeholder communication**: Regular updates, single source of truth, escalation paths
- **Templates**: Weekly status, incident communication

### 5. [Release & Deployment](./octoacme-release-and-deployment.md)
Standardize how OctoAcme releases features to production to reduce risk and improve observability.
- **Release types**: Patch, minor, major
- **Pre-release requirements**: Acceptance criteria met, CI/security scans passing, smoke tests prepared
- **Deployment checklist & rollback playbook**: Ensure safe, verifiable releases

### 6. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
Capture learnings and convert them into actionable improvements.
- **When**: After each sprint, release, or important milestone
- **Structure**: What went well, what could improve, action items with owners and due dates
- **Tracking**: Add action items to backlog and review in PM syncs

### 7. [Roles & Personas](./octoacme-roles-and-personas.md)
Detailed reference guide for team member responsibilities, goals, and communication patterns.
- **Personas**: Project Manager, Product Manager, Developer, QA/Testing
- **Usage**: Frame scenarios, create persona-specific guidance, set expectations

---

## How to Use These Docs

### For New Project Teams
1. Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand the approach
2. Use the phase-specific guides (Initiation → Planning → Execution → Release → Retrospective) as your checklist
3. Refer to [Roles & Personas](./octoacme-roles-and-personas.md) to clarify responsibilities
4. Keep all project artifacts (charters, risk registers, retrospectives) in your project repo or `.copilot/` folder

### For Copilot Spaces
Add process-specific docs to `.copilot/` to provide context to AI assistants. Use these documents to:
- Ground AI guidance in OctoAcme's processes
- Standardize language and terminology
- Enable consistent, repeatable project execution
- Provide role-specific context (e.g., "You are a Project Manager at OctoAcme")

### For Continuous Improvement
- File process improvements using the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template
- Review and update docs after major projects or incidents
- Maintain these docs as living artifacts; encourage team feedback

---

## Additional Resources

- [Issue Template: Add/Update Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) — Use this to propose updates to process documentation
- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction and principles

---

**Last Updated**: May 2026  
**Questions?** Open an issue or start a discussion in this repository.
````

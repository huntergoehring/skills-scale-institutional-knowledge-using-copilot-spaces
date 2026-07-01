# OctoAcme Project Management Process Documentation

## Overview

OctoAcme follows a structured, customer-first project management approach that emphasizes iterative delivery, clear ownership, and data-informed decisions. Our processes are designed to be lightweight yet comprehensive, ensuring projects deliver value efficiently while maintaining psychological safety and team alignment.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager and Product Lead roles
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

OctoAcme projects follow five main stages:

1. **Initiation** → Define problem, align stakeholders, create one-pager
2. **Planning** → Build backlog, estimate scope, plan dependencies
3. **Execution** → Deliver increments, track progress, manage risks
4. **Release** → Deploy to production, verify, announce
5. **Retrospective** → Capture learnings, improve processes

## How OctoAcme Works: A Process Overview

OctoAcme operates through a lifecycle-based approach with clearly defined roles and communication rhythms. The organization establishes accountability through dedicated personas—Project Managers who coordinate delivery and schedules, Product Managers who define outcomes and measure success, Developers who implement features and collaborate on quality, and QA/Testing specialists who validate acceptance criteria. This role clarity enables cross-functional collaboration while maintaining transparent project oversight.

Communication and rhythm are central to OctoAcme's execution model. Teams establish a predictable cadence including daily standups (15 minutes focused on progress and blockers), twice-weekly delivery syncs, weekly PM and Product Manager alignment meetings, and monthly stakeholder updates. Risks and blockers follow a tiered escalation path—starting with team-level triage, escalating through the PM to the Product Lead, and ultimately to the Sponsor for business-impacting issues. Status is tracked transparently through GitHub Projects and communicated via templated weekly updates.

Quality assurance is embedded throughout OctoAcme's execution and release processes. The organization mandates unit and integration testing, end-to-end smoke tests before release, CI-based automated testing and security scanning, and manual QA for feature acceptance. Pull requests follow lightweight discipline (≤400 lines when possible) with automated checks and at least one approval required before merging. Before any production deployment, teams verify acceptance criteria, passing CI/security scans, staged smoke testing, and documented rollback plans. After each sprint, release, or milestone, teams hold structured retrospectives to capture learnings and convert insights into prioritized action items tracked in the backlog.

## Process Documentation

| Document | Purpose | Use When |
|----------|---------|----------|
| [Project Management Overview](./octoacme-project-management-overview.md) | Introduction to OctoAcme approach, roles, and artifacts | You're new to OctoAcme or need a high-level understanding |
| [Project Initiation Guide](./octoacme-project-initiation.md) | Steps to validate and authorize new work | Starting a new project or feature proposal |
| [Project Planning](./octoacme-project-planning.md) | Breaking work into actionable increments | Planning sprints and milestones |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Managing day-to-day delivery and progress | Running daily standups and weekly syncs |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Identifying and managing risks and stakeholder updates | Escalating blockers or providing status updates |
| [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardizing releases to production | Preparing a release or managing deployments |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capturing learnings and process improvements | After sprints, releases, or incidents |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Definitions of key roles and responsibilities | Understanding team roles and accountabilities |

## Key Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## Quick Start

- **New to the project?** Start with [Project Management Overview](./octoacme-project-management-overview.md)
- **Kicking off a project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
- **Running a sprint?** Reference [Project Planning](./octoacme-project-planning.md) and [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Releasing features?** See [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **Reflecting on outcomes?** Review [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## Integration with Copilot Spaces

These process documents are designed to be used with GitHub Copilot Spaces. You can:

- Reference any process document in a Copilot Space to get context-specific guidance aligned with OctoAcme's approach
- Use the [Roles & Personas](./octoacme-roles-and-personas.md) definitions to prompt Copilot for role-specific advice
- Attach process docs to a Copilot Space to ground AI assistance in your organization's methodology

---

**Last updated**: 2026-07-01  
**Maintained by**: OctoAcme Project Management Community

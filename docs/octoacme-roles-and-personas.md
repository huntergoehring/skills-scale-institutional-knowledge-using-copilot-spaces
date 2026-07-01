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

## Technical Lead

### Role Summary
Technical Leads provide architectural guidance, mentor development teams, and serve as the escalation point for complex technical decisions. They ensure technical feasibility, code quality standards, and system design align with business objectives.

### Responsibilities
- Review and approve technical architecture and design decisions
- Mentor developers and conduct technical design reviews
- Identify technical risks and propose mitigation strategies
- Ensure adherence to coding standards and best practices
- Escalate and resolve complex technical blockers
- Collaborate with Product Manager on technical feasibility of features
- Guide performance optimization and refactoring efforts

### Goals
- Deliver scalable, maintainable, and secure solutions
- Reduce technical debt while enabling feature velocity
- Build team capability through mentorship and knowledge sharing
- Make principled technical trade-off decisions based on business context

### Typical Communication
- Design review meetings and architecture discussions
- Code review comments on complex or high-risk PRs
- Technical risk discussions in weekly PM syncs
- One-on-ones with developers for mentorship

### Interactions with Other Roles
- **Developers**: Provides technical guidance and code review feedback
- **Project Manager**: Advises on technical feasibility and risk mitigation
- **Product Manager**: Discusses technical implications of feature requests
- **QA Lead**: Collaborates on test strategy and quality standards

---

## Quality Assurance Lead

### Role Summary
QA Leads own the testing strategy, coordinate testing efforts across sprints, and ensure that all work meets acceptance criteria and quality standards before release.

### Responsibilities
- Define and evolve QA strategy (unit, integration, end-to-end, performance testing)
- Create and maintain test plans aligned with acceptance criteria
- Coordinate testing activities across team members
- Identify quality risks and propose testing approaches
- Validate acceptance criteria have been met before marking work complete
- Escalate quality issues that block release
- Collaborate on test automation and CI/CD improvements

### Goals
- Deliver high-quality features with minimal post-release defects
- Enable fast feedback cycles through effective automated testing
- Reduce manual testing burden through strategic test automation
- Ensure user-facing quality meets OctoAcme standards

### Typical Communication
- Sprint planning and backlog refinement meetings
- QA status updates in daily standups
- Test plan reviews and defect discussions
- Acceptance criteria walkthroughs with Product Manager

### Interactions with Other Roles
- **Developers**: Defines acceptance criteria and validates implementation quality
- **Product Manager**: Clarifies acceptance criteria and priority of quality issues
- **Project Manager**: Reports QA blockers and tracks quality metrics
- **Technical Lead**: Aligns on test strategy and automation standards

---

## Release Manager

### Role Summary
Release Managers orchestrate the deployment process, ensure compliance with release standards, and coordinate communication around releases to minimize risk and impact.

### Responsibilities
- Plan and schedule release windows and deployment timelines
- Prepare and validate release documentation and release notes
- Execute deployment checklists and manage rollback procedures
- Coordinate communication with stakeholders and support teams
- Monitor post-deployment health and escalate issues
- Ensure compliance with change management and release policies
- Maintain release calendar and deployment records

### Goals
- Deliver releases to production safely and predictably
- Minimize unplanned downtime and post-deployment issues
- Ensure stakeholder alignment and transparent communication
- Reduce deployment cycle time while maintaining stability

### Typical Communication
- Pre-release coordination meetings with development and operations teams
- Release announcement communications to stakeholders
- Post-deployment health check calls
- Incident response and rollback coordination

### Interactions with Other Roles
- **Project Manager**: Coordinates release timeline and stakeholder communication
- **Developers**: Validates code is release-ready and understands deployment process
- **Operations/DevOps**: Coordinates infrastructure readiness and deployment execution
- **QA Lead**: Confirms all testing complete and release criteria met

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams. They gather requirements, clarify business context, and ensure proposed solutions address the underlying business need.

### Responsibilities
- Gather and document business requirements from stakeholders
- Clarify acceptance criteria to ensure technical understanding of business need
- Identify business impact and risks associated with proposed solutions
- Act as subject matter expert for business domain and processes
- Validate that delivered solutions meet business objectives
- Facilitate discussions between technical teams and business stakeholders
- Support product discovery and user research activities

### Goals
- Ensure projects deliver business value and solve the right problem
- Reduce rework due to misunderstood requirements
- Enable faster time-to-value through clear business context
- Build shared understanding across business and technical teams

### Typical Communication
- Requirements gathering sessions and stakeholder interviews
- Acceptance criteria workshops with Product Manager and developers
- Backlog refinement and prioritization discussions
- Business impact assessments and validation conversations

### Interactions with Other Roles
- **Product Manager**: Collaborates on requirements and prioritization
- **Developers**: Clarifies business context and acceptance criteria
- **Project Manager**: Provides business impact context for risk and dependency management
- **Stakeholders**: Gathers detailed business requirements and validates solutions

---

## Operations / DevOps

### Role Summary
Operations and DevOps professionals manage infrastructure, deployment pipelines, monitoring, and production support. They enable the team to deploy safely and operate systems reliably.

### Responsibilities
- Design and maintain deployment pipelines and CI/CD infrastructure
- Ensure infrastructure can support application requirements (scale, performance, security)
- Monitor system health, performance, and errors in production
- Manage infrastructure changes and capacity planning
- Support incident response and production troubleshooting
- Implement security scanning and compliance controls
- Collaborate on observability and alerting strategies

### Goals
- Enable safe, fast, and repeatable deployments
- Maintain high system reliability and performance
- Reduce time-to-resolution for production issues
- Automate operational tasks to reduce manual toil

### Typical Communication
- Deployment coordination and release planning
- Infrastructure and scaling discussions in project planning
- Incident response and post-incident retrospectives
- Monitoring and alerting reviews

### Interactions with Other Roles
- **Release Manager**: Coordinates deployment execution and infrastructure readiness
- **Developers**: Advises on deployment requirements and infrastructure constraints
- **Technical Lead**: Collaborates on system design and scalability considerations
- **Project Manager**: Reports on infrastructure readiness and production stability

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business direction, priority guidance, and final approval for major project decisions. They represent business, customer, or executive interests in the project.

### Responsibilities
- Provide business context and strategic alignment for projects
- Approve project charter and major scope changes
- Provide feedback on proposed solutions and trade-offs
- Escalate business-critical issues and manage executive expectations
- Validate that delivered solutions meet business objectives
- Provide resources and remove organizational blockers
- Communicate project value to broader organization

### Goals
- Ensure projects deliver strategic business value
- Make informed trade-off decisions between competing priorities
- Maintain executive alignment and confidence in project delivery
- Enable rapid resolution of escalated issues

### Typical Communication
- Monthly stakeholder updates and business reviews
- Milestone approval gates and decision meetings
- Ad-hoc escalations for business-critical issues
- Executive communications and announcement coordination

### Interactions with Other Roles
- **Project Manager**: Receives status updates and escalations, provides direction
- **Product Manager**: Collaborates on business objectives and success metrics
- **Developers**: Understands business context through sponsor-provided context
- **Business Analyst**: Provides high-level business requirements and validation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

# OctoAcme Project Management Docs

This README is the entry point for OctoAcme's project management guidance. It provides a brief overview of the project lifecycle and links to the detailed process documents in this folder.

## Project Management Process Overview

OctoAcme runs projects through a lightweight lifecycle that emphasizes clear ownership, iterative delivery, measurable outcomes, and regular communication.

### Initiation
- Validate the business need and expected outcome.
- Align sponsors and other stakeholders on the problem, priority, and timeline.
- Define success criteria and initial milestones.
- Identify early risks, dependencies, and resource needs.
- Decide whether the work is ready to move into planning.

### Planning
- Turn approved work into a prioritized backlog of shippable increments.
- Add acceptance criteria, estimates, owners, and related documentation to backlog items.
- Confirm milestones, release timing, dependencies, and responsibilities.
- Document the Definition of Done and an initial QA approach before execution begins.

### Execution and Tracking
- Manage delivery on the project board using the documented workflow states.
- Use pull requests to connect work to issues and acceptance criteria.
- Run the expected quality gates, including testing, linting, and security scanning in CI before review and merge.
- Track delivery metrics, success metrics, and operational signals.
- Escalate blockers through the documented team, product, and sponsor levels when needed.

### Risk Management and Communication
- Maintain the risk register throughout planning and execution.
- Review risks, mitigations, and dependencies during regular syncs.
- Share consistent status updates using the documented templates and a single source of truth.
- Follow the documented escalation paths, including the security incident path when applicable.

### Release and Deployment
- Confirm acceptance criteria are met and CI and security checks have passed.
- Prepare release notes, smoke tests, and rollback or mitigation plans.
- Deploy safely, preferably through automated pipelines after staging validation.
- Verify production behavior after deployment and communicate the release to stakeholders and support teams.

### Retrospectives and Continuous Improvement
- Capture learnings after sprints, releases, milestones, and incidents.
- Review what went well, what should improve, and any previous action items.
- Track a small set of prioritized, actionable improvements with owners and follow-up dates.

### Roles and Personas
- Developers build, test, document, and help estimate work while surfacing technical risks.
- Product Managers define outcomes, success metrics, priorities, and acceptance criteria.
- Project Managers coordinate plans, timelines, risks, dependencies, and stakeholder communication.
- These roles stay aligned through standups, planning sessions, status updates, roadmap communication, project boards, and review workflows.

## Links
- [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [OctoAcme Project Initiation Guide](octoacme-project-initiation.md)
- [OctoAcme Project Planning](octoacme-project-planning.md)
- [OctoAcme Execution & Tracking](octoacme-execution-and-tracking.md)
- [OctoAcme Risk Management & Communication](octoacme-risks-and-communication.md)
- [OctoAcme Release & Deployment Guide](octoacme-release-and-deployment.md)
- [OctoAcme Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Personas](octoacme-roles-and-personas.md)

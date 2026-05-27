# OctoAcme Project Management Docs

Welcome! This README provides a summary of how OctoAcme manages projects and includes links to all process documentation in this folder.

## Project Management Process Summary

OctoAcme operates with a **customer-first, iterative delivery model** centered on five core principles:

- **Customer-first:** Prioritize customer value and usability in all decisions
- **Iterative delivery:** Work is broken into small, testable increments
- **Clear ownership:** Each project has a named Project Manager and Product Lead
- **Data-informed:** Decisions and prioritization are based on evidence and outcomes
- **Psychological safety:** Encourage feedback, learning, and continuous improvement

### Organizational Structure

OctoAcme's project teams consist of clearly defined roles:

- **Project Manager:** Coordinates delivery, manages schedules, risks, and communications
- **Product Manager:** Defines outcomes, prioritizes the backlog, and measures success
- **Developers:** Implement features, collaborate on design, and maintain quality standards
- **QA/Testing:** Validate quality and acceptance criteria
- **Stakeholders:** Provide inputs, approvals, and business context

### Project Lifecycle Phases

OctoAcme projects follow a five-phase lifecycle:

1. **Initiation:** Define the problem statement, objectives, success metrics, stakeholders, and initial timeline. Create a lightweight Project One-pager to confirm business need and authorize work.

2. **Planning:** Break work into shippable increments, prioritize the backlog with clear acceptance criteria, define Definition of Done, identify dependencies and risks, and establish release milestones.

3. **Execution & Tracking:** Build, review, and test features using daily standups and sprint workflows. Track progress through project boards, manage risks via weekly syncs, and ensure quality through automated testing and code review.

4. **Release:** Deploy to production with quality checks, pre-release verification, security scanning, smoke testing, and post-deployment verification. Maintain detailed release notes and rollback plans.

5. **Continuous Improvement:** Conduct retrospectives after each sprint, release, or milestone to capture learnings. Convert insights into actionable improvements with clear owners and timelines.

### Communication Strategy

OctoAcme maintains a structured communication cadence:

- **Weekly syncs** between Project Manager and Product Manager
- **Twice-weekly standups** for delivery teams
- **Monthly stakeholder updates** with status and decisions
- **Ad-hoc escalations** for blockers and critical issues

Communication follows clear escalation paths (Team → PM → Product Lead → Sponsor) and uses standardized templates for status reporting and incident communication.

### Quality Assurance & Risk Management

Quality is embedded throughout the project lifecycle:

- **Testing:** Unit tests, integration tests, end-to-end smoke tests, and security scanning
- **Code review:** Small PRs (≤400 lines) with at least one approval required before merging
- **Risk management:** Maintain a Risk Register tracking ID, description, impact, likelihood, owner, mitigation plan, and status
- **Metrics:** Track velocity, burndown, and success indicators from the Project One-pager

## Process Documentation Links

Detailed guidance for each phase and aspect of OctoAcme's project management:

### Core Process Guides
- **[Project Management Overview](octoacme-project-management-overview.md)** – High-level introduction to OctoAcme's approach, principles, roles, and artifacts
- **[Roles and Personas](octoacme-roles-and-personas.md)** – Detailed responsibilities and communication patterns for Developers, Product Managers, and Project Managers

### Lifecycle Phases
- **[Project Initiation Guide](octoacme-project-initiation.md)** – Steps to validate business need, align stakeholders, and create initial project authorization
- **[Project Planning](octoacme-project-planning.md)** – Techniques for breaking work into shippable increments, estimating scope, and managing dependencies
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** – Day-to-day workflows, team rhythm, quality practices, and progress reporting
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** – Pre-release requirements, deployment checklists, rollback procedures, and release notes

### Cross-Cutting Concerns
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** – Risk lifecycle, stakeholder communication strategies, escalation paths, and incident handling
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** – Running effective retrospectives, tracking action items, and building a culture of continuous learning

## Quick Start for New Team Members

1. **Read** the [Project Management Overview](octoacme-project-management-overview.md) for a 5-minute introduction
2. **Review** the [Roles and Personas](octoacme-roles-and-personas.md) document to understand your role and others' responsibilities
3. **Explore** the relevant lifecycle phase guide based on your current project stage
4. **Reference** Risk Management & Communication and Retrospective guides for ongoing project health

## How to Use These Docs

- **Keep Process Documentation Updated:** Project teams should maintain accuracy of process docs as the methodology evolves
- **Copilot Spaces Integration:** Add process-specific docs to `.copilot/` folder if you want Copilot Spaces to use them as context for AI assistance
- **Project Charters:** Store individual project charters and one-pagers in your project repository with a link back to these core process docs
- **Continuous Learning:** Use retrospectives to identify process improvements and update relevant documentation

## Key Artifacts

Every OctoAcme project maintains these key artifacts:

- Project Charter / One-pager (Problem, Goal, Success Metrics)
- Roadmap and Release Plan
- Sprint/Iteration Backlog with Acceptance Criteria
- Definition of Done
- Risk Register
- Retrospective notes and action items
- Release notes and deployment verification

---

*For questions or process updates, please engage with your Project Manager or Product Lead.*

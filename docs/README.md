# OctoAcme Project Management Docs

Welcome to OctoAcme's project management processes. This README provides a brief overview of how OctoAcme runs projects and links to detailed documentation for each phase and area.

## Overview of OctoAcme's Project Management Approach

OctoAcme operates a structured, lifecycle-based approach to project management that prioritizes customer value, iterative delivery, and clear ownership. The organization follows a five-phase workflow spanning from **Initiation** through **Retrospective & Continuous Improvement**. 

During initiation, teams validate business need through project one-pagers that capture problem statements, measurable success metrics, and stakeholder alignment. Planning breaks approved initiatives into prioritized backlogs with defined acceptance criteria, estimation, and release milestones. Execution emphasizes daily standups, small pull requests (≤400 lines), automated testing in CI pipelines, and manual QA for feature acceptance. The process ensures quality through unit tests, integration tests, end-to-end smoke tests, and security scanning before any release moves to production. Release and deployment follow standardized checklists with pre-release requirements, staged rollout to production, post-deploy verification, and documented rollback plans to minimize production risk.

OctoAcme's organizational structure centers on three primary personas working in close collaboration: **Product Managers** define what should be built by owning the product vision, prioritizing backlogs, and measuring business outcomes; **Project Managers** coordinate delivery activities, manage schedules and risks, and maintain stakeholder alignment; and **Developers** implement features, maintain tests and documentation, and help identify technical risks. Supporting roles include QA/Testing professionals who validate quality against acceptance criteria, and Stakeholders who provide inputs and approvals. The core principle of "clear ownership" means each project has named PM and Product Lead accountable for results. Communication is disciplined and regular: weekly syncs between PM and Product Manager, twice-weekly team standups, monthly stakeholder updates, and ad-hoc escalations using a structured path (team-level → PM → Product Lead → Sponsor).

Risk management and communication are baked into OctoAcme's DNA through a Risk Register that tracks ID, description, impact, likelihood, mitigation plans, and status. Risks are identified during planning and continuously monitored at weekly syncs. The organization maintains a single source of truth for project status using project boards (GitHub Projects), documentation in repository `.copilot/` or `docs/` directories, and release notes. Stakeholder groups receive templated weekly status updates covering progress, next steps, blockers, and decisions needed. Incident communication follows a blameless approach with post-incident retrospectives and triage summaries. Finally, OctoAcme institutionalizes learning through mandatory retrospectives held after each sprint, release, or significant milestone, distilling findings into 2–3 prioritized action items with clear owners and due dates.

## Process Documentation

### Core Guidance

- **[OctoAcme Project Management Overview](octoacme-project-management-overview.md)** — Concise introduction to OctoAcme's approach, core roles, key artifacts, lifecycle phases, and communication cadence.
- **[OctoAcme Roles & Personas](octoacme-roles-and-personas.md)** — Detailed definitions of Developers, Product Managers, Project Managers, and their responsibilities and communication patterns.

### Project Lifecycle

- **[OctoAcme Project Initiation](octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight initial plan. Includes the Project One-pager template and initiation checklist.
- **[OctoAcme Project Planning](octoacme-project-planning.md)** — How to turn an approved initiative into an actionable plan and backlog. Covers prioritization, estimation, Definition of Done, and risk identification.
- **[OctoAcme Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day management guidance: team rhythm, project board workflows, PR standards, testing strategy, and metrics tracking.
- **[OctoAcme Release & Deployment](octoacme-release-and-deployment.md)** — Standardized process for releases and deployments, including checklists, rollback procedures, and release notes.

### Supporting Processes

- **[OctoAcme Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, assess, monitor, and mitigate risks. Includes stakeholder communication templates and escalation paths.
- **[OctoAcme Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Structure for running retrospectives after sprints, releases, and incidents. Tracks action items and measures improvement impact.

## How to Use These Docs

1. **Starting a new project?** Begin with [Project Initiation](octoacme-project-initiation.md).
2. **Familiar with OctoAcme processes?** Use these docs as a reference during planning, execution, and release phases.
3. **New to the team?** Read the [Overview](octoacme-project-management-overview.md) and [Roles & Personas](octoacme-roles-and-personas.md) for context.
4. **Adding to Copilot Spaces?** Reference files from `.copilot/` or `docs/` in your project README to ground Copilot in process context.

## Proposing Changes

If you'd like to suggest updates or add new process documentation, please:

1. Open an issue using the [Process Doc Update](../.github/ISSUE_TEMPLATE/process-doc-update.md) template.
2. Describe what content should be added or changed and why.
3. Include stakeholder input if the change affects multiple teams.
4. Submit a pull request with your proposed changes for review.

## Maintainers

These process docs are maintained by OctoAcme's Project Management and Product Leadership team. For questions or feedback, please reach out to the team or open an issue.

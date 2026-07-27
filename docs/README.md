# OctoAcme Project Management Process Docs

Welcome to the OctoAcme Project Management framework—a comprehensive set of documented processes and best practices for running cross-functional projects with iterative delivery, clear ownership, and data-informed decisions.

## Overview of OctoAcme Project Management

OctoAcme operates through a structured five-phase project lifecycle: **Initiation, Planning, Execution, Release, and Close & Retrospective**. The framework begins with a validation phase where teams confirm business need, identify stakeholders, and create a lightweight Project One-pager with success metrics. Once approved, projects move into detailed planning where work is broken into shippable increments with clear acceptance criteria, dependencies are mapped, and a Definition of Done is established. This iterative approach emphasizes delivering small, testable increments rather than large monolithic releases, allowing teams to gather feedback and adapt quickly.

### Core Principles

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has a named Project Manager (PM) and Product Manager (PdM)
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

### Key Workflows and Practices

Throughout execution, teams maintain a project board (GitHub Projects) with columns for Backlog, Ready, In Progress, In Review, QA, and Done, enabling transparent visibility of work status. Quality is embedded throughout with unit tests, integration tests, end-to-end smoke tests, and security scanning in CI pipelines. Pull requests are kept small (≤400 lines when possible) and require at least one approval before merging. OctoAcme maintains a Risk Register reviewed weekly during syncs, with escalation paths supporting early identification of blockers. Communication follows a structured cadence: daily standups (15 minutes), weekly PM/PdM syncs, twice-weekly team standups, monthly stakeholder updates, and end-of-sprint demos. Continuous improvement happens through retrospectives after each sprint or milestone, where learnings are converted into actionable improvements.

---

## Quick Navigation

### Project Phases

**Starting a project?**
- [Project Initiation Guide](octoacme-project-initiation.md) — Validate business need and align stakeholders
- [Project Management Overview](octoacme-project-management-overview.md) — Understand roles, principles, and the project lifecycle

**Planning delivery?**
- [Project Planning](octoacme-project-planning.md) — Break work into shippable increments and define dependencies

**Executing work?**
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Manage day-to-day delivery and track progress
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies

**Preparing to release?**
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardize production releases and rollback procedures

**Closing out?**
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and iterate on processes

---

## Complete Documentation

| Document | Purpose |
|----------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to OctoAcme approach, roles, principles, and key artifacts |
| [Project Initiation Guide](octoacme-project-initiation.md) | Validate business need, align stakeholders, create a Project One-pager, and make go/no-go decisions |
| [Project Planning](octoacme-project-planning.md) | Break work into shippable increments, estimate scope, identify dependencies, and define Definition of Done |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Manage day-to-day execution, track progress, run quality assurance, and escalate blockers |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Maintain risk registers, manage dependencies, and communicate with stakeholders |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardize release types, pre-release requirements, deployment procedures, and rollback playbooks |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Run retrospectives, track action items, and measure improvement impact |
| [Roles & Personas](octoacme-roles-and-personas.md) | Define responsibilities and communication patterns for Developers, Product Managers, and Project Managers |

---

## For Different Roles

### For Developers
- Start with [Roles & Personas](octoacme-roles-and-personas.md) to understand your responsibilities
- Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for quality standards and workflow
- Review [Project Planning](octoacme-project-planning.md) for acceptance criteria and Definition of Done

### For Product Managers
- Begin with [Project Management Overview](octoacme-project-management-overview.md) for context
- Use [Project Initiation Guide](octoacme-project-initiation.md) to validate and scope work
- Reference [Project Planning](octoacme-project-planning.md) for prioritization and roadmapping

### For Project Managers
- Start with [Project Management Overview](octoacme-project-management-overview.md)
- Use all phases sequentially: [Initiation](octoacme-project-initiation.md) → [Planning](octoacme-project-planning.md) → [Execution & Tracking](octoacme-execution-and-tracking.md) → [Release](octoacme-release-and-deployment.md) → [Retrospective](octoacme-retrospective-and-continuous-improvement.md)
- Reference [Risk Management & Communication](octoacme-risks-and-communication.md) throughout

---

## How to Use These Docs

1. **Start with your current project phase** — each document aligns to a phase in the project lifecycle
2. **Reference role-specific guidance** — use the "For Different Roles" section above to find relevant documentation
3. **Adapt checklists and templates** — each document includes practical checklists and templates for your project
4. **Keep the Project One-pager updated** in your project repository
5. **Contribute improvements** — found a gap or improvement? [Create an issue](https://github.com/VC99-ACN/skills-scale-institutional-knowledge-using-copilot-spaces/issues/new?template=add-update-content-to-process-docs.yml) using the "Add Content to Project Management Process Docs" template

---

## Key Artifacts You'll Create

- **Project One-pager** — Problem statement, goals, success metrics, stakeholders, timeline, risks, and team roles
- **Backlog with Acceptance Criteria** — Prioritized items with clear acceptance criteria and estimates
- **Definition of Done** — Team-agreed quality standards for work completion
- **Risk Register** — Tracked risks with impact, likelihood, owner, and mitigation plans
- **Release Notes** — Summary, changes, migration steps, and known issues
- **Retrospective Notes** — Learnings, action items, and follow-ups

---

## Support and Questions

For questions about these processes or to suggest improvements, please:
- Review the relevant process document for your situation
- Reach out to your Project Manager or Product Lead
- [Create an issue](https://github.com/VC99-ACN/skills-scale-institutional-knowledge-using-copilot-spaces/issues/new?template=add-update-content-to-process-docs.yml) to propose updates or additions to this documentation

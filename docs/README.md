# OctoAcme Project Management Docs

This README is your starting point for all OctoAcme project management process documentation. It provides an at-a-glance summary of how we run projects—from idea to delivery to continuous improvement—and direct links to each detailed guide.

## Overview

OctoAcme's project management approach follows a lightweight, end-to-end lifecycle designed for consistent execution across cross-functional work. Projects move through **Initiation → Planning → Execution → Release → Close/Retrospective**, with an emphasis on customer value, iterative delivery in small increments, clear ownership, and data-informed decisions. Key artifacts anchor this lifecycle—such as a **Project One-pager/Charter**, prioritized backlog with acceptance criteria, a **risk register**, and retrospective action items—so the team has a shared source of truth and can measure progress and outcomes over time.

Roles are explicitly defined to reduce ambiguity and improve delivery flow. A **Project Manager (PM)** coordinates schedules, delivery rhythm, risks, and stakeholder communications; a **Product Manager (PdM)** owns outcomes, backlog prioritization, and success metrics; **Developers** implement and test solutions while collaborating on estimates and technical risk mitigation; and **QA/Testing** validates acceptance criteria and overall quality. Stakeholders provide input and approvals at key points (e.g., initiation decision gates, milestone reviews, and releases), while the PM and Product Lead ensure alignment and unblock cross-team dependencies.

Execution is managed through consistent workflows and a clear operating cadence. Work is tracked on a project board (e.g., GitHub Projects) with stages such as **Backlog, Ready, In Progress, In Review, QA, Done**, complemented by structured team rhythms: **daily standups** for blockers and dependencies, **weekly delivery syncs** for progress and risk review, and sprint/milestone demos. Communication is standardized with weekly status updates (progress, next steps, risks/blockers, and asks/decisions), and escalation follows a defined path from **team triage → PM/Product Lead → sponsor** for business-impacting issues.

Quality assurance is embedded throughout delivery and release. OctoAcme favors **small pull requests**, requires issue links and acceptance criteria in PR descriptions, and expects **CI validation (tests, linting, and security scanning)** before review, with at least one approval required before merge (per team policy). Testing expectations include **unit tests for new logic**, **integration tests where applicable**, and **end-to-end smoke tests for critical flows** prior to release, plus manual QA when needed for feature acceptance. Releases also require readiness steps such as release notes, rollback/mitigation planning, staging validation, and post-deploy verification, followed by retrospectives that convert learnings into tracked, owned action items.

## Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution and Tracking](octoacme-execution-and-tracking.md)
- [Risks and Communication](octoacme-risks-and-communication.md)
- [Release and Deployment](octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

---

To propose updates or additions to these process docs, use the [process doc update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).

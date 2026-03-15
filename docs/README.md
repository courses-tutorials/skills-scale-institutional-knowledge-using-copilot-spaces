# OctoAcme Project Management Docs

Welcome to the OctoAcme project management process documentation! This README centralizes the key workflows, artifacts, and links to guide new and existing team members.

## Overview of Project Management Processes

OctoAcme operates on a **structured, customer-first project lifecycle** defined by five core phases: **Initiation, Planning, Execution, Release, and Close & Retrospective**. During **Initiation**, teams validate business needs and create a lightweight Project One-pager that confirms success metrics, stakeholders, and rough timelines before moving forward. The **Planning** phase breaks work into shippable increments with prioritized backlogs, acceptance criteria, and identified dependencies. **Execution** follows a structured team rhythm of daily standups, weekly delivery syncs, and sprint-based iteration using GitHub Projects with columns for Backlog, Ready, In Progress, In Review, QA, and Done. Teams deliver small pull requests (≤400 lines), run automated tests and security scanning, and require at least one approval before merging—maintaining quality through unit tests, integration tests, and end-to-end smoke tests for critical flows.

OctoAcme defines **clear roles and responsibilities** to ensure accountability and alignment. The **Project Manager** coordinates delivery, manages schedules, risks, and communications; the **Product Manager** defines what should be built and prioritizes the backlog; **Developers** implement features and maintain tests; and **QA/Testing** validates quality and acceptance criteria. This clarity of ownership is reinforced through a structured **communication cadence**: weekly syncs between PM and Product Manager, twice-weekly team standups, monthly stakeholder updates, and ad-hoc escalations as needed. Risk and dependency management is embedded into the process via a **Risk Register** (ID, Description, Impact, Likelihood, Owner, Mitigation, Status) that is reviewed at weekly syncs and escalated through three levels: team-level triage, PM escalation to Product Lead, and sponsor-level escalation for business-impacting issues.

**Release and quality assurance** are treated as critical gates in the OctoAcme workflow. Before any release, teams must meet pre-release requirements including passing CI and security scans, drafted release notes, and a documented rollback plan. Deployments follow a structured checklist that includes staging verification, post-deploy monitoring, and stakeholder announcement. Finally, OctoAcme closes the loop through **retrospectives** held after each sprint, release, or milestone, where teams capture learnings in a structured format (what went well, what could improve, action items with owners and due dates) and track improvements in the backlog. This continuous improvement culture, combined with data-informed decision-making and psychological safety, enables OctoAcme teams to deliver reliable increments consistently while building institutional knowledge through documented processes and shared artifacts.

## Quick Links to Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — Core principles, roles, and high-level lifecycle
- [Project Initiation Guide](octoacme-project-initiation.md) — How to validate ideas and authorize new projects
- [Project Planning](octoacme-project-planning.md) — Breaking work into increments and creating actionable backlogs
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day workflows, team rhythm, and quality practices
- [Risks & Communication](octoacme-risks-and-communication.md) — Risk registers, stakeholder updates, and escalation paths
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklists, and rollback procedures
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and prioritizing action items
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed role descriptions and responsibilities

## How to Use This Documentation

- **New team members:** Start with the [Project Management Overview](octoacme-project-management-overview.md) for a high-level introduction, then dive into specific process docs as needed.
- **Project managers:** Refer to [Project Initiation](octoacme-project-initiation.md), [Project Planning](octoacme-project-planning.md), and [Risks & Communication](octoacme-risks-and-communication.md) for checklists and templates.
- **Product managers:** See [Project Planning](octoacme-project-planning.md) and [Roles & Personas](octoacme-roles-and-personas.md) for your responsibilities and collaboration points.
- **Developers:** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for PR workflows, testing standards, and quality expectations.
- **Stakeholders:** Review [Risks & Communication](octoacme-risks-and-communication.md) and [Release & Deployment Guide](octoacme-release-and-deployment.md) for status updates and release information.

## Keeping Docs Current

These documents are living artifacts. When you discover gaps, improvements, or better ways to work:

1. **For updates to existing docs:** Open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. **For new processes:** Create an issue with the same template and select the "<new document>" option
3. **For Copilot Spaces:** Add process-specific docs to `.copilot/` to ground Copilot's knowledge in your team's context

---

**Last Updated:** 2026-03-15  
**Maintained by:** OctoAcme Project Management Community

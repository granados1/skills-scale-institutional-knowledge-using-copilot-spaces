# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. This folder contains the process guides, templates, and role definitions used across all cross-functional projects at OctoAcme. Use these docs as a reference for how we initiate, plan, execute, release, and continuously improve our work.

## Overview

OctoAcme's project management approach is organized around a clear project lifecycle: **initiation**, **planning**, **execution**, **release**, and **retrospective**. The process emphasizes lightweight but explicit up-front alignment, iterative delivery, clear ownership, and continuous improvement.

Projects begin with a one-pager that defines the problem, goal, success metrics, stakeholders, timeline, and proposed roles. Once approved, teams turn the initiative into a prioritized backlog with acceptance criteria, a Definition of Done, dependency mapping, and a milestone plan. Execution follows a steady rhythm of daily standups, weekly delivery syncs, and milestone demos, with work tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done). Quality is built in throughout — unit, integration, and smoke tests run in CI alongside security scanning, with manual QA where needed.

Risks and communication are managed continuously. A risk register captures impact, likelihood, owner, and mitigation for each identified risk, and is reviewed weekly. Stakeholders receive regular milestone-based updates with a consistent status template. Escalation paths run from team triage through PM, Product Lead, and Sponsor as needed. Releases go through pre-release checks (verified acceptance criteria, passing CI/security scans, release notes, rollback plan, staging smoke tests) before production deployment. After each sprint or release, a retrospective surfaces learnings and feeds action items back into the backlog to drive continuous improvement.

## Key Roles

| Role | Responsibilities |
|---|---|
| **Project Manager (PM)** | Coordinates delivery, schedules, risks, and communications |
| **Product Manager (PdM)** | Defines outcomes, prioritizes backlog, and measures success |
| **Developers** | Implement features, write tests, contribute to design and estimation |
| **UX Designer** | Designs user flows, wireframes, and prototypes; validates usability |
| **Business Analyst** | Elicits and documents requirements; bridges business and delivery teams |
| **QA Lead** | Owns test strategy, executes testing, and signs off on release readiness |
| **DevOps Engineer** | Maintains CI/CD pipelines, environments, and deployment reliability |
| **Stakeholder Sponsor** | Provides strategic alignment, resources, and go/no-go decisions |

> See [Roles & Personas](octoacme-roles-and-personas.md) for full role descriptions and cross-role collaboration details.

## Communication Cadence

- **Daily standup** — 15 min; progress, blockers, dependencies
- **Weekly delivery sync** — progress updates, flagged risks
- **Weekly PM + PdM alignment** — roadmap and priority decisions
- **Milestone demos / reviews** — end of each sprint or milestone
- **Monthly stakeholder updates** — status and upcoming milestones
- **Ad-hoc escalations** — as needed per escalation path

## Documents in This Folder

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and lifecycle summary |
| [Project Initiation](octoacme-project-initiation.md) | How to validate and authorize new work; one-pager template |
| [Project Planning](octoacme-project-planning.md) | Turning an approved initiative into a backlog and release plan |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day team rhythm, PR workflow, quality, and metrics |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and communication patterns per role |
| [Project Roles Checklist](octoacme-project-roles-checklist.md) | Per-phase checklist for engaging the right roles during initiation, planning, execution, release, and retrospective |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, stakeholder updates, and escalation paths |
| [Release & Deployment](octoacme-release-and-deployment.md) | Pre-release checks, deployment checklist, and rollback playbook |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, action item tracking, and improvement culture |

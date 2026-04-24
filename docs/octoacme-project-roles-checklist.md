# OctoAcme — Project Roles Checklist

Use this checklist to ensure that all roles and personas are engaged at the right time during each phase of a project. Cross-reference with [Roles & Personas](octoacme-roles-and-personas.md) for full role descriptions and collaboration details.

---

## Phase 1 — Initiation

**Goal:** Validate the idea, align stakeholders, and authorize the work.

### All Projects
- [ ] **Stakeholder Sponsor** — Reviewed the project proposal and provided go/no-go approval
- [ ] **Product Manager** — Authored the project one-pager; defined problem statement, success metrics, and initial scope
- [ ] **Project Manager** — Created the stakeholder list, communication plan, and initial risk list
- [ ] **Business Analyst** — Identified and documented high-level requirements and open questions from stakeholders

### If design-heavy or user-facing
- [ ] **UX Designer** — Attended the kick-off; aware of the problem space and user research needed

### Notes
> Tip: Not all roles need to be involved at full capacity during initiation. Ensure at minimum that the Stakeholder Sponsor, Product Manager, and Project Manager have aligned on the charter before moving to planning.

---

## Phase 2 — Planning

**Goal:** Convert the approved initiative into a backlog, milestones, and a release plan.

- [ ] **Product Manager** — Backlog created with prioritized user stories and acceptance criteria
- [ ] **Project Manager** — Milestone plan, dependency map, and resource allocation finalized
- [ ] **Business Analyst** — All requirements reviewed with stakeholders; use cases and acceptance criteria documented in the backlog
- [ ] **UX Designer** — Initial wireframes or prototypes available for Developer review; design feasibility confirmed
- [ ] **Developers** — Participated in estimation; flagged technical risks and dependencies
- [ ] **QA Lead** — Test plan drafted; Definition of Done agreed with Product Manager and Developers
- [ ] **DevOps Engineer** — CI/CD pipeline, environments, and deployment strategy confirmed for the release
- [ ] **Stakeholder Sponsor** — Reviewed the release plan and milestone schedule; provided input on priority trade-offs

---

## Phase 3 — Execution

**Goal:** Build, test, and iterate in a steady cadence toward milestone targets.

### Ongoing every sprint / iteration
- [ ] **Developers** — Delivering against sprint commitments; raising blockers in daily standup
- [ ] **Project Manager** — Facilitating standups and weekly delivery syncs; updating risk register; managing dependencies
- [ ] **Product Manager** — Available for questions on acceptance criteria; attending sprint demos and providing feedback
- [ ] **QA Lead** — Actively testing completed work; filing and triaging defects; maintaining the defect log
- [ ] **UX Designer** — Reviewing implemented features against design specs; providing timely feedback to Developers
- [ ] **DevOps Engineer** — Maintaining CI/CD pipeline health; monitoring staging environments; supporting Developer deployments

### As needed
- [ ] **Business Analyst** — Answering requirements questions; documenting approved scope changes; updating acceptance criteria
- [ ] **Stakeholder Sponsor** — Attending milestone demos; unblocking cross-departmental issues raised by the Project Manager

### Escalation triggers
- [ ] Any risk rated **High** or **Critical** escalated to **Stakeholder Sponsor** via the Project Manager
- [ ] Scope change requests reviewed by **Product Manager** and **Business Analyst** before approval

---

## Phase 4 — Release

**Goal:** Safely deploy to production, verify functionality, and communicate the release.

- [ ] **QA Lead** — Confirmed all acceptance criteria met; release readiness sign-off completed
- [ ] **DevOps Engineer** — Pre-release checks complete (CI green, security scans passed, rollback plan documented, staging smoke tests passed)
- [ ] **Developers** — Authored release notes and verified deployment steps in staging
- [ ] **Project Manager** — Coordinated release timing; communicated outage window (if any) to stakeholders
- [ ] **Product Manager** — Reviewed and approved release notes and feature announcements
- [ ] **Stakeholder Sponsor** — Provided final go/no-go for production deployment at milestone review
- [ ] **Business Analyst** — Verified that all originally scoped requirements are included or formally deferred

### Post-deployment verification
- [ ] **DevOps Engineer** — Production smoke tests passed; monitoring and alerting confirmed active
- [ ] **QA Lead** — Spot-checked production against critical test cases
- [ ] **Project Manager** — Sent post-release stakeholder update

---

## Phase 5 — Retrospective & Continuous Improvement

**Goal:** Capture learnings and feed improvements back into the process.

- [ ] **Project Manager** — Facilitated retrospective; documented action items with owners and due dates
- [ ] **Developers** — Contributed to retrospective (what went well, what to improve, blockers)
- [ ] **QA Lead** — Shared quality metrics (defect counts, test coverage, escape rates) and improvement proposals
- [ ] **DevOps Engineer** — Reported on deployment reliability, pipeline issues, and incident learnings
- [ ] **Product Manager** — Reviewed delivery against success metrics; surfaced product-side learnings
- [ ] **UX Designer** — Reported on usability findings or post-release user feedback
- [ ] **Business Analyst** — Noted requirements gaps or ambiguities discovered during delivery
- [ ] **Stakeholder Sponsor** — Received retrospective summary; approved any major process changes

---

## Role Engagement Summary

| Phase | Core Roles | Supporting Roles |
|---|---|---|
| **Initiation** | Stakeholder Sponsor, Product Manager, Project Manager | Business Analyst |
| **Planning** | Product Manager, Project Manager, Business Analyst | Developers, UX Designer, QA Lead, DevOps Engineer, Stakeholder Sponsor |
| **Execution** | Developers, Project Manager, QA Lead | Product Manager, UX Designer, DevOps Engineer, Business Analyst, Stakeholder Sponsor |
| **Release** | QA Lead, DevOps Engineer, Project Manager | Developers, Product Manager, Stakeholder Sponsor, Business Analyst |
| **Retrospective** | Project Manager, Developers | All roles |

---

> **See also:** [Roles & Personas](octoacme-roles-and-personas.md) · [Project Initiation](octoacme-project-initiation.md) · [Project Planning](octoacme-project-planning.md) · [Execution & Tracking](octoacme-execution-and-tracking.md) · [Release & Deployment](octoacme-release-and-deployment.md) · [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

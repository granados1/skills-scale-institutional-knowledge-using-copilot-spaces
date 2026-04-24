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

## UX Designer

### Role Summary
UX Designers are responsible for the usability, accessibility, and overall user experience of the product. They translate user needs and product requirements into workflows, wireframes, and prototypes that guide development.

### Responsibilities
- Conduct user research and synthesize findings into actionable design insights
- Create wireframes, prototypes, and high-fidelity mockups
- Define and document user flows and interaction patterns
- Participate in sprint planning and review sessions to validate design feasibility
- Iterate on designs based on developer feedback and usability testing results
- Maintain a shared design system or component library

### Goals
- Ensure the product is intuitive, accessible, and meets user expectations
- Reduce rework by aligning design with technical constraints early
- Advocate for the end user throughout the entire project lifecycle

### Typical Communication
- Design reviews and prototype walkthroughs with Product Manager and Developers
- Async design handoffs via design tools (e.g., Figma) with annotated specs
- Usability testing summaries shared with the broader team
- Participation in sprint demos to gather feedback

### Interactions with Existing Roles
- **Product Manager**: Collaborates on user research, translates product requirements into user flows, and validates designs against success metrics.
- **Developers**: Provides annotated design specs and is available to answer implementation questions; reviews built features against the intended design.
- **Project Manager**: Aligns on design milestones and flags risks when design iterations may impact timelines.
- **QA Lead**: Works together to define usability acceptance criteria and review final builds for design fidelity.

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and the delivery team. They gather, document, and clarify requirements, ensuring the team builds the right solution to address real business needs.

### Responsibilities
- Elicit and document detailed requirements from stakeholders
- Produce use cases, user stories, and acceptance criteria with measurable outcomes
- Facilitate requirements workshops and review sessions
- Maintain the requirements traceability matrix to ensure all needs are addressed
- Identify scope gaps, ambiguities, or conflicts and escalate them proactively
- Support backlog grooming by providing context on business priority and dependencies

### Goals
- Ensure the team has clear, unambiguous requirements before development begins
- Minimize rework caused by misunderstood or missing requirements
- Act as the authoritative source for business context during delivery

### Typical Communication
- Requirements review sessions with Product Manager and Developers
- Written use cases and user stories added to the project backlog
- Regular check-ins with the Stakeholder Sponsor to validate scope and priority
- Change request documentation when requirements evolve

### Interactions with Existing Roles
- **Product Manager**: Collaborates on roadmap prioritization and translates high-level goals into detailed requirements; supports backlog refinement.
- **Developers**: Provides context for user stories, answers requirements questions during development, and reviews implemented features against acceptance criteria.
- **Project Manager**: Surfaces scope-change risks early, supports effort estimation with requirements detail, and contributes to project documentation.
- **Stakeholder Sponsor**: Validates that documented requirements align with strategic business objectives and secures sign-off before development.

---

## Quality Assurance (QA) Lead

### Role Summary
The QA Lead owns the test strategy and quality standards for the project. They ensure that delivered features meet acceptance criteria, are free of critical defects, and are ready for production.

### Responsibilities
- Define and maintain the test plan, test cases, and Definition of Done for quality
- Lead manual and automated testing efforts across functional, regression, and integration testing
- Coordinate with Developers to integrate automated tests into the CI/CD pipeline
- Track, triage, and prioritize defects with clear reproduction steps and severity ratings
- Validate that acceptance criteria are met before sign-off on features
- Produce quality reports and release readiness assessments

### Goals
- Prevent defects from reaching production
- Build confidence in each release through systematic test coverage
- Continuously improve test efficiency through automation and process refinement

### Typical Communication
- Test plan reviews at the start of each sprint or milestone
- Bug reports and triage discussions with Developers
- Release readiness sign-off communicated to Project Manager and Product Manager
- Retrospective contributions on quality trends and improvements

### Interactions with Existing Roles
- **Developers**: Partners on test-driven development practices, automated test integration, and prompt defect resolution.
- **Product Manager**: Reviews acceptance criteria to ensure they are testable; confirms which scenarios require manual validation.
- **Project Manager**: Reports on test progress, outstanding defects, and release readiness; flags quality risks that may affect the milestone.
- **DevOps Engineer**: Coordinates on environment setup for automated testing, pipeline configuration, and staging deployments for QA cycles.
- **UX Designer**: Reviews final builds for design and usability fidelity as part of the acceptance process.

---

## DevOps Engineer

### Role Summary
DevOps Engineers design and maintain the infrastructure, CI/CD pipelines, and operational tooling that enable teams to deliver software reliably and securely. They ensure deployment processes are automated, repeatable, and auditable.

### Responsibilities
- Design, build, and maintain CI/CD pipelines for automated build, test, and deployment
- Manage cloud infrastructure, environments (development, staging, production), and configuration
- Implement and enforce security scanning, secrets management, and compliance controls
- Monitor production systems and define alerting and on-call runbooks
- Collaborate on release planning to assess deployment risk and define rollback procedures
- Drive infrastructure-as-code practices to ensure environments are reproducible

### Goals
- Enable frequent, low-risk deployments with confidence
- Reduce manual toil through automation and reliable tooling
- Maintain high availability, observability, and security posture in production

### Typical Communication
- Release readiness reviews with Project Manager and QA Lead
- Infrastructure change notifications and deployment runbooks shared with Developers
- Incident postmortem participation and action item tracking
- Async documentation of pipeline configurations and environment policies

### Interactions with Existing Roles
- **Developers**: Provides CI/CD tooling guidance, reviews infrastructure-affecting code changes, and partners on deployment automation.
- **Project Manager**: Advises on deployment risk and scheduling; communicates environment availability or outage windows that affect milestones.
- **QA Lead**: Provisions and maintains testing environments; integrates automated test suites into the pipeline.
- **Product Manager**: Provides visibility into release feasibility from an infrastructure perspective; surfaces risks related to scaling or performance.
- **Stakeholder Sponsor**: Keeps informed on major infrastructure changes, security posture, and incident impact summaries.

---

## Stakeholder Sponsor

### Role Summary
The Stakeholder Sponsor is the senior leader or executive who champions the project at the organizational level. They ensure the project aligns with strategic goals, secure necessary resources, remove high-level blockers, and provide final decision-making authority on major scope, budget, or timeline changes.

### Responsibilities
- Approve the project charter and authorize the initiative to proceed
- Align the project with organizational strategy and funding priorities
- Remove cross-departmental blockers that cannot be resolved at the team level
- Provide go/no-go decisions for major milestones and production releases
- Represent the project's progress and value to executive leadership
- Hold accountability for business outcomes delivered by the project

### Goals
- Ensure project investment delivers measurable business value
- Maintain organizational alignment and visibility into project health
- Enable the team by clearing strategic obstacles quickly

### Typical Communication
- Monthly executive status updates from the Project Manager
- Milestone review attendance for go/no-go decisions
- On-demand escalation calls for high-severity risks or scope changes
- Summary sign-off on major deliverables (project charter, release approvals)

### Interactions with Existing Roles
- **Project Manager**: Receives regular status updates, risk escalations, and seeks sponsor decisions on blockers; keeps sponsor informed of schedule or scope changes.
- **Product Manager**: Aligns on roadmap priorities and ensures the product direction matches business strategy; seeks sponsor input on major trade-off decisions.
- **Business Analyst**: Reviews and approves high-level requirements to confirm strategic fit before detailed scoping begins.
- **Developers / QA Lead / DevOps Engineer**: Indirect interaction; may attend milestone demos or release reviews to evaluate delivery quality and ask questions.

---

## Cross-Role Collaboration Summary

The table below highlights the primary collaboration touchpoints between all roles.

| | Developer | Product Manager | Project Manager | UX Designer | Business Analyst | QA Lead | DevOps Engineer | Stakeholder Sponsor |
|---|---|---|---|---|---|---|---|---|
| **Developer** | — | Feature specs, trade-offs | Planning, estimation | Design handoffs, feasibility | Requirements clarification | Test integration, defect fixes | CI/CD, deployments | Milestone demos |
| **Product Manager** | Feature scope, acceptance | — | Roadmap, priority | User research, designs | Requirements, backlog | Acceptance criteria | Release feasibility | Strategy alignment |
| **Project Manager** | Standups, risk tracking | Weekly alignment | — | Design milestones | Scope change management | Release readiness | Deployment scheduling | Status updates, escalations |
| **UX Designer** | Implementation feedback | Design reviews | Milestone alignment | — | Requirements → user flows | Usability acceptance | — | — |
| **Business Analyst** | Story context, sign-off | Backlog refinement | Scope documentation | User flows | — | Acceptance criteria | — | Requirements sign-off |
| **QA Lead** | Defect triage, automation | Acceptance validation | Quality reporting | Design fidelity | Acceptance criteria | — | Environment/pipeline setup | Release readiness |
| **DevOps Engineer** | Pipeline, infra guidance | Release feasibility | Deployment planning | — | — | Test environments | — | Incident & security updates |
| **Stakeholder Sponsor** | Milestone demos | Strategy, trade-offs | Status, escalations | — | Requirements approval | Release go/no-go | — | — |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Use the [Project Roles Checklist](octoacme-project-roles-checklist.md) to apply these personas during project initiation, planning, execution, and release phases.


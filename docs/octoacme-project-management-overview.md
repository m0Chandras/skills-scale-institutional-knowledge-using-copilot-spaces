# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- **Project Manager (PM)**: coordinates delivery, schedules, risk, communications.
- **Product Manager (PdM)**: defines outcomes, prioritizes backlog, and measures success.
- **Developers**: implement features, collaborate on design and testability.
- **Tech Lead / Architect**: defines technical direction and ensures architectural soundness.
- **QA Lead / Test Engineer**: validate quality, create test plans, and ensure acceptance criteria are met.
- **DevOps Engineer**: manages CI/CD, infrastructure, and deployment automation.
- **UX/UI Designer**: researches user needs, designs interfaces, and validates usability.
- **Security Champion**: advocates for security best practices and conducts security reviews.
- **Business Stakeholder**: provides strategic direction, funding, and approvals.

For detailed role descriptions, see [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md).

## Key Artifacts
- **Project Charter / One-pager** - defines problem, goals, and success metrics
- **Roadmap and Release Plan** - timeline and milestones
- **Sprint/Iteration Backlog** - prioritized work items
- **Acceptance Criteria & Definition of Done** - quality standards
- **Risk Register** - tracked risks and mitigations (see [Risk Management Checklist](./octoacme-risk-management-checklist.md))
- **QA & Testing Plans** - quality assurance approach (see [QA Checklist](./octoacme-qa-checklist.md))
- **Release Checklists** - deployment verification (see [Release Checklist](./octoacme-release-checklist.md))
- **Retrospective notes and action items** - continuous improvement

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.

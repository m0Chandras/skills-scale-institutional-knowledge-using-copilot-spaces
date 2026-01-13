# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

For comprehensive testing guidance, see the [QA & Testing Checklist](./octoacme-qa-checklist.md).

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
Follow the defined escalation hierarchy for blockers and risks:

**Level 1 - Team-level:** Triage in daily standup  
**Level 2 - PM-level:** PM escalates to Product Lead and dependent teams  
**Level 3 - Leadership-level:** Product/Tech Lead for significant issues  
**Level 4 - Executive-level:** Sponsor-level escalation for business-impacting issues

For detailed escalation procedures and special cases, see [Risk Management & Communication](./octoacme-risks-and-communication.md).

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly

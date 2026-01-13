# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

For a comprehensive risk management approach, use the [Risk Management Checklist](./octoacme-risk-management-checklist.md).

**Sample Risk Register Template:**

| ID | Description | Impact | Likelihood | Owner | Mitigation Plan | Status |
|----|-------------|--------|------------|-------|-----------------|--------|
| R-001 | Database migration may fail | High | Medium | DevOps Lead | Test on staging, prepare rollback | Active |
| R-002 | Key developer on vacation | Medium | High | PM | Cross-train team member | Mitigated |

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths

### Standard Escalation Flow
Follow this escalation hierarchy for issues, blockers, and risks:

**Level 1 - Team Level:**
- **When:** Day-to-day blockers, technical questions, minor risks
- **Who:** Raised in daily standup or team chat
- **Action:** Team collaborates on resolution
- **Timeframe:** Resolve within 1-2 days

**Level 2 - Project Manager:**
- **When:** Cross-team dependencies, resource needs, schedule risks
- **Who:** Project Manager coordinates with stakeholders
- **Action:** PM escalates to dependent teams or Product Lead
- **Timeframe:** Resolve within 3-5 days

**Level 3 - Leadership Level:**
- **When:** Significant scope/timeline changes, budget issues, high-impact risks
- **Who:** Product Lead, Tech Lead, or Department Head
- **Action:** Leadership makes decisions or reallocates resources
- **Timeframe:** Resolve within 1 week

**Level 4 - Executive/Sponsor Level:**
- **When:** Project at risk of failure, major business impact, strategic pivots
- **Who:** Business Stakeholder, Executive Sponsor, or C-level
- **Action:** Strategic decision, additional funding, or project re-evaluation
- **Timeframe:** Emergency decision within 24-48 hours

### Special Escalation Paths

**Security Incidents:**
- Immediately notify Security Champion
- Follow security incident runbook
- Notify Security on-call team
- Escalate to CISO for high/critical incidents
- Communicate with legal/compliance as needed

**Production Outages:**
- Trigger incident response protocol
- Notify DevOps Engineer and on-call team
- Engage Tech Lead for technical decisions
- Update status page and notify stakeholders
- Conduct post-incident review

**Compliance Issues:**
- Notify compliance officer immediately
- Engage legal team as appropriate
- Escalate to executive level if material
- Document all actions and decisions

### Escalation Guidelines
- **Escalate early:** Don't wait until issues become critical
- **Provide context:** Include impact, urgency, and recommended actions
- **Document:** Record escalation in project log or risk register
- **Follow up:** Keep escalation chain informed of progress
- **Close the loop:** Confirm resolution with all stakeholders

For detailed risk management procedures, see [Risk Management Checklist](./octoacme-risk-management-checklist.md).

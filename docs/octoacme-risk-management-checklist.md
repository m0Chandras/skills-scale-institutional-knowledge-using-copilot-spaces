# OctoAcme — Risk Management Checklist

## Purpose
Structured approach to identify, assess, track, and mitigate risks throughout the project lifecycle. Use this checklist during project initiation, planning, and ongoing execution.

## Risk Identification

### Initial Risk Assessment (Project Initiation)
- [ ] Project kickoff risk brainstorming session conducted
- [ ] Technical risks identified (architecture, technology, complexity)
- [ ] Resource risks identified (availability, skills, capacity)
- [ ] Schedule risks identified (dependencies, timeline, scope)
- [ ] Stakeholder risks identified (alignment, communication, expectations)
- [ ] External risks identified (vendors, regulations, market)
- [ ] Security and compliance risks identified
- [ ] Operational risks identified (deployment, monitoring, support)

### Ongoing Risk Identification
- [ ] Risk review included in weekly team syncs
- [ ] Team members encouraged to raise risks proactively
- [ ] Dependencies tracked and risk-assessed regularly
- [ ] Change requests evaluated for risk impact
- [ ] Retrospectives include risk identification
- [ ] External environment scanned for new risks

## Risk Assessment

### Risk Analysis Framework
For each identified risk, document:
- [ ] Risk ID and description
- [ ] Impact level (Critical/High/Medium/Low)
- [ ] Likelihood/Probability (High/Medium/Low)
- [ ] Risk score (Impact × Likelihood)
- [ ] Risk category (Technical/Resource/Schedule/Business/External)
- [ ] Risk owner assigned
- [ ] First identified date

### Impact Assessment Criteria

**Critical Impact:**
- Project failure or cancellation
- Major security breach or data loss
- Significant financial loss (>$100K)
- Severe reputation damage
- Legal or regulatory violation

**High Impact:**
- Major schedule delay (>4 weeks)
- Significant scope reduction
- Key team member loss
- Major customer dissatisfaction
- Important feature unavailable at launch

**Medium Impact:**
- Moderate schedule delay (1-4 weeks)
- Minor scope reduction
- Temporary resource shortage
- Quality degradation requiring rework
- Support burden increase

**Low Impact:**
- Minimal schedule delay (<1 week)
- Negligible scope impact
- Easily mitigated issue
- Minor inconvenience

### Likelihood Assessment Criteria

**High Likelihood (>60%):**
- Has occurred on similar projects
- Multiple risk indicators present
- Limited control over risk factors
- No clear mitigation path

**Medium Likelihood (30-60%):**
- Could occur based on current trajectory
- Some risk indicators present
- Moderate control over risk factors
- Mitigation possible but challenging

**Low Likelihood (<30%):**
- Unlikely based on current conditions
- Few risk indicators present
- Strong control over risk factors
- Clear mitigation options available

## Risk Prioritization

### Risk Priority Matrix
- [ ] Critical/High risks prioritized for immediate action
- [ ] Medium risks tracked and monitored
- [ ] Low risks accepted or monitored passively
- [ ] Top 5-10 risks actively managed at any time
- [ ] Risk register sorted by priority

### High-Priority Risk Criteria
Risks requiring immediate attention:
- [ ] Critical impact risks (regardless of likelihood)
- [ ] High impact + High likelihood risks
- [ ] Risks blocking critical path
- [ ] Risks with imminent trigger dates
- [ ] Escalated risks from stakeholders

## Risk Mitigation

### Mitigation Strategy Development
For each high-priority risk:
- [ ] Mitigation strategy defined (Avoid/Reduce/Transfer/Accept)
- [ ] Specific mitigation actions identified
- [ ] Mitigation action owners assigned
- [ ] Mitigation timeline established
- [ ] Success criteria defined
- [ ] Resource requirements identified

### Mitigation Strategy Types

**Avoid:**
- [ ] Remove risk source
- [ ] Change project approach
- [ ] Descope risky features
- [ ] Use proven technology instead

**Reduce:**
- [ ] Implement preventive controls
- [ ] Add buffer time or resources
- [ ] Conduct proof-of-concept
- [ ] Increase testing or validation
- [ ] Add monitoring and alerts

**Transfer:**
- [ ] Outsource risky work
- [ ] Use managed services
- [ ] Purchase insurance
- [ ] Shift responsibility to vendor

**Accept:**
- [ ] Document accepted risk
- [ ] Define contingency plan
- [ ] Allocate contingency budget/time
- [ ] Monitor risk indicators

### Contingency Planning
For critical risks:
- [ ] Contingency plan documented
- [ ] Trigger conditions defined
- [ ] Contingency actions detailed
- [ ] Contingency resources identified
- [ ] Escalation path defined
- [ ] Plan communicated to stakeholders

## Risk Monitoring

### Regular Risk Reviews
- [ ] Weekly risk review in team sync
- [ ] Monthly detailed risk review with stakeholders
- [ ] Risk register updated weekly
- [ ] New risks added promptly
- [ ] Resolved risks closed with lessons learned
- [ ] Risk trends analyzed and reported

### Risk Indicators & Triggers
- [ ] Leading indicators defined for top risks
- [ ] Trigger thresholds established
- [ ] Monitoring mechanisms in place
- [ ] Alert/notification system configured
- [ ] Indicator trends reviewed regularly

### Risk Status Tracking
For each active risk:
- [ ] Current status documented (Active/Mitigating/Closed)
- [ ] Mitigation progress tracked
- [ ] Ownership confirmed and active
- [ ] Impact/likelihood reassessed periodically
- [ ] Changes in risk profile noted

## Risk Communication

### Stakeholder Communication
- [ ] Risk register shared with stakeholders
- [ ] High/critical risks escalated promptly
- [ ] Risk status included in weekly reports
- [ ] Risk dashboard maintained (if applicable)
- [ ] Stakeholders notified of risk materialization

### Escalation Paths
- [ ] Team-level: Raised in daily standup or team sync
- [ ] PM-level: Project Manager coordinates mitigation
- [ ] Leadership-level: Product Lead or Tech Lead engaged
- [ ] Executive-level: Business Stakeholder or Sponsor involved
- [ ] Crisis-level: Incident response team activated

### Risk Communication Template
```
Risk Summary: [One-line description]
Impact: [Critical/High/Medium/Low]
Likelihood: [High/Medium/Low]
Status: [Active/Mitigating/Closed]
Owner: [Name]
Mitigation Plan: [Brief summary]
Help Needed: [Specific asks]
Next Review: [Date]
```

## Risk Documentation

### Risk Register Maintenance
- [ ] Risk register template in use (see template below)
- [ ] All risks documented with required fields
- [ ] Register accessible to all team members
- [ ] Register version controlled or in shared location
- [ ] Archive of closed risks maintained for lessons learned

### Risk Register Template
| ID | Description | Category | Impact | Likelihood | Score | Owner | Status | Mitigation Plan | Last Updated |
|----|-------------|----------|--------|------------|-------|-------|--------|----------------|--------------|
| R-001 | | | | | | | | | |

### Risk Reporting
- [ ] Weekly status report includes top risks
- [ ] Monthly risk summary for stakeholders
- [ ] Quarterly risk trend analysis
- [ ] Risk metrics tracked (# new, # closed, # escalated)
- [ ] Lessons learned from materialized risks

## Special Risk Categories

### Technical Risks
- [ ] Architecture scalability assessed
- [ ] Technology maturity evaluated
- [ ] Integration complexity analyzed
- [ ] Technical debt impact assessed
- [ ] Performance and reliability risks identified

### Security Risks
- [ ] Security Champion consulted
- [ ] Threat modeling completed
- [ ] Vulnerability assessment conducted
- [ ] Data protection risks evaluated
- [ ] Compliance risks identified
- [ ] Security incident response plan ready

### Resource Risks
- [ ] Key person dependencies identified
- [ ] Skill gaps assessed
- [ ] Capacity constraints evaluated
- [ ] Contractor/vendor reliability assessed
- [ ] Knowledge transfer risks mitigated

### Schedule Risks
- [ ] Critical path dependencies mapped
- [ ] Buffer time allocated for high-risk items
- [ ] External dependencies tracked
- [ ] Integration timing risks assessed
- [ ] Release date flexibility evaluated

## Risk Closure

### Risk Resolution
- [ ] Mitigation successfully implemented
- [ ] Risk no longer applicable (conditions changed)
- [ ] Risk transferred or accepted formally
- [ ] Stakeholders notified of closure
- [ ] Lessons learned documented

### Lessons Learned Capture
- [ ] What triggered the risk?
- [ ] How effective was the mitigation?
- [ ] What would we do differently?
- [ ] What can prevent similar risks in future?
- [ ] Lessons shared with team and organization

## Related Documentation
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Roles and Personas](./octoacme-roles-and-personas.md) - See Project Manager role

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

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- **Stakeholder Champion** identifies stakeholder groups and their communication needs (e.g., engineering, sales, support)
- **PM and Stakeholder Champion** provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- **Data Analyst** includes relevant metrics in stakeholder reports
- Coordinate with **User Experience Lead** when gathering user feedback from stakeholders

## Communication Templates

### Weekly Status Template
- **Prepared by**: PM
- **Contributors**: Scrum Master (team velocity), Data Analyst (metrics), Stakeholder Champion (stakeholder feedback)
- **Content**:
  - Progress this week:
  - Next steps:
  - Risks & blockers:
  - Key metrics update:
  - Ask / decisions needed:

### Incident Communication
- **Led by**: PM and on-call engineer
- **Stakeholder Champion** coordinates external communication
- **Content**:
  - Triage summary
  - Actions being taken
  - Expected timeline
  - Post-incident blameless retrospective scheduled (facilitated by Scrum Master)

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call

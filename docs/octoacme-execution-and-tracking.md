# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- **Daily standups** (15 min) — facilitated by Scrum Master, focus on progress, blockers, dependencies
- **Weekly delivery sync** — PM shows progress, updates, and flagged risks; Data Analyst shares relevant metrics
- **Sprint demos/reviews** — Scrum Master facilitates; team shows completed work to stakeholders
- **Retrospectives** — Scrum Master facilitates reflection and continuous improvement actions

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic (responsibility: Developers)
- Integration tests where applicable (responsibility: Developers, QA)
- End-to-end smoke tests for critical flows before release (responsibility: QA)
- Usability testing and design reviews (responsibility: User Experience Lead)
- Security scanning in CI (automated)
- Manual QA for feature acceptance when needed (responsibility: QA)

## Reporting & Metrics
- Track velocity and burndown (responsibility: Scrum Master, Data Analyst)
- Monitor success metrics identified in the Project One-pager (responsibility: Data Analyst, PdM)
- Use dashboards for key signals: errors, latency, usage (responsibility: Data Analyst)
- Regular metric reviews with stakeholders (responsibility: Data Analyst, Stakeholder Champion)

## Blocker Escalation
- **Level 1**: Team-level triage in daily standup (facilitated by Scrum Master)
- **Level 2**: Scrum Master and PM escalate to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues (via PM and Stakeholder Champion)

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly

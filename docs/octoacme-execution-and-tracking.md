# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies, led by Scrum Master
- Weekly delivery sync — show progress, updates, flagged risks (Scrum Master, Technical Architect, Stakeholder Rep invited)
- Demo/Review at the end of each sprint/milestone (include Stakeholder Rep, UX Designer, Technical Architect for feedback)

## Workflows
- Use the project board (e.g., GitHub Projects): Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Automated tests and linting in CI before review
  - At least one approval before merging (by assigned persona/reviewer)
  - Reviewer role assignment (Scrum Master, QA, Tech Architect for complex changes)

## Quality & Testing
- Unit tests for new logic (Developer/QA)
- Integration tests (Technical Architect validates)
- End-to-end smoke tests for critical flows (QA/UX Designer feedback)
- Security scanning in CI (Technical Architect reviews)
- Manual QA for feature acceptance

## Reporting & Metrics
- Track velocity and burndown (Scrum Master, PM)
- Monitor success metrics (as in One-pager)
- Dashboards for key signals (errors, latency, usage) shared with Stakeholder Rep

## Blocker Escalation
- Level 1: Team triage in standup (Scrum Master leads)
- Level 2: PM escalates to Product Lead, Tech Architect, dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues (Stakeholder Rep included)

## Execution Checklist
- [ ] Branching and PR conventions documented
- [ ] CI configured for tests/lint (Technical Architect)
- [ ] Regular demos scheduled (all personas invited)
- [ ] Risk register updated weekly (owners by persona)

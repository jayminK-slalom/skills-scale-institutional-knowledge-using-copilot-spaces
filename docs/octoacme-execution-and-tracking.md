# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies (facilitated by Scrum Master if using Agile)
- Weekly delivery sync — show progress, updates, and flagged risks (PM coordinates with Product Manager)
- Demo/Review at the end of each sprint or milestone (Product Manager accepts work, UX Designer reviews user experience, stakeholders provide feedback)
- Sprint retrospectives (facilitated by Scrum Master) to identify improvements

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
- UX Designer conducts usability testing for user-facing features
- BA validates that delivered features meet business requirements and coordinates UAT

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (Scrum Master facilitates resolution)
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues or organizational blockers

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled with stakeholders
- [ ] Risk register updated weekly
- [ ] Scrum Master tracking and reporting velocity (if Agile)
- [ ] UX Designer involved in design reviews and usability testing
- [ ] BA available for requirements clarification and UAT coordination

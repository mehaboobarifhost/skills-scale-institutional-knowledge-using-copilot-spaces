# OctoAcme — Release Checklist

Purpose: A concise, role-aware checklist to standardize release readiness and reduce operational risk.

Pre-release (3-7 days before planned release)
- [ ] Confirm included PRs are merged and linked to acceptance criteria
- [ ] Smoke tests defined and assigned
- [ ] All critical bugs triaged (severity & owners documented)
- [ ] Rollback plan drafted and owners assigned
- [ ] Stakeholder communication scheduled (who, when, channel)

Release day
- [ ] Release Manager runs pre-deploy checklist and confirms readiness
- [ ] CI pipeline green for release branch/tag
- [ ] Backup/snapshot performed if applicable
- [ ] Deploy to staging and execute smoke tests
- [ ] Stakeholders notified of planned deployment window
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy smoke tests and verify key metrics
- [ ] Announce release status and link release notes

Post-release
- [ ] Monitor alerts/dashboards for 1-24 hours depending on risk
- [ ] Capture any immediate action items in the project board
- [ ] Publish final release notes and known issues
- [ ] Conduct a short post-release review (if incidents occurred)

Role-specific responsibilities
- Release Manager: Owns the checklist, coordinates communication, validates sign-off for each step
- Technical Writer: Drafts release notes and coordinates stakeholder messaging
- Developers: Ensure feature flags, migrations, and rollback paths are implemented and tested
- QA: Execute smoke tests and validate critical flows
- Project Manager: Ensure stakeholder lists and post-release actions are tracked

Acceptance criteria for a release
- All checklist items marked done or explicitly deferred with approval
- Rollback plan validated and tested
- Stakeholders informed and support on-call assigned

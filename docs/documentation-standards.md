# OctoAcme — Documentation Standards

Purpose: Define standards and lightweight governance for authoring, reviewing, and maintaining project documentation.

Core principles
- Keep docs close to the code and project artifacts (docs/ in repo)
- Prefer short, task-focused documents (how-tos, runbooks, templates)
- Ownership: each doc should list an owner and last-updated date

Templates (examples)
- README pattern: Purpose, Getting Started, How to contribute, Contacts
- Runbook pattern: Symptoms, Diagnosis, Mitigation, Rollback, Postmortem links
- Release notes: Summary, Notable changes, Migration steps, Known issues

Authoring workflow
- Create or update docs in a branch and open a PR; include reviewers: Technical Writer (if available), Project Manager, and a relevant Engineer
- Use the docs checklist in PR description: Owner, Summary of changes, Impact, Reviewers
- Merge after at least one approval and green CI (if docs linting is configured)

Review cadence & maintenance
- Owners should review and update their docs quarterly or after major changes
- During project close, ensure docs referenced in the One-pager are current

Onboarding & discoverability
- Add a short index or link list in project README pointing to critical docs
- Technical Writer or PM to maintain a living table of contents for shared processes

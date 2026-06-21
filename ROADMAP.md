# Canor-Infinitum Org Roadmap

This roadmap tracks shared organizational standards, workflows, and automation across Canor-Infinitum repositories.

## Purpose
The goal is to create a consistent, low-friction contributor experience and a scalable maintenance model across the organization.

## Phases

### Phase 1 — Foundation
**Goal:** Establish the baseline contribution and governance structure for the org.

#### Scope
- `CONTRIBUTING.md`
- `SECURITY.md`
- Pull request template
- Issue templates
- `CODEOWNERS`
- `profile/README.md`
- Org overview in `.github/README.md`

#### Success criteria
- Contributors know how to open issues and PRs
- Security reporting path exists
- Ownership and review routing are defined
- Every repo has consistent contributor-facing entry points

#### Typical issue types
- Docs setup
- Templates
- Policy files
- Ownership mapping

---

### Phase 2 — Automation
**Goal:** Reduce manual work and standardize repetitive repo maintenance.

#### Scope
- Shared CI workflows
- Label automation
- Stale issue/PR automation
- Docs validation
- Dependency validation
- Security scanning

#### Success criteria
- Repos share a consistent CI baseline
- Triage is partially automated
- Documentation and security checks run automatically

#### Typical issue types
- GitHub Actions
- Workflow reuse
- Lint/test/build automation
- Repository hygiene automation

---

### Phase 3 — Governance
**Goal:** Make maintenance, merges, and releases predictable and safe.

#### Scope
- Branch protection standards
- Review requirements
- Merge strategy policy
- Release and tagging policy
- Incident response workflow
- Escalation and ownership rules

#### Success criteria
- Protected branches follow a standard policy
- Merge/release behavior is documented
- Escalation paths are clear

#### Typical issue types
- Policy updates
- Release process
- Review rules
- Maintenance process

---

### Phase 4 — Scale
**Goal:** Make org-wide processes reusable across all current and future repositories.

#### Scope
- Reusable workflows
- Backport automation
- Release automation
- Shared operational handbook
- Cross-repo maintenance patterns

#### Success criteria
- New repos can adopt standards quickly
- Shared workflows reduce duplication
- Maintenance is repeatable and observable

#### Typical issue types
- Org platform work
- Reusable automation
- Cross-repo sync
- Long-term maintenance tooling

---

## Tracking conventions

### Labels
Each issue or PR should be tagged with at least:
- one phase label
- one work-type label
- one priority or status label when applicable

### Phase labels
- `phase:foundation`
- `phase:automation`
- `phase:governance`
- `phase:scale`

### Recommended work-type labels
- `type:docs`
- `type:infra`
- `type:security`
- `type:workflow`
- `type:policy`
- `type:maintenance`

### Recommended status labels
- `status:blocked`
- `status:needs-review`
- `status:in-progress`
- `status:ready`
- `status:backlog`

### Recommended priority labels
- `priority:critical`
- `priority:high`
- `priority:medium`
- `priority:low`

## Operating model

1. Add new org-wide work to the appropriate phase.
2. Tag issues and PRs with the matching phase label.
3. Use status labels to show progress.
4. Keep the roadmap updated as standards evolve.

## Notes
- This roadmap is org-wide and applies across repositories.
- Repositories may adopt phases at different speeds, but the label taxonomy should stay consistent.
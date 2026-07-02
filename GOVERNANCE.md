# Governance

This document defines how Rachel Capital is governed as a long-term repository and software-like project.

The goal is durability, consistency, and traceable decision-making.

## Governance Principles

- GitHub is the single source of truth.
- Investment discussions happen in ChatGPT.
- Approved decisions are written back into GitHub.
- Every important investment decision must be documented.
- Every architecture change requires review.
- Every release should have release notes.
- Repository history is more important than chat history.
- The repository should remain maintainable for many years.

## Source Of Truth Rules

| Topic | System Of Record |
| --- | --- |
| Repository structure | GitHub |
| Documentation history | GitHub |
| Pull requests and reviews | GitHub |
| Release notes | GitHub |
| Working discussion | ChatGPT |
| Approved operating output | GitHub |

ChatGPT may host analysis and discussion, but GitHub must hold the approved and durable result.

## Documentation Rules

- Important investment decisions belong in `decisions/Decision_Log.md`.
- Stable investment rules belong in `docs/`.
- Current portfolio state belongs in `Dashboard.md` and `account/`.
- Governance rules belong in `.ai/`, `GOVERNANCE.md`, and `CONTRIBUTING.md`.
- If a decision matters later, it must be written to the repository.

## Change Control

- Never commit directly to `main`.
- Every meaningful change should start from an issue.
- Every sprint must have a clear goal.
- Every pull request must include why, what changed, impact, and next sprint.
- Every architecture change requires explicit review before merge.
- Every merge should produce a repository history that is understandable without chat context.

## Review Requirements

| Change Type | Review Requirement |
| --- | --- |
| Investment principle or rule change | Review for consistency and downstream impact |
| Thesis structure change | Review for template compatibility |
| Dashboard or portfolio structure change | Review for clarity and maintenance cost |
| Engineering architecture change | Review before merge |
| Workflow or governance change | Review before merge |

## Recommended Label System

| Label | Purpose |
| --- | --- |
| `architecture` | Repository structure and system design work |
| `dashboard` | Dashboard changes and portfolio visibility work |
| `automation` | Future tooling and process automation work |
| `documentation` | Markdown, templates, and documentation quality |
| `investment` | Investment operating documents and decision structure |
| `research` | Sector, macro, and thematic research work |
| `bug` | Broken behavior or incorrect repository state |
| `enhancement` | Improvements to existing workflows or documents |
| `weekly-review` | Weekly review tasks and outputs |
| `monthly-review` | Monthly review tasks and outputs |
| `good-first-issue` | Starter work for future contributors |

## Recommended Milestones

| Milestone | Purpose |
| --- | --- |
| `Sprint 1 Foundation` | Initial repository structure and templates |
| `Sprint 1.1 Governance` | Governance, workflow, and project standards |
| `Sprint 2 Automation` | Future system tooling and automation work |
| `Sprint 3 Workflow` | Expanded development workflow and release discipline |
| `Sprint 4 Market Data` | Future data integration work |
| `Sprint 5 Dashboard` | Future dashboard evolution |

## Release Strategy

Use milestone-based semantic project versions.

| Version | Release Theme |
| --- | --- |
| `v1.0` | Foundation |
| `v1.1` | Governance |
| `v2.0` | Automation |
| `v3.0` | Workflow |
| `v4.0` | Data |
| `v5.0` | Dashboard |

### Release Rules

- Every release should summarize what changed and why it matters.
- Release notes should link to the relevant sprint or pull requests.
- Breaking structural changes should be called out explicitly.
- A release without notes is incomplete.

## Repository Standards

- Favor simple structures over broad frameworks.
- Avoid duplicate content across documents.
- Update templates before creating alternative formats.
- Prefer explicit ownership over informal assumptions.
- Keep the repository usable without external tools.

## Definition Of Done

Sprint 1.1 is complete only if:

- governance files exist
- repository workflow is fully documented
- future contributors can understand how to work without reading chat history
- repository has clear long-term engineering standards
- all documentation is internally consistent

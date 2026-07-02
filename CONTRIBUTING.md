# Contributing

Rachel Capital accepts contributions through a disciplined GitHub workflow.

The repository is maintained like a long-term software project even when the change is documentation-first.

## Contribution Flow

Every contribution should follow this path:

Fork / Branch -> Issue -> Sprint -> Pull Request -> Review -> Merge -> Release

## Before You Start

- Read `GOVERNANCE.md`.
- Read `.ai/WORKFLOW.md`.
- Confirm that the change fits an existing issue or open a new one.
- Define the sprint goal before making broad edits.

## Branching

- Never commit directly to `main`.
- Create a branch for each unit of work.
- Keep one branch focused on one sprint or one change theme.

### Recommended Branch Names

- `feature/sprint-x`
- `feature/dashboard`
- `feature/thesis`
- `fix/dashboard`
- `docs/principles`

## Commit Messages

Use short, readable commit messages in imperative form.

Recommended format:

`type(scope): summary`

Examples:

- `docs(governance): add workflow and team guides`
- `feat(dashboard): refine portfolio snapshot layout`
- `fix(thesis): remove duplicate sell condition section`

Recommended commit types:

- `docs`
- `feat`
- `fix`
- `refactor`
- `chore`

## Pull Requests

Every contribution must be submitted through a pull request.

### Required Pull Request Description

Every PR should explain:

- why
- what changed
- impact
- next sprint

### Pull Request Rules

- link the related issue
- keep scope narrow enough to review
- update documentation when behavior or structure changes
- resolve duplicate content before requesting review
- do not mark a PR ready until the description is complete

## Review

- Never skip review.
- Architecture, workflow, and governance changes require explicit review.
- If review comments expose unclear reasoning, improve the PR description and the changed documents.

## Merge

- Merge only after review is complete.
- Prefer readable history over high commit volume.
- If the PR changes repository structure, confirm downstream documents were updated.

## Release

- Every merged sprint should produce release notes.
- Release notes should summarize scope, impact, and follow-up work.

## Documentation Standard

- Keep one H1 per file.
- Use clear section names.
- Prefer compact tables for metadata and tracking.
- Keep Markdown style consistent with the rest of the repository.

## Contributor Expectation

Contributors should leave the repository clearer than they found it.

If a change adds complexity, the PR should explain why that complexity is justified.

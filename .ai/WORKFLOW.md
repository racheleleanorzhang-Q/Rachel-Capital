# Workflow

Every repository change follows one workflow:

Issue -> Sprint -> Pull Request -> Review -> Merge -> Release

This workflow exists to keep repository history reliable, reviewable, and maintainable over multiple years.

## Workflow Stages

| Stage | Purpose | Required Output | Primary Owner |
| --- | --- | --- | --- |
| Issue | Define the problem or change request | A documented issue with scope and intent | Rachel / ChatGPT / Codex |
| Sprint | Define the short-term goal | A sprint goal with clear completion criteria | Rachel / Codex |
| Pull Request | Propose the implementation | A PR with complete description and changed files | Contributor |
| Review | Validate quality and consistency | Review comments, requested changes, or approval | ChatGPT / Codex / Rachel |
| Merge | Accept the change into `main` | Merged PR | Maintainer |
| Release | Publish what changed | Release notes tied to a version or sprint output | Codex |

## Stage Requirements

### 1. Issue

- Every meaningful change starts with an issue.
- The issue should state the problem, scope, and expected result.
- If the work affects investment content, reference the affected documents.
- If the work affects architecture, identify the impacted layer.

### 2. Sprint

- Every sprint must have a clear goal.
- The sprint should define what is included and what is excluded.
- Large requests should be broken into separate sprints rather than merged as one broad change.

### 3. Pull Request

- Never commit directly to `main`.
- Every change should be submitted through a pull request.
- Every pull request must explain:
  - why
  - what changed
  - impact
  - next sprint

### 4. Review

- Never skip review.
- Architecture changes require review before merge.
- Investment process changes should be reviewed for consistency with `GOVERNANCE.md` and the relevant operating documents.
- A PR is not ready to merge until review comments are addressed or explicitly resolved.

### 5. Merge

- Merge only after review is complete.
- Squash, merge, or rebase strategy may be chosen by the maintainer, but history should remain readable.
- If the PR description is incomplete, it should be fixed before merge.

### 6. Release

- Never skip release notes.
- Each release should summarize scope, impact, and follow-up work.
- Releases may map to versions, sprints, or both, but the release record must be written in GitHub.

## Workflow Rules

- GitHub is the execution system for repository change management.
- Chat history may inform work, but it does not replace issues, PRs, or release notes.
- If a change cannot be explained clearly in an issue and PR, it is not ready.
- Duplicate or overlapping work should be resolved before merge, not after.

## Definition of a Ready Pull Request

| Check | Required |
| --- | --- |
| Issue exists | Yes |
| Sprint goal is clear | Yes |
| Why is explained | Yes |
| What changed is explained | Yes |
| Impact is explained | Yes |
| Next sprint is identified | Yes |
| Documentation is updated | Yes |
| Ready for review | Yes |

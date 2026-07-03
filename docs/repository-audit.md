# Repository Audit

This audit captures the repository state before the July 2026 cleanup that removed placeholder documents and simplified the operating structure.

## Scope

This audit covers all Markdown files in the repository, including hidden workflow docs under `.ai/` and `.github/`.

Reference status below means explicit Markdown-level references from other Markdown files by path or filename. GitHub templates under `.github/` are still operationally used by GitHub even when no other document links to them.

## Overall Assessment

The repository has a solid governance scaffold, but the operating content layer is still mostly scaffolded. The main structural problems are:

- duplicate governance/architecture responsibility across several documents
- many live-content documents that are present but not yet populated
- many content documents that are not linked from the main navigation or workflow docs
- a few workflow/template mismatches against the current `TEAM.md` and workflow rules

## Repository Tree

```text
.
├── .ai
│   ├── ARCHITECTURE.md
│   ├── TEAM.md
│   └── WORKFLOW.md
├── .github
│   ├── ISSUE_TEMPLATE
│   │   ├── automation.md
│   │   ├── bug.md
│   │   ├── feature.md
│   │   ├── investment-thesis-update.md
│   │   ├── monthly-review.md
│   │   ├── research.md
│   │   └── weekly-review.md
│   └── PULL_REQUEST_TEMPLATE.md
├── account
│   ├── Current.md
│   └── History.md
├── assets
│   └── README.md
├── committee
│   └── README.md
├── decisions
│   └── Decision_Log.md
├── docs
│   ├── Investment_Principles.md
│   ├── Mistake_Book.md
│   ├── Trading_Rules.md
│   └── repository-audit.md
├── monthly
│   └── README.md
├── releases
│   ├── v1.0.md
│   └── v1.1.md
├── research
│   ├── AI.md
│   ├── Gold.md
│   ├── Internet.md
│   └── Macro.md
├── templates
│   ├── Dashboard_Template.md
│   ├── Meeting_Template.md
│   ├── Monthly_Review_Template.md
│   ├── README.md
│   └── Weekly_Review_Template.md
├── thesis
│   ├── 三花智控.md
│   ├── 北京银行.md
│   ├── 理想汽车.md
│   ├── 紫金矿业.md
│   └── 美团.md
├── watchlist
│   └── Watchlist.md
├── weekly
│   └── 2026
│       └── README.md
├── ARCHITECTURE.md
├── CONTRIBUTING.md
├── Dashboard.md
├── GOVERNANCE.md
└── README.md
```

## File Inventory

| Path | Purpose | Lines | Empty / Placeholder | Referenced By Other Docs |
| --- | --- | ---: | --- | --- |
| `.ai/ARCHITECTURE.md` | Defines the governance-layer architecture and the five-layer ownership model. It explains how knowledge, portfolio, engineering, workflow, and governance should stay separate. | 62 | No | Yes |
| `.ai/TEAM.md` | Defines contributor roles, ownership boundaries, and escalation rules. It is the source document for who owns what. | 61 | No | Yes |
| `.ai/WORKFLOW.md` | Defines the GitHub-centered change lifecycle from issue through release. It is the most explicit workflow spec in the repo. | 82 | No | Yes |
| `.github/ISSUE_TEMPLATE/automation.md` | GitHub issue template for automation proposals. It standardizes future tooling requests. | 26 | No | No |
| `.github/ISSUE_TEMPLATE/bug.md` | GitHub issue template for repository or workflow bugs. It captures expected vs actual behavior and impact. | 30 | No | No |
| `.github/ISSUE_TEMPLATE/feature.md` | GitHub issue template for structural or capability improvements. It captures scope and sprint goal. | 26 | No | No |
| `.github/ISSUE_TEMPLATE/investment-thesis-update.md` | GitHub issue template for updating an existing thesis. It frames thesis revisions as structured work requests. | 26 | No | No |
| `.github/ISSUE_TEMPLATE/monthly-review.md` | GitHub issue template for a monthly review request. It captures month, portfolio questions, and expected output. | 26 | No | No |
| `.github/ISSUE_TEMPLATE/research.md` | GitHub issue template for research requests. It captures topic, questions, and deliverable. | 26 | No | No |
| `.github/ISSUE_TEMPLATE/weekly-review.md` | GitHub issue template for a weekly review request. It captures week, risks, focus areas, and expected output. | 26 | No | No |
| `.github/PULL_REQUEST_TEMPLATE.md` | Default PR description scaffold. It asks for why, what changed, risks, future work, and a short checklist. | 26 | No | No |
| `ARCHITECTURE.md` | Explains the repository's functional information architecture. It describes the folder model and long-term design logic. | 56 | No | Yes |
| `CONTRIBUTING.md` | Defines contributor workflow, branching, commits, PR expectations, review, merge, and release norms. It is the practical collaborator guide. | 105 | No | Yes |
| `Dashboard.md` | Live top-level portfolio dashboard. It summarizes current state, recent changes, near-term attention items, and next actions. | 62 | Live but incomplete | Yes |
| `GOVERNANCE.md` | Defines repository governance, source-of-truth rules, change control, labels, milestones, and release strategy. It is the broad policy layer. | 121 | No | Yes |
| `README.md` | Main entrypoint and orientation document. It explains vision, structure, workflow, and roadmap. | 139 | No | No |
| `account/Current.md` | Live account baseline and immediate follow-up tracker. It is the current-state source behind the dashboard. | 32 | Live but incomplete | Yes |
| `account/History.md` | Periodic capital history log for structural asset changes and milestones. It is intended to capture time-series account history, not trades. | 20 | Placeholder | No |
| `assets/README.md` | Explains the purpose of `assets/` for non-Markdown supporting files. It is a directory guide, not an operating record. | 12 | No | No |
| `committee/README.md` | Usage guide for ad hoc committee meeting records outside weekly/monthly cadence. It defines naming and intended use. | 9 | No | No |
| `decisions/Decision_Log.md` | Master decision register plus a reusable decision entry template. It is central to process review but not yet populated with live decisions. | 62 | Placeholder | Yes |
| `docs/Investment_Principles.md` | Stable investment philosophy and portfolio construction principles. It is one of the core durable operating documents. | 55 | No | No |
| `docs/Mistake_Book.md` | Structured log for recurring, preventable investing mistakes and the rules created to avoid them. It is conceptually important but still scaffolded. | 56 | Placeholder | Yes |
| `docs/Trading_Rules.md` | Stable rules for buy/add/reduce/cash/risk behavior. The policy content is substantive, but the checklist block is still template-like. | 57 | Substantive with placeholder fields | No |
| `monthly/README.md` | Usage guide for live monthly strategic review files. It defines how future monthly records should be created and named. | 9 | No | No |
| `releases/v1.0.md` | Human-written release note for the foundation release. It records the initial structure and why it mattered. | 26 | No | No |
| `releases/v1.1.md` | Human-written release note for the governance release. It records the addition of team/workflow/governance scaffolding. | 26 | No | No |
| `research/AI.md` | Theme research note for AI. It is currently an unfilled research template. | 37 | Placeholder | No |
| `research/Gold.md` | Theme research note for Gold. It is currently an unfilled research template. | 37 | Placeholder | No |
| `research/Internet.md` | Theme research note for Internet. It is currently an unfilled research template. | 37 | Placeholder | No |
| `research/Macro.md` | Theme research note for Macro. It is currently an unfilled research template. | 37 | Placeholder | No |
| `templates/Dashboard_Template.md` | Reusable structural template for redesigning or regenerating the dashboard. It intentionally mirrors the live dashboard format. | 56 | Template | Yes |
| `templates/Meeting_Template.md` | Reusable template for ad hoc investment committee meetings. It defines agenda, discussion, decisions, and action items. | 47 | Template | Yes |
| `templates/Monthly_Review_Template.md` | Reusable template for monthly strategic reviews. It captures allocation, decision quality, mistakes, and next-month focus. | 80 | Template | Yes |
| `templates/README.md` | Explains what the templates directory is for and how to use it. It separates reusable structure from live records. | 14 | No | No |
| `templates/Weekly_Review_Template.md` | Reusable template for weekly investment committee reviews. It structures market, portfolio, risk, decision review, and actions. | 72 | Template | Yes |
| `thesis/三花智控.md` | Stock-level thesis document for 三花智控. It is currently a blank thesis skeleton. | 40 | Placeholder | No |
| `thesis/北京银行.md` | Stock-level thesis document for 北京银行. It is currently a blank thesis skeleton. | 40 | Placeholder | No |
| `thesis/理想汽车.md` | Stock-level thesis document for 理想汽车. It is currently a blank thesis skeleton. | 40 | Placeholder | No |
| `thesis/紫金矿业.md` | Stock-level thesis document for 紫金矿业. It is currently a blank thesis skeleton. | 40 | Placeholder | No |
| `thesis/美团.md` | Stock-level thesis document for 美团. It is currently a blank thesis skeleton. | 40 | Placeholder | No |
| `watchlist/Watchlist.md` | Candidate watchlist with buy/cancel triggers and target position fields. It exists structurally but is not populated. | 25 | Placeholder | No |
| `weekly/2026/README.md` | Usage guide for live weekly review records for 2026. It defines naming and warns against storing templates there. | 9 | No | No |

## Duplicate Responsibilities

### High-confidence overlaps

- `ARCHITECTURE.md` and `.ai/ARCHITECTURE.md`
  - Both define "architecture," but at different layers.
  - The distinction is understandable to a maintainer, but not obvious to a newcomer.
  - Risk: drift between repository structure guidance and governance-layer architecture guidance.

- `GOVERNANCE.md`, `CONTRIBUTING.md`, and `.ai/WORKFLOW.md`
  - All three restate the issue -> sprint -> PR -> review -> merge -> release lifecycle.
  - They are not pure duplicates, but responsibility boundaries are blurred enough that workflow drift is likely.

- `Dashboard.md` and `templates/Dashboard_Template.md`
  - This duplication is intentional, but the two files now carry overlapping ownership and maintenance semantics.
  - Risk: the live dashboard and the reusable structure drift apart.

### Lower-risk overlap

- `README.md` repeats parts of structure and workflow that also live in governance/architecture documents.
  - This is normal for a root README, but it increases maintenance cost if the deeper docs change.

## Orphan Documents

### High-confidence orphan content docs

These files are not explicitly referenced by other Markdown documents and are not obviously platform-discovered entrypoints:

- `account/History.md`
- `docs/Investment_Principles.md`
- `docs/Trading_Rules.md`
- `research/AI.md`
- `research/Gold.md`
- `research/Internet.md`
- `research/Macro.md`
- `thesis/三花智控.md`
- `thesis/北京银行.md`
- `thesis/理想汽车.md`
- `thesis/紫金矿业.md`
- `thesis/美团.md`
- `watchlist/Watchlist.md`

### Unreferenced but still structurally expected

These files also have no explicit inbound Markdown references, but their role is still clear from repository structure or GitHub behavior:

- `README.md`
- `.github/PULL_REQUEST_TEMPLATE.md`
- `.github/ISSUE_TEMPLATE/*.md`
- `assets/README.md`
- `committee/README.md`
- `monthly/README.md`
- `weekly/2026/README.md`
- `templates/README.md`
- `releases/v1.0.md`
- `releases/v1.1.md`

## Placeholder / TODO / Incomplete Files

### Live files that are present but not yet operationally complete

- `Dashboard.md`
- `account/Current.md`

### Placeholder operating records

- `account/History.md`
- `decisions/Decision_Log.md`
- `docs/Mistake_Book.md`
- `watchlist/Watchlist.md`

### Placeholder research and thesis content

- `research/AI.md`
- `research/Gold.md`
- `research/Internet.md`
- `research/Macro.md`
- `thesis/三花智控.md`
- `thesis/北京银行.md`
- `thesis/理想汽车.md`
- `thesis/紫金矿业.md`
- `thesis/美团.md`

### Intentional templates

- `templates/Dashboard_Template.md`
- `templates/Meeting_Template.md`
- `templates/Monthly_Review_Template.md`
- `templates/Weekly_Review_Template.md`

### Mixed case

- `docs/Trading_Rules.md`
  - The rules themselves are substantive.
  - The checklist section is still template-like.

## Files No Longer Used By The Current Architecture

No Markdown file is conclusively obsolete.

The stronger problem is not dead documents but under-linked and under-populated documents. Several files are idle today, but they are still consistent with the intended architecture:

- `assets/README.md`
- `committee/README.md`
- `monthly/README.md`
- `weekly/2026/README.md`
- `account/History.md`

## Documents Potentially Inconsistent With TEAM / Workflow Rules

### TEAM ownership mismatch

- `templates/Dashboard_Template.md`
  - It says `Updated By` is `Rachel / ChatGPT`.
  - `.ai/TEAM.md` assigns dashboard ownership to Codex.
  - This is the clearest role inconsistency in the current docs.

### Workflow enforcement gaps

- `.github/PULL_REQUEST_TEMPLATE.md`
  - `.ai/WORKFLOW.md` and `CONTRIBUTING.md` require PRs to explain `why`, `what changed`, `impact`, and `next sprint`.
  - The PR template has `Why`, `What Changed`, `Risks`, and `Future Work`, but no explicit `Impact` field and no explicit `Next Sprint` field.

- `.github/ISSUE_TEMPLATE/bug.md`
- `.github/ISSUE_TEMPLATE/investment-thesis-update.md`
- `.github/ISSUE_TEMPLATE/monthly-review.md`
- `.github/ISSUE_TEMPLATE/research.md`
- `.github/ISSUE_TEMPLATE/weekly-review.md`
  - `.ai/WORKFLOW.md` expects meaningful work to start with an issue that clearly states scope and expected result, and architecture-affecting work should identify the impacted layer.
  - Only some issue templates ask for a sprint goal or architecture/layer impact explicitly.
  - Result: the workflow docs are stricter than the issue intake forms.

### Minor workflow wording drift

- `CONTRIBUTING.md` describes `Fork / Branch -> Issue -> Sprint -> Pull Request -> Review -> Merge -> Release`.
- `.ai/WORKFLOW.md` describes `Issue -> Sprint -> Pull Request -> Review -> Merge -> Release`.
- This is not a major contradiction, but it is still workflow drift across the governance docs.

## Summary Judgment

The repository is architecturally coherent at the governance level but operationally incomplete at the content level.

The highest-value cleanup targets before further feature work are:

1. Clarify the boundary between `ARCHITECTURE.md` and `.ai/ARCHITECTURE.md`.
2. Consolidate or cross-link `GOVERNANCE.md`, `CONTRIBUTING.md`, and `.ai/WORKFLOW.md` to reduce workflow drift.
3. Decide whether thesis/research/watchlist/history files should be populated now or hidden from the main operating loop until they are real.
4. Link currently orphaned core content documents from `README.md`, `Dashboard.md`, or the relevant directory READMEs.
5. Align dashboard and GitHub templates with the actual `TEAM.md` ownership and workflow requirements.

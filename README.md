# Rachel Capital

Rachel Capital is a personal investment operating system.

It is designed to improve decision quality over time through disciplined review, explicit rules, and durable knowledge capture. It is not designed to predict markets, chase activity, or optimize for frequent trading.

## Vision

Build a better investor.

The repository exists to support long-term thinking in five areas:

- investment committee work
- market analysis
- investment thesis management
- periodic review
- portfolio decision discipline

## Philosophy

Rachel Capital treats investing as an operating process rather than a stream of trades.

The system is built on four ideas:

1. Portfolio quality matters more than isolated stock opinions.
2. Written reasoning matters more than memory.
3. Review quality matters more than activity level.
4. A repository should accumulate judgment, not just records.

## Repository Structure

| Path | Purpose |
| --- | --- |
| `Dashboard.md` | One-page operating view of the current portfolio. |
| `account/` | Current account state and capital history. |
| `weekly/` | Weekly review templates and future weekly records by year. |
| `monthly/` | Monthly review templates and future monthly records. |
| `decisions/` | Decision log and reusable decision format. |
| `docs/` | Stable operating rules, principles, and mistake management. |
| `thesis/` | Stock-level thesis documents with one unified template. |
| `watchlist/` | Candidates under observation with explicit triggers. |
| `research/` | Theme and sector research using a shared structure. |
| `assets/` | Supporting files for future reports and visuals. |
| `.ai/` | Team, workflow, and architecture guidance for AI contributors. |
| `.github/` | Pull request and issue templates for standardized project changes. |
| `GOVERNANCE.md` | Project rules, release discipline, and long-term standards. |
| `CONTRIBUTING.md` | Contribution workflow for future collaborators. |
| `ARCHITECTURE.md` | Rationale for the repository design. |

## Workflow

The intended operating loop is simple:

1. Update `Dashboard.md` to reflect the current state.
2. Maintain `account/Current.md` after any meaningful portfolio change.
3. Record each non-trivial action in `decisions/Decision_Log.md`.
4. Update stock theses when evidence changes, not only after trades.
5. Run a weekly review to capture market context, portfolio changes, and risks.
6. Run a monthly review to evaluate decision quality and capital allocation.
7. Add recurring errors to `docs/Mistake_Book.md` so they become part of the operating memory.

Project changes follow a separate governance workflow documented in `.ai/WORKFLOW.md` and `CONTRIBUTING.md`:

1. Open an issue.
2. Define the sprint goal.
3. Submit a pull request.
4. Complete review.
5. Merge to `main`.
6. Publish release notes.

## Maintenance Principles

This repository is intentionally conservative.

- One document should have one job.
- Stable rules live in `docs/`; time-based records live in `weekly/`, `monthly/`, and `decisions/`.
- Reusable templates should be copied, not rewritten from scratch.
- Tables should remain compact and easy to scan.
- New sections should only be added when they support recurring decisions.
- The structure should stay readable without any scripts or automation.

## Roadmap

### Sprint 1: Foundation

- establish repository structure
- standardize document formats
- define operating principles and trading rules
- create durable templates for review and decisions

### Sprint 1.1: Governance

- define team responsibilities
- standardize development workflow
- establish contribution and release rules
- make GitHub the single source of truth

### Sprint 2: Operating Rhythm

- begin real weekly and monthly records
- refine dashboard fields based on actual usage
- sharpen thesis quality and review discipline

### Sprint 3: Knowledge Depth

- expand sector and macro research
- improve watchlist quality
- strengthen mistake prevention and decision review

## Future Versions

Future versions may add automation, structured data extraction, or reporting support, but only after the manual workflow proves stable.

The foundation rule is simple: process first, tooling second.

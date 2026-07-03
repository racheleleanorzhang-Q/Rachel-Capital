# Architecture

This repository is structured as an operating system for investment decision-making, not as an analysis dump and not as a traditional software application.

## Design Logic

The architecture separates documents by function:

- current-state views live at the top level and in `account/`
- recurring reviews live in `weekly/` and `monthly/`
- committee workflows live in `committee/`
- action records live in `decisions/`
- stable rules live in `docs/`
- asset-specific thinking lives in `thesis/`
- idea pipelines live in `watchlist/`
- non-position research lives in `research/`
- reusable structures live in `templates/`
- release history lives in `releases/`

This separation keeps permanent knowledge distinct from time-based records.

## Why This Works Long Term

The structure is designed around future maintenance:

- low coupling: each folder has a clear responsibility
- high readability: a human can find the right document quickly
- future automation readiness: headings and tables are predictable
- low overhead: the system works without scripts, APIs, or workflows

Sprint 1.1 adds a governance layer through `.ai/`, `GOVERNANCE.md`, `CONTRIBUTING.md`, and `.github/` templates so the repository can also operate like a disciplined long-term software project.

Sprint 2 adds the operating layer by making the dashboard, recurring reviews, committee meetings, release notes, thesis maintenance, and decision evaluation function as one continuous working system.

Issue #001 further clarifies that live state and reusable structure must remain separate: `Dashboard.md` is permanently live, while reusable formats belong in `templates/`.

## Documentation Standards

Every document follows the same principles:

- one H1 title
- short purpose-oriented sections
- compact tables for status, metadata, and logs
- plain language over narrative writing
- reusable templates where work is repeated

## Change Policy

The repository should evolve slowly.

- add fields only when they are repeatedly useful
- avoid duplicate documents with overlapping roles
- prefer revising templates over creating parallel formats
- keep manual operation possible at every stage

The result is a foundation that can support years of review, research, and decision logging without becoming brittle.

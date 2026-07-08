# Dashboard

This file now routes current portfolio review to the dedicated portfolio dashboard.

## Primary Entry Point

- `portfolio/Portfolio_Dashboard.md`

This is the single entry point for current portfolio review as of `2026-07-08`.

## Supporting Documents

- `account/Current.md`: current position ledger and cash state
- `decisions/Decision_Log.md`: decision history and execution trail
- `strategy/Asset_Allocation.md`: target allocation, current allocation, and gap analysis
- `watchlist/Watchlist.md`: core holdings, candidates, and institution-tracker linkage
- `institution-tracker/README.md`: supporting evidence system for coverage and allocation

## Update Rule

- Put current-state portfolio review in `portfolio/Portfolio_Dashboard.md`.
- Preserve decision history in `decisions/Decision_Log.md` rather than overwriting dashboard context.
- Treat this file as the repo-level gateway, not the primary numeric dashboard.

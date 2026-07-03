# Dashboard

This file is the live operating dashboard for Rachel Capital.

It should always reflect the current real state. It is not a reusable template.

## Dashboard Status

| Field | Value |
| --- | --- |
| Last Updated | `2026-07-03` |
| Updated By | `Codex` |
| Source Documents | `account/Current.md` (live baseline incomplete), `thesis/`, current repository operating records |
| Next Weekly Review | `2026-07-10` |
| Next Monthly Review | `2026-08-01` |

## Where We Are

| Metric | Current | Notes |
| --- | --- | --- |
| Total Assets | `Not yet recorded in repository` | No live asset baseline has been entered in `account/Current.md`. |
| Cash | `Not yet recorded in repository` | Cash level cannot be stated until the live account baseline is entered. |
| Equity Exposure | `Not yet recorded in repository` | Exposure cannot be calculated from the current repository state. |
| Current Stage | `Operating system ready; portfolio intake pending` | Repository structure is live, but account state is still missing. |
| Market Regime | `No active market view recorded` | No weekly, monthly, or committee record has documented a live view yet. |

## What Changed

| Item | Change | Why It Matters |
| --- | --- | --- |
| Weekly Decision | `No weekly decision record exists yet.` | Decision quality cannot be reviewed until the first live meeting record is created. |
| Portfolio Change | `No live portfolio update has been documented yet.` | Assets, cash, and exposure remain unknown inside the repository. |
| Thesis Change | `Five thesis files exist, but none contains live evidence.` | Ownership, confidence, and sell conditions are not yet auditable. |

## What Deserves Attention

| Item | Trigger | Owner | Deadline |
| --- | --- | --- | --- |
| `Enter live account baseline` | `Dashboard cannot show assets, cash, or exposure until account data exists.` | `Rachel` | `2026-07-10` |
| `Confirm owned assets vs. research-only names` | `Thesis files exist, but the repository does not yet identify actual holdings.` | `Rachel` | `2026-07-10` |

## Core Holdings

| Holding | Role | Thesis Status | Next Action | Notes |
| --- | --- | --- | --- | --- |
| `No confirmed core holding recorded` | `Unconfirmed` | `No live thesis status` | `Confirm current holdings` | `Do not infer ownership from existing thesis filenames.` |

## What Happens Next

| Action | Reason | Destination |
| --- | --- | --- |
| `Populate account baseline with actual assets, cash, and weights` | `Live dashboard cannot become numeric until its source account record is real.` | `account/Current.md` |
| `Create the first weekly committee record` | `A dated operating cadence is required before the dashboard can report decisions and regime views.` | `weekly/2026/` |
| `Populate thesis files only for confirmed holdings` | `The repository needs a clear boundary between owned assets and research coverage.` | `thesis/` |

## Notes

- This page should answer four questions in one minute: where are we, what changed, what deserves attention, and what happens next.
- Update this page after `account/Current.md`, the latest weekly review, and any material decision change.
- If an item appears in `What Deserves Attention`, the related thesis, decision log, or review document should also be updated.
- Reusable structure belongs in `templates/Dashboard_Template.md`, not here.
- If live portfolio data is missing, state that explicitly rather than inventing placeholder numbers.

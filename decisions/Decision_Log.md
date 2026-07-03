# Decision Log

## Log Index

| Decision ID | Date | Decision Type | Subject | Success Criteria | Review Date | Final Result |
| --- | --- | --- | --- | --- | --- | --- |
| `20260703-01` | `2026-07-03` | `Process` | `Establish first live portfolio baseline` | `Dashboard, account, and review documents use one portfolio baseline.` | `2026-08-01` | `Open` |
| `20260703-02` | `2026-07-03` | `Risk` | `Maintain ¥90,000 cash as a strategic reserve` | `Cash remains deliberate and is not deployed without a written decision.` | `2026-08-01` | `Open` |
| `20260703-03` | `2026-07-03` | `Risk` | `Keep Li Auto under review and prohibit adds` | `No averaging down before the thesis improves or an exit path is chosen.` | `2026-07-10` | `Open` |

## Live Decision Entries

### Decision ID

`20260703-01`

### Date

`2026-07-03`

### Decision Type

`Process`

### Subject

`Establish first live portfolio baseline`

### Reason

- Rachel Capital moved from template documents to live operating records.
- Future decisions cannot be reviewed unless the repository starts from one explicit asset baseline.
- Dashboard, account, thesis, and review documents must reference the same portfolio state.

### Expected Outcome

- `Dashboard.md` and `account/Current.md` become the live homepage and live source of account truth.
- Weekly and monthly reviews can evaluate changes against a dated starting point.
- Future trading decisions can be judged against one auditable baseline.

### Success Criteria

- Total assets, stock assets, cash, and live holdings are recorded once and referenced consistently.
- Portfolio roles are explicit for all confirmed holdings.
- No conflicting live baseline exists elsewhere in the repository.

### Review Date

`2026-08-01`

### Final Result

- `Open`

### Lessons Learned

- A live investment system requires a recorded baseline before it requires new trades.
- Documentation lag is itself a portfolio risk because it weakens decision review quality.

### Review Notes

| Review Date | Outcome | What Was Correct | What Was Wrong | Next Adjustment |
| --- | --- | --- | --- | --- |
| `2026-07-03` | `Open` | `The first live baseline is now explicit.` | `Thesis and watchlist files were still incomplete at baseline creation.` | `Complete Sprint 2.1 live documents before the next weekly review.` |

### Decision ID

`20260703-02`

### Date

`2026-07-03`

### Decision Type

`Risk`

### Subject

`Maintain ¥90,000 cash as a strategic reserve`

### Reason

- Cash is 21.5% of total assets and remains a valid position under the current operating rules.
- Portfolio quality is still being improved, especially because Li Auto remains under review.
- No current watchlist trigger justifies immediate deployment.

### Expected Outcome

- Cash preserves optionality while portfolio roles and thesis files are being tightened.
- Capital will not be committed simply to reduce idle cash.
- Future deployment decisions will require explicit triggers and written justification.

### Success Criteria

- Cash stays deliberate rather than drifting down through unplanned trades.
- Any deployment is preceded or followed immediately by a logged decision.
- The next monthly review can explain why cash changed or why it remained unchanged.

### Review Date

`2026-08-01`

### Final Result

- `Open`

### Lessons Learned

- Cash only helps if it is paired with a clear watchlist and deployment rules.
- Optionality is more valuable than forced activity when conviction is uneven.

### Review Notes

| Review Date | Outcome | What Was Correct | What Was Wrong | Next Adjustment |
| --- | --- | --- | --- | --- |
| `2026-07-03` | `Open` | `Cash is explicitly treated as a strategic reserve.` | `Deployment triggers were not yet written in the live watchlist.` | `Complete the watchlist so cash policy becomes actionable.` |

### Decision ID

`20260703-03`

### Date

`2026-07-03`

### Decision Type

`Risk`

### Subject

`Keep Li Auto under review and prohibit adds`

### Reason

- Li Auto has the largest accumulated loss in the portfolio at `-¥104,000`.
- The dashboard's current market map treats EV as the weakest live theme.
- A losing position must earn the right to remain through evidence, not through sunk-cost bias.

### Expected Outcome

- The portfolio avoids averaging down into a weak role without stronger evidence.
- The next weekly review will force a clearer keep / reduce / exit discussion.
- Capital allocation quality improves by separating review status from active conviction.

### Success Criteria

- No additional capital is allocated to Li Auto before the review status changes.
- The next weekly review records a clearer thesis update or an action path.
- Li Auto remains in the portfolio only if a fresh case can be written clearly.

### Review Date

`2026-07-10`

### Final Result

- `Open`

### Lessons Learned

- Large losing positions need dated review checkpoints.
- "Do not add" is a valid risk decision when conviction quality is below portfolio standards.

### Review Notes

| Review Date | Outcome | What Was Correct | What Was Wrong | Next Adjustment |
| --- | --- | --- | --- | --- |
| `2026-07-03` | `Open` | `Li Auto is now explicitly under review rather than passively held.` | `The full live thesis had not yet been written.` | `Use the next weekly review to decide whether the position still deserves capital.` |

## Decision Entry Template

### Decision ID

`YYYYMMDD-01`

### Date

`YYYY-MM-DD`

### Decision Type

`Buy / Add / Reduce / Exit / Risk / Process`

### Subject

`TBD`

### Reason

- `TBD`

### Expected Outcome

- `TBD`

### Success Criteria

- `TBD`

### Review Date

`YYYY-MM-DD`

### Final Result

- `TBD`

### Lessons Learned

- `TBD`

### Review Notes

| Review Date | Outcome | What Was Correct | What Was Wrong | Next Adjustment |
| --- | --- | --- | --- | --- |
| `YYYY-MM-DD` | `TBD` | `TBD` | `TBD` | `TBD` |

## Usage Rules

- Assign one decision ID per meaningful action.
- Record the decision before or immediately after execution.
- Define success criteria before the outcome is known.
- Update the final result and lessons learned when the review date arrives.

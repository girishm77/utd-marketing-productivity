# Commit summary

## Suggested commit title
Add focus labels to productivity dashboard

## Suggested commit body
- Added a sortable `Focus` column to the author productivity table.
- Consumer behavior now gets priority when JCR plus Psych flagship-5 is more than 25% of selected-range UTD plus Psych flagship-5 output.
- Otherwise, Focus falls back to the strategy, quantitative, and hybrid rules documented in the methodology/caveats section.
- Removed inline table notes from below the table; definitions now live in the methodology/caveats section and README.
- Added the destination-journal click hint and kept journal clicks opening author rankings by destination.

## Files included
- `index.html`
- `README.md`
- `COMMIT_SUMMARY.md`

## Verification
- Dashboard JavaScript compiles cleanly.
- No inline table-note markers or table-note strip remain under the productivity table.

# Commit summary

## Suggested commit title
Update dashboard table and correct Homburg affiliation

## Suggested commit body
- Removed the experimental `Focus` column from the author productivity table.
- Kept table definitions in the methodology/caveats section instead of below the table.
- Added the destination-journal click hint and kept journal clicks opening author rankings by destination.
- Corrected Christian Homburg's displayed university to University of Mannheim.

## Files included
- `index.html`
- `README.md`
- `COMMIT_SUMMARY.md`

## Verification
- Dashboard JavaScript compiles cleanly.
- The author table no longer includes a `Focus` column.
- Christian Homburg resolves to `["University of Mannheim"]` in the embedded dashboard data.

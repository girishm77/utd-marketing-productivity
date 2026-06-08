# Commit summary

## Suggested commit title
Update dashboard non-marketing table definitions

## Suggested commit body
- Reordered the author table metrics to `Total UTD`, `Marketing`, `Mgmt Sci`, `Non-mktg`, and `Non-mktg %`.
- Defined `Non-mktg` as all UTD journals except JM, JMR, JCR, Marketing Science, and Management Science.
- Calculated `Non-mktg %` from the updated `Non-mktg` count divided by `Total UTD`.
- Updated README and fallback dashboard copy so GitHub-facing files no longer show old cohort counts or the prior column description.

## Files included
- `index.html`
- `README.md`
- `COMMIT_SUMMARY.md`

## Verification
- Browser verification on a fresh localhost URL showed the expected column order.
- Sample first row rendered as `91 / 79 / 12 / 0 / 0%`, confirming `Mgmt Sci` and `Non-mktg` are separated.
- Checked the first 40 rendered rows for `Non-mktg % = Non-mktg / Total UTD`; no mismatches.

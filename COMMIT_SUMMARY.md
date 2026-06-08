# Commit summary

## Suggested commit title
Update dashboard data and author disambiguation

## Suggested commit body
- Removed the experimental `Focus` column from the author productivity table.
- Relabeled the author table columns from `Marketing` / `Non-mktg` to `MKTG-4` / `CrossDisc`, including the methodology definitions for those table fields.
- Added the destination-journal click hint and kept journal clicks opening author rankings by destination.
- Corrected Christian Homburg's displayed university to University of Mannheim.
- Split the `Xi Li` homonym so the marketing/HKU-path Xi Li keeps the Toronto, CityU Hong Kong, and University of Hong Kong papers, while accounting/finance namesakes are excluded from that dashboard author.
- Added a broader Chinese-name homonym pass for exact-name collisions including Jie Zhang, Ying Zhang, Yang Yang, Yang Li, Yang Wang, Li Xiao, Qinghai Wang, Xiao Liu, Cheng Zhang, Jing Xu, Tao Chen, Xiaolin Li, Yi Liu, and Song Lin.
- Appended affiliation brackets to remaining duplicate display names; the two dashboard Jing Wang identities now display with their universities.
- Fixed author-table display so bracketed university disambiguators render as `Name (University)` instead of being inverted by last-name formatting.
- Updated the embedded dashboard DATA snapshot to 2026-06-08.

## Files included
- `index.html`
- `COMMIT_SUMMARY.md`

## Verification
- `scripts/ja_update.py` completed with `done.` and reported `matched to cohort: 156 | authors with >=1 just-accepted: 145`.
- Xi Li now has 16 dashboard papers and displays University of Hong Kong.
- The generated dashboard DATA reports 2,551 cohort authors, 17,167 cohort papers, and zero duplicate display names.
- Static render-function checks confirm `Jing Wang (Singapore Management University)` and `Jing Wang (University of Iowa)` display in `Name (University)` format.
- Static table-label checks passed: author tables now show `MKTG-4`, `CrossDisc`, and `CrossDisc %`.

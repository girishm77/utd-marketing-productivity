# Marketing Authors' UTD Productivity, 1990–2025

An interactive dashboard of publication output for 2,553 marketing-home authors
(more than 20% of their full-career UTD papers in the marketing journals, with
at least two marketing-journal papers) across all 24 UTD-ranked business
journals, 1990–2025 (17,264 papers, de-duplicated to one per author per article).
Author name variants (e.g., "Pradeep Chintagunta" / "Pradeep K Chintagunta")
are consolidated.

**Live site:** https://girishm77.github.io/utd-marketing-productivity/

## What it shows

- Annual output (marketing vs. non-marketing) with distinct active authors
- Non-marketing share over time (2005 ranking onset marked)
- Field mix and top destination journals for non-marketing work
- A sortable, searchable ranking of the most productive authors, with
  `Total UTD`, `Marketing`, `Mgmt Sci`, `Non-mktg`, and `Non-mktg %` shown
  separately

All panels refilter to a year range you choose with the slider.

## Notes

- `index.html` is fully self-contained — Chart.js is inlined, so it works offline
  and needs no build step or external files.
- Source: UTD Top-100 Business School Research Rankings extract; marketing-home
  cohort defined as authors with more than 20% of their full-career papers in the
  marketing journals (JCR, JM, JMR, Marketing Science), plus at least two
  marketing-journal papers, with normalized author names and papers de-duplicated
  to one per author per article.
- In the author table, `Non-mktg` counts all other UTD journals except Journal of
  Marketing, Journal of Marketing Research, Journal of Consumer Research,
  Marketing Science, and Management Science. `Non-mktg %` is that count divided
  by `Total UTD`. Counts are descriptive — see the companion spillover analysis
  for causal caveats.

## Publishing (GitHub Pages)

1. Commit and push this repo to `github.com/girishm77/utd-marketing-productivity`.
2. In the repo: **Settings → Pages → Build from branch → `main` / root → Save**.
3. The site appears at https://girishm77.github.io/utd-marketing-productivity/.

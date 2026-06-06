# Marketing Authors' UTD Productivity, 1990–2025

An interactive dashboard of publication output for 5,199 marketing-home authors
(full-career home field = Marketing) across all 24 UTD-ranked business journals,
1990–2025 (18,821 papers, de-duplicated to one per author per article).

**Live site:** _add your GitHub Pages URL here after publishing_

## What it shows

- Annual output (marketing vs. non-marketing) with distinct active authors
- Non-marketing share over time (2005 ranking onset marked)
- Field mix and top destination journals for non-marketing work
- A sortable, searchable ranking of the most productive authors

All panels refilter to a year range you choose with the slider.

## Notes

- `index.html` is fully self-contained — Chart.js is inlined, so it works offline
  and needs no build step or external files.
- Source: UTD Top-100 Business School Research Rankings extract; marketing-home
  cohort defined by full-career home field (marketing is the author's single
  largest field across all years), with normalized author names and papers
  de-duplicated to one per author per article. Counts are descriptive — see the
  companion spillover analysis for causal caveats.

## Publishing (GitHub Pages)

1. Create a new public repo on GitHub.
2. Push this folder to it.
3. In the repo: **Settings → Pages → Build from branch → `main` / root → Save**.
4. The site appears at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

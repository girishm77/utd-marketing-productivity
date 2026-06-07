# Marketing Authors' UTD Productivity, 1990–2025

An interactive dashboard of publication output for 5,368 marketing-home authors
(more than 20% of their full-career UTD papers in the marketing journals) across
all 24 UTD-ranked business journals, 1990–2025 (20,785 papers, de-duplicated to
one per author per article).
Author name variants (e.g., "Pradeep Chintagunta" / "Pradeep K Chintagunta")
are consolidated.

**Live site:** https://girishm77.github.io/utd-marketing-productivity/

## What it shows

- Annual output (marketing vs. non-marketing) with distinct active authors
- Non-marketing share over time (2005 ranking onset marked)
- Field mix and top destination journals for non-marketing work
- A sortable, searchable ranking of the most productive authors
- A `Focus` column classifying authors' selected-range UTD journal mix

All panels refilter to a year range you choose with the slider.

## Notes

- `index.html` is fully self-contained — Chart.js is inlined, so it works offline
  and needs no build step or external files.
- Source: UTD Top-100 Business School Research Rankings extract; marketing-home
  cohort defined as authors with more than 20% of their full-career papers in the
  marketing journals (JCR, JM, JMR, Marketing Science) — a superset of the earlier
  plurality home-field rule — with normalized author names and papers de-duplicated
  to one per author per article. Counts are descriptive — see the companion
  spillover analysis for causal caveats.
- `Focus` is computed from selected-range UTD papers only: Consumer behavior if
  JCR is more than 50%; Marketing strategy if JM/JMR is more than 50%; and
  Quantitative if Marketing Science/Management Science/JMR is more than 50%.
  Split labels require each side to be at least 20% of output and the combined
  journal set to exceed 50%: `CB/strat` = JCR with JM/JMR, `CB/quant` = JCR with
  Marketing Science/Management Science, and `strat/quant` = JM/JMR with Marketing
  Science/Management Science/JMR.

## Publishing (GitHub Pages)

1. Create a new public repo on GitHub.
2. Push this folder to it.
3. In the repo: **Settings → Pages → Build from branch → `main` / root → Save**.
4. The site appears at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

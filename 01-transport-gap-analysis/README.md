# 01 — Qatar Transport Research Gap Analysis

*Flagship study. Independent applied research on what has and has not been studied in Qatar's transportation, infrastructure, and urban-mobility research base, cross-referenced against current government strategic priorities and global academic literature.*

## What's in this folder

| File | Content |
|---|---|
| [`GAP_ANALYSIS.md`](GAP_ANALYSIS.md) | Main analytical report. Five sections: saturated topics, recent government-funded themes, identified gaps, recommended project direction, differentiation analysis vs the three closest existing papers. |
| [`methodology.md`](methodology.md) | Study-specific methodology, data-collection protocol, scoring rubric, and limitations. |
| [`data/qatar_papers_inventory.json`](data/qatar_papers_inventory.json) | 30 papers from 7 Qatar institutions (Qatar University, HBKU, Texas A&M Qatar, Carnegie Mellon Qatar, Weill Cornell Medicine Qatar, Georgetown Qatar, University of Doha for Science and Technology), with title, authors, year, methodology, data source, key finding, funding source, URL. |
| [`data/qatar_funded_projects.json`](data/qatar_funded_projects.json) | NPRP and QRDI funded transport projects identified through grant acknowledgements, plus the 2024-2025 funding landscape (QLTC, NRP, PTP). |
| [`data/qatar_gov_priorities.json`](data/qatar_gov_priorities.json) | Nine government strategy documents (NDS3 2024-2030, MoT Strategy 2025-2030, TMPQ 2050, QFMP, TASMU, QPTMP, QNV2030, Autonomous Vehicle Strategy, Ashghal Expressway Programme), with stated priorities, KPIs, funding allocations, and acknowledged gaps. |
| [`data/global_qatar_papers.json`](data/global_qatar_papers.json) | 15 international/global academic papers on Qatar transport (ScienceDirect, MDPI, Tandfonline, USDOT, IEEE), with abstract snippets and methodology. |

## Headline finding

The closest extant published work on Doha's road network — [Spatiotemporal analysis of road network evolution and urban growth in Doha](https://www.sciencedirect.com/science/article/pii/S230718772600026X), Jan 2026 — is forward-looking and descriptive. **No published Qatar research is backward-looking and evaluative.** The gap is independently flagged by the IMF (as a GCC-wide PIM weakness) and by the Qatar Ministry of Transport itself (which launched the QPTMP public survey in June 2025 to begin building the congestion baseline).

## Recommended project direction

> *"An ex-post evaluation of Qatar's road infrastructure investment (2010-2025): supply-demand mismatch, induced-demand testing, and 2030 KPI plausibility from open-data sources."*

Combines five publicly available data streams (OSM road history, Qatar Open Data vehicle registrations, Comtrade vehicle imports, Doha Metro published ridership, TomTom Traffic Index history) into a panel suitable for difference-in-differences and synthetic-control identification of investment-outcome causal effects.

## How to use this folder

- **Government agencies** — section 2 of `GAP_ANALYSIS.md` maps stated government priorities to the existing research base; useful for calibrating funding-call themes.
- **Research institutes and universities** — section 3 lists ten scored research questions ready for proposal development; section 5 differentiates the recommended project from three closest existing efforts.
- **Consultancies** — `data/qatar_gov_priorities.json` is a structured KPI inventory cross-referenced to source documents.
- **Infrastructure / transport organizations** — section 4 outlines the recommended ex-post evaluation methodology applicable to investment-outcome questions.

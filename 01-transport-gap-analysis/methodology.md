# Methodology — Transport Research Gap Analysis

## Approach

Four-phase structured pipeline, executed over a single compressed work session, with all source material verified at the URL level:

### Phase 1 — Qatar institutional harvest

For each of the seven major research-producing institutions in Qatar (Qatar University, Hamad Bin Khalifa University, Texas A&M Qatar, Carnegie Mellon Qatar, Weill Cornell Medicine Qatar, Georgetown Qatar, University of Doha for Science and Technology), collected publications related to transportation, traffic, urban mobility, infrastructure, roads, congestion, or vehicles. Sources: QSpace repository, institutional research pages, Google Scholar / ResearchGate surfaced metadata.

For each paper indexed: title, authors, institution, year, abstract snippet (when accessible), methodology, data source, time period studied, key finding, funding source (if cited), URL.

### Phase 2 — Funded-project inventory

Collected QRDI and QNRF (NPRP) funded transport projects through grant-acknowledgement traces in publication metadata, official QRDI press releases, and news reporting on award announcements. Annotated with the broader 2024-2025 funding landscape (QLTC, NRP, PTP, AIQAT, Agentic AI Call) to contextualize current government priorities.

### Phase 3 — Government priority extraction

Direct fetch of official strategy documents and ministerial press releases:
- Qatar National Vision 2030
- Third National Development Strategy 2024-2030
- Ministry of Transport Strategy 2025-2030 ("Reaching Beyond Horizons")
- Transportation Master Plan for Qatar 2050 (TMPQ 2050)
- Qatar Freight Master Plan (QFMP)
- TASMU Smart Qatar transportation pillar
- Qatar Public Transport Master Plan (QPTMP) — in progress
- Qatar Autonomous Vehicle Strategy 2025-2030
- Ashghal Expressway Programme

For each: stated priorities, numerical KPIs, acknowledged challenges, total funding allocation, time horizons, key direct quotes.

### Phase 4 — Global literature search

Searched ScienceDirect, MDPI, IEEE Xplore, Taylor & Francis, ResearchGate, PubMed Central, and USDOT databases for international academic work on Qatar transport. Filtered to 2018-2026 publication date.

## Scoring rubric for identified gaps

Each gap evaluated on four dimensions, 1-5 each:

| Dimension | What it measures |
|---|---|
| Novelty | How unique vs existing Qatar literature |
| Feasibility | Can be done with publicly available data |
| Government interest | Matches stated priorities in NDS3 / MoT Strategy / TMPQ / TASMU |
| Methodological strength | Is there a defensible, established methodology |

## Limitations

1. **Coverage depth.** Surface-web search (Google, institutional pages, ResearchGate, ScienceDirect) typically returns ~10-20 results per query. Deeper indexing (Scopus, Web of Science) was not accessed. Arabic-only publications, restricted conference proceedings, and unpublished ministry technical reports are out of scope.
2. **Funded-project inventory.** QGrants and QRDI Connect portal require authenticated access; many NPRP cycles 1-13 transport projects are likely missing.
3. **Abstract accuracy.** Some abstract snippets paraphrase search-engine summaries rather than direct full-text reads. These are starting points for direct retrieval, not authoritative quotes.
4. **Gap claims.** "Not located" means "did not surface through this search pass." Before formal proposal submission against any identified gap, a paid Scopus/WoS query and Google Scholar deep-dive should re-verify each "absent" claim.

## Reproducibility

Every claim in `GAP_ANALYSIS.md` is traceable to a source URL either in the report's "Sources" section or in the individual JSON dataset entries. The four JSON files are the source-of-truth structured data; the Markdown report is the synthesis.

To extend this analysis:
- Add a new paper to `data/qatar_papers_inventory.json` using the existing schema
- Add a new funded project to `data/qatar_funded_projects.json` with grant number where known
- Add a new strategy document to `data/qatar_gov_priorities.json` with the same KPI-extraction structure

The gap-scoring rubric is intentionally simple and human-evaluable; no machine-learning models or proprietary tooling are required.

# Qatar Transportation/Infrastructure Research — Gap Analysis

*Compiled 2026-05-12. Sources: 4 JSON inventories in this directory + cited URLs throughout. All paper claims trace to a source URL; where an abstract was inaccessible the entry is flagged.*

---

## 1. What HAS Been Studied (Saturated Topics)

The Qatar literature, while modest in size, clusters tightly around a handful of themes. The following are saturated — new research framed within them faces a high bar for differentiation.

| # | Topic | ~Paper count | Dominant authors / institutions | Representative source |
|---|-------|------|---------------------------------|-------------|
| 1 | Road traffic crashes / fatalities / safety culture | 8+ | Alhajyaseen (QTTSC, QU); Bener (WCM-Q); Timmermans | [Crashes 2019](https://www.tandfonline.com/doi/full/10.1080/17457300.2019.1620289), [WCM-Q speed cameras](https://qatar-weill.cornell.edu/news-archive/Reports/2011/raviRTA.html) |
| 2 | Doha Metro ridership / satisfaction / mode choice | 6+ | various, QU + MDPI venues | [Mode choice](https://www.sciencedirect.com/science/article/pii/S2590198223000994), [Satisfaction](https://www.sciencedirect.com/science/article/pii/S0001691825000939) |
| 3 | Driver behaviour (taxi vs general, autistic drivers, mobile use) | 5+ | QTTSC team | [Professional vs non-pro](https://qspace.qu.edu.qa/handle/10576/73) |
| 4 | Roundabout safety / signalized intersection operation | 4+ | QU CivEng | [Signalized roundabouts](https://qspace.qu.edu.qa/bitstream/handle/10576/51115/Safety%20and%20Operational%20Performance%20of%20Signalized%20Roundabouts%20A%20Case%20Study%20in%20Doha.pdf) |
| 5 | Transit-oriented development (TOD) around Doha Metro stations | 5+ | QU Arch + Urban Planning; MDPI Urban Sci | [Souq Waqif TOD](https://www.mdpi.com/2413-8851/8/4/182), [Transit villages](https://ascelibrary.org/doi/10.1061/JUPDDM.UPENG-3949) |
| 6 | Air pollution emissions from transport (vehicle inventory based) | 4+ | HBKU ELMI (Al-Thani, Koç, Isaifan) | [LEAP Qatar](https://www.mdpi.com/2073-4433/14/8/1286), [HBKU PM diesel](https://www.tandfonline.com/doi/full/10.1080/10962247.2019.1704939) |
| 7 | Urban form / sprawl narrative on Doha | 5+ | mixed | [MDPI 2019](https://www.mdpi.com/2071-1050/11/3/786), [LU/LC change](https://www.tandfonline.com/doi/full/10.1080/19475683.2014.992369) |
| 8 | E-scooter / micromobility public perception | 3+ (rising) | QTTSC | [E-scooter Qatar](https://qspace.qu.edu.qa/handle/10576/73) |

**Inference:** Qatar's transport research portfolio is heavily microscale (crashes, roundabouts, surveys at metro stations, vehicle-level emissions). Macro-evaluative work — testing whether investments delivered their goals — is essentially absent.

---

## 2. What HAS Been Funded Recently (Government Priority Signals)

The 2024–2025 funding landscape tells a clearer story than the publication record.

| Year | Mechanism | Theme | Awardees | What it signals |
|------|-----------|-------|----------|-----------------|
| 2025-07 | QRDI Rapid Research Calls (30 awards across 6 calls) | **QLTC** — Qatar Logistics & Transportation Call | HBKU, QU, UDST; partner Qatar Airways | Aviation/SAF emphasis. Urban roads/congestion NOT the primary frame. |
| 2024-04 | QRDI NRP | Economic Sustainability Call | TBA | Logistics/transport indirectly relevant |
| 2024-02 | MoT | Qatar Freight Master Plan finalized | n/a | Freight separated from passenger transport; needs separate evaluation |
| 2025 | MoT | Transport Strategy 2025-2030 (QAR 1.2bn, 42 initiatives, 125 projects) | n/a | Sharp KPIs but no published baseline study |
| 2025-06 | MoT | Qatar Public Transport Master Plan (QPTMP) survey campaign | n/a (citizens) | **Government openly acknowledges it lacks the congestion baseline.** |
| 2022 | QU Student Grant | TOD framework for Souq Waqif | QU student team | Continued TOD interest |
| 2021 | NPRP | Smart transportation modeling/control ($510k, 3yr) | unknown PI | ICT-side, not policy evaluation |
| 2010-2014 | NPRP cycles 3, 5, 9 | V2X (CopITS), transport network simulation, crash analysis | QMIC, QTTSC | Historical baseline of NPRP transport priorities |

**Inference:** Three distinct funding lanes are open:
- **QLTC / NRP transport calls** — favour applied, scalable, partner-anchored work (Qatar Airways SAF was the 2025 anchor; future calls likely to ride a similar template).
- **NPRP successor / Academic Research Program** — accepts more analytical/methodological work.
- **MoT direct contracting** — the active QPTMP and Freight Master Plan studies. A research project that complements (rather than competes with) QPTMP could position for direct ministry uptake.

---

## 3. What HAS NOT Been Studied (Identified Gaps)

Each gap below is paired with: (a) why it is absent, (b) which government priority it aligns with, (c) which public datasets enable it, and (d) a scoring rubric (1–5).

### Gap 3.1 — Ex-post evaluation of road infrastructure investment outcomes

**Question:** Did Qatar's ~$100B road and infrastructure spend (2010–2024) deliver the congestion-reduction and modal-shift outcomes its strategies claimed?

- **Absent because:** No Qatar paper located. The closest is an "Assessment Framework for Strategic Transportation Projects" ([Academia.edu](https://www.academia.edu/85510513/)) — but it is **ex-ante** (project appraisal), not ex-post (outcome verification). The IMF directly notes "lack of ex-post evaluations" as a GCC-wide PIM weakness ([IMF PFM 2023](https://blog-pfm.imf.org/en/pfmblog/2023/04/improving-infrastructure-investment-in-the-gcc)).
- **Aligns with:** NDS3 2024-2030, MoT Strategy 2025-2030 (which itself acknowledges resilience/sustainability KPIs without a baseline), QPTMP (active survey).
- **Data feasibility:** Ashghal road project records, MoT public spending series, TomTom Traffic Index historical Qatar series, OSM history layer for road growth, Qatar Open Data registered-vehicles series, PSA crash and traffic flow records.
- **Scores:** Novelty **5/5**, Feasibility **4/5**, Government interest **5/5**, Methodological strength **4/5** (well-established CBA + DiD design exists; difficulty is data assembly).

### Gap 3.2 — Supply-demand mismatch between road network growth and vehicle fleet growth

**Question:** Has road capacity expansion (km lane-equivalent) kept pace with the registered-vehicle fleet, and where are the chronic mismatches geographically?

- **Absent because:** Spatiotemporal Doha paper (Jan 2026) describes road network evolution and recommends growth direction, but does NOT quantify supply vs. registered-vehicle demand. No located paper joins Comtrade/PSA vehicle import data with OSM road growth and a congestion proxy.
- **Aligns with:** QPTMP, MoT Strategy 2025-2030 (smart mobility innovation), TASMU Real-time Crowd Analytics use case.
- **Data feasibility:** OSM history (open), Qatar Open Data vehicle-registration series (open), Comtrade HS 8703 imports (open), TomTom Traffic Index city-level history (open), Worldpop / GHSL population grids (open).
- **Scores:** Novelty **5/5**, Feasibility **5/5**, Government interest **4/5**, Methodological strength **4/5**.

### Gap 3.3 — Induced demand testing in a high-income car-dependent GCC city

**Question:** Does the Duranton-Turner "fundamental law of road congestion" (capacity adds beget proportional traffic) hold in Doha, given its unique combination of fuel subsidy, low population density, and rapid fleet growth?

- **Absent because:** No GCC-specific test located. Global evidence dominated by US/Europe panel data. Qatar's combination of demand drivers is regionally distinct.
- **Aligns with:** MoT 2025-2030 "sustainability" pillar, NDS3 GHG target.
- **Data feasibility:** Same as 3.2 plus traffic count panels from Ashghal/MoT. Synthetic control or DiD methods well-developed.
- **Scores:** Novelty **5/5**, Feasibility **3/5** (needs project-level traffic counts), Government interest **3/5** (politically uncomfortable framing if positive finding), Methodological strength **5/5**.

### Gap 3.4 — Combined longitudinal modal-share evolution and Doha Metro performance vs. 2019 promises

**Question:** Did Doha Metro deliver against its projected 190,000-car/day displacement and 19.42 kt CO2 reduction ([USDOT projection](https://www.itskrs.its.dot.gov/2023-b01774))? Five-year ex-post.

- **Absent because:** All located mode-choice papers are survey-based or pre-launch. None compare projected vs. realized.
- **Aligns with:** NDS3 sustainability, MoT 2025-2030 public transport efficiency pillar.
- **Data feasibility:** Doha Metro published ridership (200M cumulative by Dec 2024), Qatar Open Data fleet, TomTom Traffic Index pre/post 2019.
- **Scores:** Novelty **4/5**, Feasibility **4/5**, Government interest **5/5**, Methodological strength **3/5** (counterfactual construction is hard).

### Gap 3.5 — Government KPI feasibility analysis

**Question:** Is the 35% EV fleet by 2030 / 100% e-bus by 2030 / 25% GHG-reduction target plausible given current vehicle import trajectories (Comtrade HS 8703.80 BEV imports), charger rollout, and household preferences?

- **Absent because:** No Qatar paper located that triangulates Comtrade BEV imports + registered-vehicle data + KPI plausibility.
- **Aligns with:** Every transport strategy document (MoT 2025-2030, QNECCS, NDS3).
- **Data feasibility:** Fully open (Comtrade + Qatar Open Data + IEA EV outlook).
- **Scores:** Novelty **4/5**, Feasibility **5/5**, Government interest **5/5**, Methodological strength **3/5**.

### Gap 3.6 — Three-peak daily traffic regime and its operational implications

**Question:** What is the welfare cost and operational implication of Doha's unique three-peak pattern (06:30, 12:30, 17:15)? Implications for signal timing, freight routing, transit headways?

- **Absent because:** Single QU paper documents the existence of the pattern; no follow-up exploiting it.
- **Aligns with:** QFMP (freight routing), TASMU "intelligent road signage" tendered use case.
- **Data feasibility:** Signal-detector data available via QU/MoT partnerships; needs collaboration.
- **Scores:** Novelty **4/5**, Feasibility **3/5**, Government interest **4/5**, Methodological strength **3/5**.

### Gap 3.7 — Climate-constrained micro-mobility viability windows

**Question:** Given Doha's extreme summer heat, what fraction of daylight hours per year are micro-mobility (e-scooter, e-bike) usable under WHO/ISO heat-stress thresholds, and how does that affect investment ROI?

- **Absent because:** E-scooter perception papers exist but none integrate climate windows or heat-stress modeling.
- **Aligns with:** TASMU (eBike/eCar sharing tendered), MoT 2030 sustainability, QNECCS climate adaptation.
- **Data feasibility:** Open weather records (NOAA/QMD), ISO 7243 WBGT, ECMWF reanalysis.
- **Scores:** Novelty **5/5**, Feasibility **4/5**, Government interest **3/5**, Methodological strength **4/5**.

### Gap 3.8 — Freight movement impact on passenger traffic (QFMP empirical baseline)

**Question:** What share of passenger-route congestion is attributable to freight movement at peak hours, and how does the proposed freight route network in QFMP shift that?

- **Absent because:** QFMP launched Feb 2024 with stated intent to reduce truck-passenger conflict, but no academic baseline study located.
- **Aligns with:** QFMP, NDS3 logistics cluster.
- **Data feasibility:** Requires partnership with MoT freight unit; partial use of Open Data permitted vehicle classifications.
- **Scores:** Novelty **4/5**, Feasibility **2/5** (data partnership needed), Government interest **5/5**, Methodological strength **3/5**.

### Gap 3.9 — Smart-mobility use case impact quantification (TASMU "not initiated" cases)

**Question:** For each of the 8+ TASMU transportation use cases still marked "not initiated" (V2V, car-pooling, smart taxi, accessible transportation, etc.), what is the expected benefit and what blocks implementation?

- **Absent because:** No published evaluation of TASMU portfolio progress located.
- **Aligns with:** TASMU directly, MoT 2025-2030.
- **Data feasibility:** Documentary + stakeholder interviews + benchmarking from other cities.
- **Scores:** Novelty **3/5**, Feasibility **4/5**, Government interest **4/5**, Methodological strength **3/5**.

### Gap 3.10 — UHI–traffic feedback loop quantification

**Question:** Single QU paper documents that traffic contributes to urban heat island. What is the quantitative feedback loop (UHI → AC load → grid emissions → climate → traffic survival of micromobility)?

- **Absent because:** Single descriptive paper; no causal chain quantification.
- **Aligns with:** Environmental Development pillar of QNV2030, QNECCS.
- **Data feasibility:** Open Landsat thermal + AC consumption data harder to obtain.
- **Scores:** Novelty **5/5**, Feasibility **2/5**, Government interest **3/5**, Methodological strength **3/5**.

---

## 4. Recommended Project Direction

### The pick: combined Gap 3.1 + 3.2 + 3.5

**Proposed title:** *"An ex-post evaluation of Qatar's road infrastructure investment (2010–2025): supply-demand mismatch, induced-demand testing, and 2030 KPI plausibility from open-data sources."*

**Why this is the strongest single pick:**

| Dimension | Combined score | Reasoning |
|-----------|----------------|-----------|
| Novelty | 5/5 | No Qatar paper combines OSM road history + Comtrade vehicle imports + TomTom congestion outcomes + government KPI plausibility. The IMF explicitly flags ex-post evaluation as a regional gap. |
| Feasibility | 5/5 | 100% public data (OSM history, Comtrade, Qatar Open Data, TomTom city series, World Bank, ECMWF). No partnership dependency. |
| Government interest | 5/5 | Plugs directly into the live QPTMP work (government openly asking the public for input on the same baseline question). Cross-cuts MoT 2025-2030, NDS3, and QNECCS. |
| Methodological strength | 4/5 | Established methods (DiD, synthetic control, panel regression, induced-demand elasticity following Duranton-Turner). Defensible framing as a methods-import study rather than a from-scratch theoretical claim. |

**Concrete framing for funding application (QRDI NRP or successor of QLTC):**

> "Qatar has invested an estimated USD 100 billion in road and transportation infrastructure since 2010, alongside the country's first heavy-rail metro. This project assembles a longitudinal panel — combining OpenStreetMap road network history, Qatar Open Data vehicle-registration series, Comtrade vehicle imports, Doha Metro published ridership, and TomTom Traffic Index — to deliver the first ex-post evaluation of these investments. We test the Duranton-Turner fundamental law of road congestion in a high-income GCC context and assess the plausibility of MoT 2030 KPIs (35% EV fleet, 100% e-bus, 25% GHG reduction) against current import trajectories. Outputs feed directly into the in-progress Qatar Public Transport Master Plan."

This frames the project not as adversarial to road investment, but as a **methodology contribution** that fills a gap the IMF and Qatar government itself have publicly noted.

---

## 5. Differentiation from Closest Competitors

### Competitor #1 — Spatiotemporal analysis of road network evolution and urban growth in rapidly developing cities: The case of Doha metropolitan (ScienceDirect, Jan 2026, [link](https://www.sciencedirect.com/science/article/pii/S230718772600026X))

| What they did | What our project would do differently | Why ours adds value |
|---|---|---|
| Used GIS + dot density maps + isochrone Orthogonal Rake System + GeoHash density mapping | Use a longitudinal panel that joins OSM road km, registered vehicles, Comtrade imports, and TomTom congestion | Theirs is descriptive ("where to grow next"); ours is evaluative ("did past growth work?") |
| Forward-looking land-use proposal: ideal growth direction is west and north | Backward-looking ex-post: lane-km added vs. fleet added vs. delay outcome | Theirs feeds planners; ours feeds budget officers and the QPTMP analytic baseline |
| Inputs: OSM road network + planning policy documents + population trends | Inputs: same OSM + Comtrade + Qatar Open Data + TomTom + Ashghal project budget records | We add the demand-side and outcome-side data they don't touch |
| No causal identification | DiD around Metro launch (May 2019), synthetic-control of expressway program completions | Different intellectual product (causal claim, not a planning recommendation) |

### Competitor #2 — Analysis of mode choice effects from the introduction of Doha Metro using ML and statistical analysis (ScienceDirect 2023, [link](https://www.sciencedirect.com/science/article/pii/S2590198223000994))

| What they did | Our differentiation |
|---|---|
| Used RP/SP survey + binary logit + multinomial logit + XGBoost on individual-level survey | Use aggregate OD-pair-level realized travel times and modal-flow proxies over 2017–2025 |
| Survey snapshot of stated/revealed preferences | Multi-year panel of realized outcomes |
| Generalizable to "who's likely to switch?" | Specific to "how much did switching actually happen, and at what infrastructure cost-per-shifted-trip?" |

### Competitor #3 — Evaluation of sustainable urban mobility using comparative LCA: A case study of Qatar (ScienceDirect 2019, [link](https://www.sciencedirect.com/science/article/pii/S259019821930003X))

| What they did | Our differentiation |
|---|---|
| Comparative LCA of cars vs. metro per-trip | We add system-level realized modal mix and capacity utilization |
| Per-unit metric: 78pp climate impact reduction per swapped trip | System-level: how many trips were actually swapped, net of induced demand on roads |
| Static technology comparison | Dynamic policy outcome evaluation |

---

## Sources

Primary inventories saved as JSON in this directory:
- [data/research/qatar_papers_inventory.json](qatar_papers_inventory.json) — 30 Qatar-institution papers
- [data/research/qatar_funded_projects.json](qatar_funded_projects.json) — 9 NPRP/QRDI funded projects + landscape
- [data/research/qatar_gov_priorities.json](qatar_gov_priorities.json) — 9 government documents with explicit KPIs
- [data/research/global_qatar_papers.json](global_qatar_papers.json) — 15 international/global papers on Qatar transport

Key external references cited above:
- [QRDI Council 30 awards announcement (Jul 2025)](https://thepeninsulaqatar.com/article/22/07/2025/qrdi-council-announces-30-awards-for-six-rapid-research-calls)
- [Ministry of Transport Strategy 2025-2030](https://mot.gov.qa/en/news/prime-minister-launches-ministry-transport-strategy-2025-2030)
- [TASMU Transportation pillar with KPIs](https://tasmu.gov.qa/transportation)
- [TMPQ 2050](https://www.mot.gov.qa/en/land-transport/transportation-master-plan-for-qatar-2050)
- [Qatar Freight Master Plan finalized 2024](https://www.mot.gov.qa/en/news/ministry-finalizes-qatar-freight-master-plan)
- [QPTMP active public survey 2025](https://thepeninsulaqatar.com/article/10/06/2025/mot-public-survey-to-shape-modern-public-transport-continues)
- [IMF: GCC infrastructure investment gaps](https://blog-pfm.imf.org/en/pfmblog/2023/04/improving-infrastructure-investment-in-the-gcc)
- [Competitor — Spatiotemporal Doha (ScienceDirect 2026)](https://www.sciencedirect.com/science/article/pii/S230718772600026X)
- [Qatar Open Data — vehicle registration](https://www.data.gov.qa/explore/dataset/registered-vehicles-and-motor-cycles-by-type-of-license/)
- [TomTom Traffic Index Doha](https://www.tomtom.com/traffic-index/city/doha)

## Caveats and limitations

1. **Coverage:** Google search surface ~10–20 results per query; deeper academic indexing (Scopus, Web of Science) was not directly accessible. Qatar-published papers in Arabic-only venues, restricted conference proceedings, and unpublished MoT/Ashghal technical reports are not visible to this analysis.
2. **Funded-project list:** QGrants and QRDI Connect both require authenticated access. NPRP grant numbers surface mostly through paper acknowledgements; many cycles 1–13 transport projects are likely missing from this inventory.
3. **Abstract accuracy:** Some abstract snippets are paraphrased from search-engine summaries rather than direct full-text reads. Treat as starting points for direct paper retrieval.
4. **Gap claims:** "Not located" means "did not surface through this search pass." Before formal proposal submission, a paid Scopus/WoS query and Google Scholar deep-dive should re-verify each "absent" claim — especially for Gaps 3.1, 3.2, 3.5.

# Independent search-gap audit — 16 November 2026

## Status and limits

This is a targeted, multi-pass discovery and protocol audit, not an exhaustive systematic search, independent eligibility review, or completed corpus-difference analysis. It compares the published v0.1 search specification and previously reviewed project summaries with independent web discovery using two search engines, primary publisher/author records and reference tracing. No WoS/Scopus session was executed. Original 3,825-record exports and native November 13 query logs were not located in the inspected local project paths. Consequently **no newly surfaced paper is certified absent from that corpus**. Known project seeds, supplementary candidates and contextual sources must be reconciled before any omission count is reported.

## Diagnosed gaps and corrective actions

| Gap | Evidence and consequence | Correction |
|---|---|---|
| Compensation vocabulary | Honeybee studies use precocious foraging, behavioral maturation/reversion and demographic manipulation, which the v0.1 C block does not explicitly cover. | Add both behavior spellings, reversion, maturation, demograph*, nurse/forager depletion; validate on Perry 2015 and older demographic studies. |
| Task-specific vocabulary | Undertaking, corpse/intruder removal, larval feeding, fanning, water collection, emigration and nest repair may omit generic compensation words. | Run task-specific supplementary queries and citation tracing without requiring the C response block. |
| Specialization versus activity | Toledo 2024 compares activity categories and efficiency; that is not automatically a multi-task specialization contrast. | Extract predictor definition and keep activity–efficiency separate from specialization–efficiency. |
| Individual versus colony outcome | Jongepier/Foitzik includes colony fitness endpoints; individual handling-time studies answer another question. | Search reproduction, growth, survival, fitness, brood output as supplementary outcome vocabulary; preserve levels in synthesis. |
| Task integration | Queueing and transfer delays may improve collective performance without improving individual specialist skill. | Add task integration, material transfer, queueing/queuing, sequential transport and ergonomic efficiency; distinguish integration from specialization. |
| Inactivity definitions | Immobility, unobserved focal tasks, roaming and task-specific unemployment differ. | Add nonforager/non-forager, quiescen*, rest*, idle*, unemployed and reserve terms in bounded queries; code definitions and visibility. |
| Temporal scale | Momentary inactivity, persistent individual inactivity, periodic bouts and fatigue replacement are not interchangeable. | Extract sampling interval, observation duration, diel timing and repeatability; do not pool raw percentages across windows. |
| Negative reserve evidence | Jandt 2012 supplies a defensive-reserve counterexample. Positive removal studies alone bias the rationale. | Include negative/failed responses in sentinel and citation sets; never require a positive compensation result. |
| Empirical versus model outcome | Hasegawa 2016 and Perry 2015 combine empirical observations with modeled colony consequences. | Code provenance at the outcome level, not only the paper level. Simulated persistence/collapse is not observed colony survival. |
| Taxonomic breadth | Termite replacement can be described as age-based spatial resilience; current seeds emphasize ants. | Add termite sentinels and genera (e.g. Reticulitermes, Coptotermes, Zootermopsis), plus stingless bees and social-wasp variants; test database indexing coverage. |
| Older terminology | Elitism, ergonomic efficiency, temporal polyethism and task partitioning predate modern specialization language. | Backward-search historical references and books; preserve alternate genus names and spelling variants. |
| Adjacent versus eligible evidence | Experience, morphology and learning studies can help interpret results without testing focal specialization/inactivity relationships. | Contextual ledger separate from eligible evidence; no automatic scope expansion. |
| Existing syntheses | Jeanne et al. 2022 already meta-analyzes colony-size/efficiency; Gordon's colony-level review and the 2025 division-of-labour theme issue are citation hubs. | Restore explicit prior-synthesis comparison; do not claim the entire area lacks meta-analysis. |
| Recent literature | 2024–2026 records include new inactivity models, ant recruitment studies and reproductive-plasticity reviews. | Search date-bounded updates; distinguish online/publication dates and preprint versions. |
| Coverage versus syntax | A proposed Boolean expression is not validated platform syntax; web retrieval does not establish WoS/Scopus recall. | Test exact strings in each collection, record failures/counts and retain exports. |
| Provenance/duplication | Preprint, article, thesis and deposit can be one study; records can be retrieved repeatedly. | DOI/title/year reconciliation with manual review; keep occurrence, report and study-family IDs separate. |

These are demonstrated vulnerabilities or unresolved coverage questions, not claims that every associated paper was missed.

## Prioritized reconciliation register

Inspection codes: P = primary article page/abstract or primary full-text excerpt inspected; A = author/institution record inspected; R = reference-list lead only; H = review/model context. None is a final eligibility decision.

| Record and stable link | Level | Why reconcile / coding boundary |
|---|---|---|
| [Dornhaus 2008, Specialization does not predict individual efficiency](https://doi.org/10.1371/journal.pbio.0060285) | P; known seed | Anchor individual specialization versus task efficiency. |
| [Santoro et al. 2019, Behaviourally specialized foragers](https://doi.org/10.1038/s41598-019-41791-0) | P; known seed | Wasp specialization/performance/longevity; not interchangeable with ant handling times. |
| [Jongepier & Foitzik 2016, Fitness costs of worker specialization](https://doi.org/10.1098/rspb.2015.2572) | P abstract; known project lead | Colony reproduction/growth under raids; full-text retrieval encountered challenge. |
| [Toledo et al. 2024, Performance and efficiency in leaf transport](https://doi.org/10.1007/s00265-024-03454-7) | P publisher abstract/reference list; known project lead | Activity categories rather than automatically task specialization. Subscription full text not inspected. |
| [Charbonneau & Dornhaus 2015, Workers specialized on inactivity](https://doi.org/10.1007/s00265-015-1958-1) | R | Persistent inactivity, useful measurement reference; full text needed. |
| [Charbonneau, Sasaki & Dornhaus 2017, Who needs lazy workers?](https://doi.org/10.1371/journal.pone.0184074) | P full-text excerpts; known seed | Replacement/activity homeostasis; do not infer independent completed-output recovery. |
| [Charbonneau et al. 2017, Who are the lazy ants?](https://doi.org/10.1093/icb/icx029) | P full-text excerpts | Operational definitions and alternative functions; reference hub for negative reserve evidence. |
| [Hasegawa et al. 2016, Lazy workers are necessary for long-term sustainability](https://doi.org/10.1038/srep20846) | P abstract; known seed | Separate empirical worker replacement from simulated colony persistence. |
| [Crall et al. 2018, Spatial fidelity predicts collective response](https://doi.org/10.1038/s41467-018-03561-w) | P full-text excerpts; known lead | Bumblebee removal/reallocation; foraging activity not automatically food yield. |
| [Jandt et al. 2012, Individual bumblebees vary in response to disturbance](https://www.annadornhaus.net/publications) | A author publication record | Negative defensive-reserve evidence; obtain primary full text and verify bibliographic identity. |
| [Vaes & Detrain 2022, Colony specificity and starvation-driven changes](https://doi.org/10.1371/journal.pone.0273087) | P abstract/A | Activity decreases under starvation; does not itself establish productivity. |
| [Vaes, Avanzi & Detrain 2024, Beyond busy workers](https://doi.org/10.1007/s00040-024-00959-2) | A institutional abstract | Stimulus responsiveness/larval carrying; not colony-output recovery. |
| [Group level trait and individual performance, 2025](https://www.sciencedirect.com/science/article/pii/S0003347224002860) | P indexed excerpt; direct fetch 403 | In-nest activity/recruitment connection; verify full text and author/year metadata before inclusion. |
| [Perry et al. 2015, Rapid behavioral maturation accelerates failure](https://doi.org/10.1073/pnas.1422089112) | P abstract/full-text excerpts | Empirical precocious-forager performance versus modeled colony failure; C/context boundary. |
| [Age-based spatial distribution is resilient to worker loss in a subterranean termite](https://pubmed.ncbi.nlm.nih.gov/35552445/) | P indexed abstract; direct open incomplete | Spatial/functional replacement is not necessarily measured food throughput. |
| [Brugger et al. 2018, Increase in scout trips due to forager removal](https://doi.org/10.1016/j.beproc.2018.04.015) | R | Leafcutter compensation lead from Toledo references; inspect primary report. |
| [Robinson, Feinerman & Franks 2009, Flexible task allocation](https://doi.org/10.1098/rspb.2009.1244) | R | Behavioral switching lead; verify prior worker state and endpoint. |
| [Rocha et al. 2014, Fine individual specialization and elitism: intruder removal](https://doi.org/10.1111/eth.12291) | R | Defense/task-specific language; examine specialization and actual performance metrics. |
| [Kohlmeier et al. 2018, Vitellogenin-like A and task specialization](https://doi.org/10.1371/journal.pbio.2005747) | R | Demographic reversal/mechanistic boundary; not presumed performance evidence. |
| [Jeanne et al. 2022, Michener's paradox review/meta-analysis](https://doi.org/10.1111/brv.12854) | H reviewed excerpts; known lead | Existing colony-size synthesis, task-integration terminology, historical citation hub. |
| [Gordon, Regulation of division of labor: colony-level perspective](https://pubmed.ncbi.nlm.nih.gov/38109969/) | H abstract | Colony-level conceptual framing and backward citation hub. |
| [Changes of division of labour along the eusociality spectrum in termites](https://pmc.ncbi.nlm.nih.gov/articles/PMC11923608/) | H excerpts | Expand termite sentinel/citation coverage; review is not primary evidence. |
| [Randomness as a driver of inactivity, 2024](https://pmc.ncbi.nlm.nih.gov/articles/PMC11651616/) | H abstract | Model-based alternative explanation; exclude from empirical effects. |
| [Specialism and generalism in variable environments, 2025](https://pubmed.ncbi.nlm.nih.gov/40109114/) | H abstract | Numerical model and recent citation hub; not primary biological effect evidence. |
| [Reproductive and behavioral plasticity review, 2026](https://doi.org/10.1016/j.cois.2026.101561) | H publisher excerpt | Recent succession/plasticity coverage; verify primary leads separately. |

## Amendment proposals — not yet frozen search syntax

Retain broad P AND A and P AND B searches without mandatory performance terms. Add a separately logged compensation expansion:

`P AND ("precocious foraging" OR "behavioral reversion" OR "behavioural reversion" OR "behavioral maturation" OR "behavioural maturation" OR "demographic manipulation" OR "demographic regulation" OR "nurse depletion" OR "forager depletion")`

Add bounded task-specific runs:

`P AND (remov* OR deplet* OR disturb* OR loss OR demand) AND (undertak* OR "corpse removal" OR "intruder removal" OR fanning OR thermoregulat* OR "water collection" OR "larval feeding" OR emigration OR "nest repair")`

Add integration terminology to specialization supplementary runs: `"task integration" OR "ergonomic efficiency" OR queueing OR queuing OR "material transfer" OR "sequential transport" OR elitism`. These expressions require field-code/parser validation and precision inspection before adoption. Avoid unrestricted `rest*` across all taxa without context because of noise.

## How to close the audit

1. Recover original query logs, occurrence exports, deduplicated records, screening labels and source matrices. Reconcile the register by normalized DOI and title/year, retaining ambiguous matches.
2. For each candidate record, code: already retrieved; citation-only addition; indexed but missed; not indexed; retrieval truncated/error; screened out (reason); identity unresolved. Distinguish retrieval misses from eligibility mistakes.
3. Validate old and amended searches against a taxonomically/task-balanced sentinel set with known database coverage. Report retrieval per sentinel, not an unjustified population recall estimate.
4. Execute WoS/Scopus/BIOSIS/CAB and supplementary thesis/preprint/registry searches with full logs. Search trial registries/OSF for overlapping review protocols where relevant, separately from primary-study discovery.
5. Obtain primary full texts for R/A/abstract-only candidates, follow references and citations, and retain negative/ambiguous records. Check corrections/retractions and duplicate versions before synthesis.
6. Finalize background citations and query amendments only after this reconciliation. Do not erase the original search version, retroactively classify these discoveries as prespecified, or submit OSF as a completed validated protocol.

## Discovery log

Four batches, 15 web queries, 16 November 2026; two engines. Topics: specialization/performance (Dornhaus, Santoro, Jongepier, Toledo); inactivity/reserve (Vaes, Hasegawa, Ishii); termite allocation/replacement; bumblebee removal/negative reserve tests; honeybee demographic stress and precocious foraging; task partitioning/integration; recent 2025–2026 literature. Targeted primary opens: Toledo publisher (abstract/reference list accessible); Jongepier PMC (challenge); termite PubMed (incomplete); 2025 ant recruitment publisher (403). Search-result excerpts supported discovery but are not substitutes for full-text eligibility or extraction. Search engine results are ranked and incomplete; no total unique retrieval denominator is asserted.

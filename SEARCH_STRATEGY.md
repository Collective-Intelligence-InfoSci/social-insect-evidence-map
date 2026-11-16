# Draft search strategy v0.2

These strings are **prepared, not executed or validated**. Freeze the tested versions before the formal search. Earlier exploratory searches must be logged separately. Search development follows the three streams in [PROTOCOL.md](PROTOCOL.md).

## Concept blocks

Population P:
`("social insect*" OR "eusocial insect*" OR ant OR ants OR Formicidae OR termite* OR Isoptera OR Termitidae OR Reticulitermes OR Coptotermes OR Zootermopsis OR bee OR bees OR honeybee* OR "honey bee*" OR bumblebee* OR "bumble bee*" OR "stingless bee*" OR wasp* OR Apis OR Bombus OR Melipon* OR Polistes OR Polybia OR Vespula OR Ropalidia OR Temnothorax OR Leptothorax)`

A — specialization:
`(speciali* OR "division of labo*" OR "task allocation" OR "task partition*" OR polyethism OR "task fidelity" OR "task consistency" OR "behavioral maturation" OR "behavioural maturation" OR "behavioral reversion" OR "behavioural reversion" OR "precocious forag*" OR "ergonomic efficiency" OR "task integration" OR "work integration" OR "sequential transport" OR "material transfer" OR queueing OR queuing OR elitism)`

B — inactivity:
`(inactiv* OR idl* OR "reserve labo*" OR "reserve worker*" OR "lazy worker*" OR "lazy ant*" OR "workload distribution" OR nonforag* OR "non-forag*" OR quiescen* OR "unemployed worker*" OR "resting worker*" OR "resting ant*" OR "resting bee*")`

C1 — perturbation and compensation:
`((perturb* OR remov* OR loss OR depletion OR disturbance OR challenge OR succession) AND (compensat* OR recruit* OR reallocat* OR recover* OR resilien* OR "task switch*" OR "labor replacement" OR "labour replacement"))`

C2 — demographic regulation and behavioral transitions:
`("demographic regulation" OR "demographic manipulation" OR "precocious forag*" OR "behavioral reversion" OR "behavioural reversion" OR "nurse depletion" OR "forager depletion")`

C3 — task-specific perturbation:
`((remov* OR deplet* OR disturb* OR loss OR demand OR perturb*) AND (undertak* OR "corpse removal" OR "intruder removal" OR fanning OR thermoregulat* OR "water collection" OR "larval feeding" OR emigration OR "nest repair" OR nurse* OR forag*))`

Run C1, C2 and C3 separately with P and retain query-level occurrence provenance. These complementary searches replace the single mandatory perturbation-plus-response route in v0.1. Broader A terminology may retrieve task integration without individual specialization; code these constructs separately and apply eligibility, rather than treating them as synonyms analytically. Avoid unrestricted `rest*`, which retrieves unrelated terms. Pilot precision and recall before freezing these expansions.

Do not require performance terms in the main search: doing so could miss descriptive evidence and studies using unexpected outcome terminology. Broad terms such as bee/wasp are screened for sociality rather than removed by a brittle taxonomy filter.

## Database implementation

Web of Science Core Collection Advanced Search: `TS=(P) AND TS=(A)`; repeat for B, C1, C2 and C3.

Scopus Advanced Search: `TITLE-ABS-KEY(P) AND TITLE-ABS-KEY(A)`; repeat for B, C1, C2 and C3.

Here P/A/B/C denote the exact blocks above, substituted without the letter labels. These are query specifications, not claims that database parser syntax has passed testing. Adapt phrase/wildcard behavior explicitly for each platform. BIOSIS/CAB controlled vocabulary and platform-specific field codes must be recorded after access/validation; do not copy WoS syntax blindly to another host.

## Validation and supplementary searching

1. Build an independent sentinel set spanning taxa and all streams from project seed papers, including Dornhaus 2008, Santoro et al. 2019, and Charbonneau, Sasaki & Dornhaus 2017; expand beyond these ant/wasp leads to bees and termites.
2. Check each sentinel's database coverage and retrieval; inspect misses for synonyms, indexing and spelling. Record query changes and their rationale. Add genus names or terms where justified, not just those yielding expected findings.
3. Have the other reviewer check concept coverage, Boolean structure and limits. Freeze exact executed strings, platform, indexed collections and dates.
4. Save all results/identifiers allowed by database terms. Maintain original occurrences and deduplication mappings.
5. Run backward/forward citations and searches for relevant syntheses; log seed, platform and date. Document supplementary engines' ranking/export limits.
6. Search preprints, theses and repositories using adapted blocks; record precise queries, collections, access limits and screening boundaries. Do not call an opportunistic web search exhaustive.
7. Log author contacts and missing reports. Rerun the finalized searches before manuscript submission and screen updates under the same rules.

See `templates/search_log.csv`. No formal search date, yield or validation result has been invented.

## Approved expansion and evidence exposure (16 November 2026)

The PI approved incorporating the [search-gap audit](SEARCH_GAP_AUDIT_2026-11-16.md). The expansions above are adopted for validation, not validated searches. The audit inspected selected published findings; development was therefore informed by results, including mixed and negative findings, before registration. It does not establish that any candidate was absent from the historical corpus.

Extend the candidate sentinel set with Perry et al. 2015 (honeybee maturation), Crall et al. 2018 (bumblebee disturbance), the 2022 termite worker-loss study (PMID 35552445), Toledo et al. 2024 (leaf transport), and Vaes and colleagues' inactivity studies. Include the defensive-reserve test listed in the audit to avoid validating only supportive reserve findings. Verify bibliographic identity, eligibility and indexed database coverage before using any candidate as a recall benchmark. Keep theory/reviews as citation-search seeds, not empirical inclusion sentinels. See [REFERENCES.md](REFERENCES.md) for verified rationale sources and the audit for remaining discovery leads.

Original exports are still needed to match all audit candidates by DOI/title, link study families and establish actual omissions. Neither web discovery nor this amendment is the formal database search.

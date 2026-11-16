# Draft search strategy v0.1

These strings are **prepared, not executed or validated**. Freeze the tested versions before the formal search. Earlier exploratory searches must be logged separately. Search development follows the three streams in [PROTOCOL.md](PROTOCOL.md).

## Concept blocks

Population P:
`("social insect*" OR "eusocial insect*" OR ant OR ants OR Formicidae OR termite* OR Isoptera OR Termitidae OR bee OR bees OR honeybee* OR "honey bee*" OR bumblebee* OR "bumble bee*" OR "stingless bee*" OR wasp* OR Apis OR Bombus OR Melipon* OR Polistes OR Polybia OR Vespula OR Ropalidia OR Temnothorax OR Leptothorax)`

A — specialization:
`(speciali* OR "division of labo*" OR "task allocation" OR "task partition*" OR polyethism OR "task fidelity" OR "task consistency")`

B — inactivity:
`(inactiv* OR idl* OR "reserve labo*" OR "reserve worker*" OR "lazy worker*" OR "lazy ant*" OR "workload distribution")`

C — perturbation and compensation:
`((perturb* OR remov* OR loss OR depletion OR disturbance OR challenge OR succession) AND (compensat* OR recruit* OR reallocat* OR recover* OR resilien* OR "task switch*" OR "labor replacement" OR "labour replacement"))`

Do not require performance terms in the main search: doing so could miss descriptive evidence and studies using unexpected outcome terminology. Broad terms such as bee/wasp are screened for sociality rather than removed by a brittle taxonomy filter.

## Database implementation

Web of Science Core Collection Advanced Search: `TS=(P) AND TS=(A)`; repeat for B and C.

Scopus Advanced Search: `TITLE-ABS-KEY(P) AND TITLE-ABS-KEY(A)`; repeat for B and C.

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

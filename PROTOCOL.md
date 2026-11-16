# Review protocol v0.1

**16 November 2026 — adopted working direction; pre-registration development.** Search validation, appraisal piloting, and outcome-specific statistical specification remain pending. This document is not a claim of preregistration or completed review work. Provenance is in [DECISIONS_AND_SOURCES.md](DECISIONS_AND_SOURCES.md).

## 1. Objective and questions

Map and synthesize empirical evidence on behavioral specialization, worker inactivity, and performance in social-insect colonies:

1. How is behavioral specialization associated with individual task performance and colony-level performance?
2. How is worker inactivity associated with independently measured colony performance?
3. Following perturbation, when does recruitment or task reassignment translate into recovery of completed work or colony performance?

The review does not assume specialization improves performance, inactive workers are reserves, or recruited activity restores output. Movement, activity, allocation, individual task efficiency, and colony output are distinct constructs. No blanket novelty claim is made; existing syntheses must be searched and compared.

## 2. Eligibility

Include empirical studies of ants, termites, social bees and social wasps; other insects qualify only where cooperative colony organization and a relevant construct are documented. Include laboratory, semifield and field studies, coded separately. Do not infer social organization from a taxonomic label alone.

Established worker colonies are the principal population. Founding groups and reproductive succession qualify when directly relevant to a review question, but form separate context strata. Code behavioral specialization separately from morphological caste differentiation and age-related allocation. Studies measuring only caste morphology do not establish behavioral specialization.

Maintain two evidence tiers:

- **Descriptive map:** operationally measured specialization, inactivity or perturbation-related compensation, even when performance is absent. General social-insect tracking with no relevant measured construct is insufficient.
- **Relationship synthesis:** the relevant exposure/contrast and a separately measured performance outcome, with interpretable design and sampling units. Descriptive prevalence cannot be used as an inactivity–performance association. Recruitment without output is behavioral compensation only, not demonstrated performance recovery.

Experimental and observational studies qualify. Exclude simulations without empirical observations, artificial agents, robotics, non-insect collectives, nonsocial insects, opinion and review articles from primary evidence. Reviews and theory inform context and citation searching. In mixed reports, extract eligible empirical components only.

No publication-year restriction. Search without language or publication-status exclusions; seek reliable translation. Include preprints, theses and unpublished studies when methods/results permit assessment. Record reports awaiting translation or author information separately. Abstract-only records without adequate methods/results cannot enter quantitative synthesis. Link articles, preprints, theses and deposits from the same study family; count independent studies, not reports.

## 3. Information sources and searches

Core sources: Web of Science Core Collection and Scopus. Supplement with BIOSIS and CAB Abstracts where institutional access is confirmed, dissertation/thesis sources, bioRxiv and institutional repositories. OpenAlex supports supplementary discovery and citation tracing. Search dataset repositories for associated records and rights metadata. Conduct backward/forward citation searching of included reports and relevant syntheses; contact authors for missing information and eligible unpublished work.

The PI reports access to Web of Science, Scopus and other databases; actual platform coverage and successful access must be logged, not assumed. Use [SEARCH_STRATEGY.md](SEARCH_STRATEGY.md). Search inception to the execution date, and update before manuscript submission. Preserve exact strings, filters, timestamps, counts and exported identifiers where licenses permit.

## 4. Screening

Deduplicate using DOI/other identifiers plus normalized bibliographic fields with manual review of uncertain matches. Preserve occurrence-to-record mappings; do not merge separate studies merely because they share authors or titles.

Daniel and Nitika independently screen titles/abstracts and full texts. Pilot on 100 title/abstract records and 10 full texts selected across streams and ambiguous cases. Discuss discrepancies and revise the codebook before full screening. Reassess pilot records against the final rules. No numerical agreement target has been asserted; unresolved systematic interpretation differences trigger another calibration batch.

Resolve disagreements through discussion, then Greg as adjudicator. Log full-text exclusions using a primary reason: wrong population; no relevant construct; ineligible study/report type; no usable empirical component; duplicate report with no unique information. Lack of a performance outcome excludes only from relationship synthesis, not automatically from the descriptive map. Unretrieved reports and pending information are separate statuses, not substantive exclusions.

Report flow counts for occurrences, records, reports and study families. A paper may contribute to multiple streams but is not thereby multiple independent studies.

## 5. Extraction and appraisal

Use [EXTRACTION_AND_APPRAISAL.md](EXTRACTION_AND_APPRAISAL.md) and the blank templates. Pilot extraction/appraisal on 10 diverse eligible studies before full extraction; revise definitions and recheck pilot entries. One reviewer extracts descriptive data and the other verifies against the source. Two reviewers independently extract all numerical inputs for any pooled analysis and independently appraise quality; reconcile differences and retain provenance (page/table/figure).

Extract sample size at each level, colony/species/study dependence, observation length and thresholds, task/outcome definitions, perturbation and comparator details, effect estimates and uncertainty. Record unavailable data as missing, not zero. Contact authors where necessary, logging requests and responses. Any digitization or reconstruction must retain its source, formula, uncertainty assumptions and human verification.

Assess domains rather than an aggregate score: sampling/selection, allocation and baseline comparability, confounding, measurement validity, temporal alignment, missingness, selective reporting, and statistical independence. Use low concern / some concern / high concern / unclear / not applicable, with reasons and source locations. Domain judgments guide limitations and sensitivity analyses rather than post hoc favorable-study selection.

## 6. Synthesis

Deliver a descriptive evidence map irrespective of pooling feasibility. Tabulate evidence by stream, taxon, social/colony stage, setting, design, construct definition, observation window and outcome level. Summarize effect direction, magnitude and uncertainty where available, without counting statistically significant results as votes. Distinguish absence of evidence from evidence of no effect.

Daniel and Nitika coordinate the quantitative plan. A subset is considered for pooling only when studies share a scientifically comparable construct, contrast, outcome and timescale; provide effect estimates and uncertainty; and permit defensible dependence handling. At least two independent study families are necessary but not sufficient. Two-study estimates, if justified, are exploratory. Do not apply the older 15-effects/five-species threshold as a universal gate.

Do not pool activity prevalence across incompatible inactivity definitions/windows, individual efficiency with colony output, or behavioral recruitment with output recovery. Separate observational associations from intervention contrasts. Correlation transformations may suit comparable associations; standardized mean differences or log response ratios may suit particular contrasts, but no universal effect metric is selected in advance of the outcome inventory. Repeated measures, shared controls, colonies nested within studies and overlapping datasets must not be treated as independent.

Before fitting pooled models, finalize and date the outcome-specific analysis specification: estimand, metric and direction, conversion rules, variance/covariance assumptions, model and estimator, dependency handling, heterogeneity/interval reporting, moderator feasibility, missing-data rules, robustness analyses and small-study/reporting-bias assessment. Choose based on design/measurement compatibility, not favorable effects. Disclose any effect results already inspected. A decision to defer statistical detail does not constitute a completed preregistered analysis plan.

Potential sensitivity analyses include excluding high-concern studies, separating unpublished/preprint evidence, alternative justified dependence assumptions, and leave-one-study-family-out checks where informative. Moderator and phylogenetic analyses require adequate information; no automatic ten-species rule is adopted. If defensible synthesis is not possible, report the incompatibility and evidence gaps instead of forcing a pooled result.

## 7. AI and reproducibility

AI may assist query development, prioritization, translation and extraction suggestions, with recorded tool/version, purpose and human verification. No AI-only eligibility exclusion, final appraisal or unverified numerical extraction. Verify source citations and extracted claims against originals. Follow source access and data-use conditions before sending documents to external services. Preserve human decisions and reproducible analysis scripts when produced. Report using PRISMA 2020 and relevant ecological/evolutionary reporting guidance; reporting checklists do not themselves establish methodological quality.

## 8. Rights, conflicts and governance

Cross-species raw-data reanalysis is deferred. Greg coordinates a dataset-level rights audit covering exact version, license, ownership, attribution, redistribution, derivative uses and unpublished-data agreements. Public availability is not blanket clearance. A later reanalysis needs its own explicit methods/rights approval and separate protocol or amendment.

All authors are affiliated with the College of Information Science, University of Arizona. Greg confirmed agreed roles, no dedicated funding and no conflicts on 16 November 2026. Team-authored work remains eligible, but authors do not judge their own papers. Use two non-author reviewers, recruiting an external reviewer if needed. Authorship overlap and related intellectual interests are disclosed even with no declared conflicts.

Greg is review lead and OSF administrator; Daniel and Nitika jointly coordinate synthesis/statistics and carry out screening, extraction, verification and appraisal. No backup OSF administrator has been designated. Authorship order will reflect agreed contributions.

## 9. Timing, outputs and amendments

13 November 2026 is a documented review-development milestone, not a verified first-search date. Target completion is 13 November 2027. Preliminary searches and assessments predate registration and will be disclosed. No final included-study denominator or new pooled estimate is claimed.

Outputs: registered protocol, search logs and strategies, screening decisions, extraction dictionary/table, evidence map, quality assessments, synthesis code where applicable, manuscript, and documented gaps. Release only rights-cleared materials under the appropriate licenses. Team-authored materials use CC BY 4.0; future original code is intended for MIT, with its own license when created.

Publish the OSF registration after readiness checks and explicit submission authorization. Record amendments with date, rationale, affected fields and stage of evidence exposure; never silently rewrite the registered historical plan.

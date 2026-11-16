# Extraction dictionary and appraisal v0.1

Blank templates contain no study results. Pilot and freeze coding instructions before full extraction.

## Core coding

- `study_family_id`: shared underlying sample/experiment; links all reports and deposits.
- `report_id`, `doi_or_url`, `source_location`: bibliographic identity and exact page/table/figure for each claim.
- `evidence_stream`: A specialization; B inactivity; C compensation; multiple values allowed.
- `evidence_tier`: descriptive map or relationship synthesis; explain the latter's independently measured outcome.
- `taxon`, `species`, `social_organization`, `colony_stage`, `setting`: retain authors' descriptions; founding/succession separate from established worker colonies.
- `design`, `exposure_or_intervention`, `comparator`: distinguish observational differences from manipulated contrasts.
- `specialization_definition`: index, formula, tasks, behavioral versus morphological/age basis, observation window.
- `inactivity_definition`: threshold, denominator, interval, behavior versus movement, visible/unobserved status. Unobserved is not inactive.
- `perturbation`, `compensation_measure`: what was altered, baseline, recovery window, recruitment origin if tracked, output evidence.
- `outcome_definition`, `outcome_level`, `outcome_unit`: distinguish movement/activity/allocation from individual efficiency and colony output; retain direction and denominator.
- `n_studies`, `n_species`, `n_colonies`, `n_individuals`, `n_observations`: retain nesting; repeated observations do not increase independent colony count.
- `effect_metric`, `estimate`, `uncertainty_type`, `uncertainty_value`, `sample_sizes`: original reported values and units before conversion. Add row-level contrasts/outcomes as needed.
- `dependence_notes`: shared control, repeated time, reused colony/sample, species or family overlap.
- `missing_information`, `author_contact`, `rights_status`: no inference of permission from accessibility.
- `extractor`, `verifier`, `resolution`, `version`: audit trail.

## Appraisal questions

| Domain | Questions |
|---|---|
| Selection | Were colonies/individuals selected in a way that could distort the target relationship? Is target population clear? |
| Allocation/comparability | For interventions, how were groups allocated and baseline differences handled? For observations, are comparison groups interpretable? |
| Confounding | Were relevant colony size/stage, age/caste, environment, task and time differences measured or addressed? Do not require every confounder in every design. |
| Measurement | Are specialization/inactivity definitions reproducible? Is performance independently measured? Is movement substituted for work? Could observer knowledge affect measurement? |
| Timing | Are exposure and outcome windows aligned with the question? Are pre/post comparisons and recovery intervals appropriate? |
| Missingness | Are missing individuals, occlusion, tracking failures and excluded trials reported and plausibly consequential? |
| Reporting | Are measured outcomes/analyses selectively presented? Are protocols or methods available to assess this? Absence of a preregistration alone is not high risk. |
| Independence | Are colony-level replication, shared controls, repeated measures and reused data handled appropriately? |

Use low concern / some concern / high concern / unclear / not applicable. Provide domain-specific justification and source locations. Do not sum judgments into a quality score. Record external relevance (taxon, setting, stage) separately from internal validity. Lack of sufficient detail is unclear, not evidence that sound procedures were used.

## Pooling inventory

For every proposed subset, document construct, contrast, outcome, window, independent families, available effect/variance, dependence, major appraisal concerns and an include/defer/no-pooling decision with reasons. Final quantitative specifications are led by Nitika and Daniel and dated before fitting; no subset is currently certified pool-ready.

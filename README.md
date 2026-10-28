# IMARA: Integrated Meta-Analysis Resource for Africa

Open data behind the IMARA preview: what the published literature reports about lymphoma, leukaemia and myeloma in
African patients. Release 54, data of 2026-10-28.

**Preview page:** `index.html` (served by GitHub Pages when switched on).

## Headline numbers

| | |
|---|---|
| Studies with African patient data | 1,193 |
| Patients reported across those studies | 140,345 |
| Unique patients after removing the same cohort reported twice (estimate) | 120,168 |
| African countries | 43 (37 in the WHO African Region) |
| Disease groups | 8 |

Population-registry studies (59 papers, 214,657 patient records) are counted separately.

## Files

| File | What it holds |
|---|---|
| `data/studies.csv` | 1,398 studies: citation, disease group, countries, design, enrolment years, patients |
| `data/values.csv` | 29,813 extracted values: patient group, field, value, unit, denominator, reported or calculated, where in the paper |
| `data/pooled_estimates.csv` | 157 pooled estimates by disease group (random effects, with 95 % and prediction intervals) |
| `data/survival_curves.csv` | overall survival of patients rebuilt from published curves, all and by disease group |
| `data/survival_hiv.csv` | the same for HIV-positive and HIV-negative patients, compared within studies |
| `data/summary.json` | the headline numbers and summary results |

## How the data were built

Systematic searches of the international and African medical literature; every candidate study screened for African
patients with a blood cancer and data of their own; values extracted study by study, each traceable to its place in the
paper; values cross-checked and the same patients counted once; results pooled with standard meta-analysis methods.

**Status:** provisional and under continuing review. Values were extracted with automated tools and cross-checked; they
have not yet been checked by a person. Always confirm a value against the cited paper before relying on it.

## Use and citation

Licence to be confirmed. Until then, please ask before reusing the data. The underlying facts belong to the cited
studies; cite them alongside IMARA.

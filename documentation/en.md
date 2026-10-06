<!-- ELUCENIA technical documentation · gad-7 · en · no clinical/professional/rights approval -->

# GAD-7 scale

[conditions, sources and permissions](https://elucenia.org/en/tools/gad-7)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Over the last 2 weeks, how often have you been bothered by the following problems? 1. Feeling nervous, anxious or very tense

`q1`

- `0` — Never
- `1` — Several days
- `2` — More than half the days
- `3` — Nearly every day

### 2. Not being able to stop or control worrying

`q2`

- `0` — Never
- `1` — Several days
- `2` — More than half the days
- `3` — Nearly every day

### 3. Worrying a lot about different things

`q3`

- `0` — Never
- `1` — Several days
- `2` — More than half the days
- `3` — Nearly every day

### 4. Difficulty relaxing

`q4`

- `0` — Never
- `1` — Several days
- `2` — More than half the days
- `3` — Nearly every day

### 5. Being so restless that it is difficult to sit still

`q5`

- `0` — Never
- `1` — Several days
- `2` — More than half the days
- `3` — Nearly every day

### 6. Becoming easily annoyed or irritable

`q6`

- `0` — Never
- `1` — Several days
- `2` — More than half the days
- `3` — Nearly every day

### 7. Feeling afraid as if something awful might happen

`q7`

- `0` — Never
- `1` — Several days
- `2` — More than half the days
- `3` — Nearly every day

## Method edition

GAD-7/Spitzer 2006: 7 items 0–3, total 0–21; cutoffs 5/10/15; Brazilian Portuguese Moreno 2016

## Documented formula

Each item scores 0 (not at all) to 3 (nearly every day). Total 0 to 21. Severity cutoffs: 5, 10, 15. For generalized anxiety screening, ≥10 showed 89% sensitivity and 82% specificity in the original study.

## Limits and population

Screening and measurement of generalized anxiety symptom severity in adults. A probable result requires diagnostic assessment. Primary-care studies and the Brazilian community sample do not automatically validate new populations, the local implementation or additional translations.

## References

- [Spitzer RL et al. A brief measure for assessing generalized anxiety disorder: the GAD-7. Arch Intern Med, 2006.](https://doi.org/10.1001/archinte.166.10.1092)

- [Moreno AL et al. Factor structure, reliability, and item parameters of the Brazilian-Portuguese version of the GAD-7 questionnaire. Temas em Psicologia, 2016.](https://doi.org/10.9788/TP2016.1-25)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Minimal anxiety (0 to 4)

Screening instrument: does not make a diagnosis.


### 2

Moderate anxiety (10 to 14): positive screening

Confirm with clinical interview: GAD, panic, social anxiety, and PTSD also score high.


### 3

Severe anxiety (15 to 21): positive screening

Confirm with clinical interview and start active treatment.


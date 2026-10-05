<!-- ELUCENIA technical documentation · ipi-linfoma · en · no clinical/professional/rights approval -->

# IPI (International Prognostic Index)

[conditions, sources and permissions](https://elucenia.org/en/tools/ipi-linfoma)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Age \> 60 years

`idade`

### Serum LDH above the upper limit of normal

`ldh`

### ECOG ≥ 2

`ecog`

### Ann Arbor stage III or IV

`estadio`

### More than 1 extranodal site

`extranodal`

## Method edition

International Prognostic Index 1993: 5 factors, 0–5; not NCCN-IPI or R-IPI

## Documented formula

One point for each factor: age \> 60 years · elevated LDH · ECOG ≥ 2 · stage III or IV · more than 1 extranodal site. Maximum: 5.

## Limits and population

A classic prognostic index for adults with aggressive non-Hodgkin lymphoma, developed before treatment in historical doxorubicin cohorts. Distinguish classic IPI, age-adjusted IPI, R-IPI and NCCN-IPI. Historical probabilities do not demonstrate calibration for all subtypes or current treatments.

## References

- [The International Non-Hodgkin's Lymphoma Prognostic Factors Project. A predictive model for aggressive non-Hodgkin's lymphoma. N Engl J Med, 1993.](https://doi.org/10.1056/NEJM199309303291402)

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

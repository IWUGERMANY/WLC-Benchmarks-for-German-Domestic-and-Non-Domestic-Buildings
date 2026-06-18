# Methodology Summary

This repository accompanies a paper proposing a transparent method for defining and communicating whole-life-cycle greenhouse-gas benchmarks for buildings. The released workbook applies the method to the German building-stock context.

## Benchmark Logic

The benchmark framework defines A-G performance classes for each building usage category. Class boundaries are based on:

- a theoretical long-term target of zero fossil GHG emissions,
- medium- and short-term target values,
- current-practice reference values,
- upper limit values,
- interpolated values between selected thresholds.

Operational and embodied emissions are tracked separately and then combined into whole-life-cycle benchmark values.

## Functional Unit And Boundary

- Functional unit: one square metre of gross floor area per year.
- Unit: `kg CO2e/(m2 GFA*a)`.
- Reference study period: 50 years.
- Main indicator: `GWPfossil`.
- Core life-cycle modules: A1-A3, B4, B6, C3-C4.
- Module D and biogenic carbon are not used to offset the main benchmark balance and should be reported separately where relevant.

## German Case-Study Application

The case-study dataset differentiates 13 domestic and non-domestic building usage categories. Operational reference and limit values are derived from German building-stock data and models. Target values use adapted proxy values where Germany-specific planetary-boundary-derived values are not available. Embodied reference and limit values use European embodied-carbon benchmark data where German-specific representative datasets are not available.

## Interpretation

The benchmark values are intended for transparent comparison and early design communication. They should not be interpreted as a final normative standard. The paper explicitly identifies the need for future validation and calibration with larger, more representative German building datasets.

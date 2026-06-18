# Data Dictionary

This document describes the sheets in `data/WLC_Benchmarks.xlsx`. The workbook is the authoritative dataset artifact for this release.

## Workbook-Level Scope

- Indicator: `GWPfossil`
- Unit: `kg CO2e/(m2 GFA*a)`
- Reference study period: 50 years
- Core system boundary: A1-A3, B4, B6, C3-C4
- Performance classes: A-G benchmark classes derived from target, reference, limit, and interpolated values

## Sheets

### `Benchmarks`

Derived benchmark class boundaries and whole-life-cycle values. This sheet combines operational and embodied benchmark components into benchmark classes for the covered building usage categories.

### `targets`

Target values by building type and ambition level. This sheet contains values used to define target-related benchmark thresholds.

### `op_non-res`

Operational benchmark inputs for non-residential building categories. This sheet documents operational-emission statistics and category labels used for non-residential benchmarks.

### `op_res`

Residential operational inputs. This sheet contains residential building-stock and operational-emission assumptions used for residential benchmarks.

### `emb_res_non-res`

Embodied carbon source and derivation data for residential and non-residential building categories. This sheet includes embodied-emission statistics and transformations used in benchmark derivation.

## Notes For Users

- The workbook is released as-is and remains the source of truth for this first dataset release.
- Raw source datasets from third parties are not redistributed here.
- Where source assumptions are needed to interpret the values, use `docs/source_provenance.md` and the accompanying paper.

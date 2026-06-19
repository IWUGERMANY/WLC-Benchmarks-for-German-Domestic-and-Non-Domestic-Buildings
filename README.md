# Whole-Life-Cycle Benchmarks for Domestic and Non-Domestic Buildings: A Method for Definition and Communication Applied to the German Building Stock

Dataset accompanying the paper:

**Whole-Life-Cycle Benchmarks for Domestic and Non-Domestic Buildings: A Method for Definition and Communication Applied to the German Building Stock**  
Behem and Bischof, 2026

The paper was written for the [eceee Summer Study 2026](https://www.eceee.org/summerstudy/).

## Repository Status

This repository is a dataset release accompanying a paper currently in copyediting. The workbook is released as the authoritative dataset artifact. Values, wording, citation details, and metadata may still be updated after the final publication.

The study was conducted within the [LezBAU project](https://www.lezbau.de/), which develops a life-cycle assessment tool to support early-design decisions for the German building context.

The manuscript PDF, copyedited publisher files, raw third-party source datasets, and extracted copyrighted source material are not included in this repository.

## Dataset

- Workbook: [data/WLC_Benchmarks.xlsx](data/WLC_Benchmarks.xlsx)
- Indicator: `GWPfossil`
- Unit: `kg CO2e/(m2 GFA*a)`
- Reference study period: 50 years
- Core system boundary: A1-A3, B4, B6, C3-C4
- Reporting convention: Module D and biogenic carbon are treated separately where relevant
- Scope: benchmark values for 13 domestic and non-domestic building usage categories in the German case-study context

## Covered Building Usage Categories

The workbook covers:

1. Multi-family houses
2. Single- and two-family houses
3. Trade Buildings
4. Office, Administrative or Government Buildings
5. Sports Facilities
6. Technical and Utility Buildings (supply and disposal)
7. School, Day Nursery and other Care Buildings
8. Transport Buildings
9. Buildings for Health and Care
10. Buildings for Research and University Teaching
11. Production, Workshop, Warehouse or Operations
12. Hotels, Boarding, Restaurants or Catering
13. Buildings for Culture and Leisure

## Method Summary

The dataset implements a whole-life-cycle greenhouse-gas benchmark framework for building use categories. Benchmark class boundaries are derived from target, reference, and limit values, then expressed as A-G performance classes. Operational and embodied contributions are distinguished so that users can interpret both whole-life-cycle performance and the underlying emission structure.

The method is designed as a transparent benchmark definition and communication approach rather than as a final normative standard. It combines policy-aligned target values, current-practice reference values, limit values, and interpolated class boundaries.

For more detail, see:

- [docs/methodology_summary.md](docs/methodology_summary.md)
- [docs/data_dictionary.md](docs/data_dictionary.md)
- [docs/source_provenance.md](docs/source_provenance.md)

## License

Repository documentation and the released benchmark workbook are provided under the MIT License amended for datasets; see [LICENSE](LICENSE). Third-party source datasets and publications remain under their original rights and are not redistributed here.

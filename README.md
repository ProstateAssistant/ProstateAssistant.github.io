# Prostate Reference Percentiles

[![Calculator](https://img.shields.io/badge/calculator-prostateassistant.github.io-1c5cab)](https://prostateassistant.github.io/)
[![Paper](https://img.shields.io/badge/Eur%20Radiol-2026-2a78d6)](https://doi.org/10.1007/s00330-026-12937-2)

Age-, BMI- and height-adjusted reference values for **PSA**, **PSA density** and **MRI prostate volume**. They come from 1,037 men in the population-based SHIP cohort (Germany) who stayed free of prostate cancer, BPH and LUTS over about 10 years of follow-up. Prostate volume was measured by deep-learning MRI segmentation, and the percentiles were modelled with GAMLSS.

> Lindholz M, et al. **Reference values for PSA, PSA density, and MRI prostate volume in healthy German men.** *Eur Radiol* (2026). https://doi.org/10.1007/s00330-026-12937-2

| | Median | 95th percentile |
|---|---:|---:|
| Prostate volume | 31.3 mL | 51.4 mL |
| PSA | 0.81 ng/mL | 2.79 ng/mL |
| PSA density | 0.025 ng/mL² | 0.071 ng/mL² |

- **Prostate volume** and **PSA** rise with age.
- **PSA density** is more stable with age than PSA: in the age-adjusted analysis, its 95th percentile stays at or below **0.11 ng/mL²** across all ages.
- **Higher BMI** means a larger prostate and a lower PSA density.

The percentile tables are in [`data/`](data/). The calculator is a research tool, not a diagnostic device.

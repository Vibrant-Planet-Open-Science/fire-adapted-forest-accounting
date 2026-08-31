# Fire-Adapted Forest Carbon: An Observed-Counterfactual Quantification Approach

*Katharyn Duffy ([ORCID 0000-0001-6108-7718](https://orcid.org/0000-0001-6108-7718)) · Ethan Yackulic ([ORCID 0000-0001-5500-0401](https://orcid.org/0000-0001-5500-0401)) · Spencer Plumb ([ORCID 0000-0002-0821-8755](https://orcid.org/0000-0002-0821-8755))*

We have known how to temper high-severity fire for decades: thinning, prescribed and cultural fire, and restoration of the open stand structures that frequent fire once maintained. What has lagged is the accounting. A treatment's carbon benefit is largely carbon kept in the forest — stores that survive fire because fuels were reduced — and what is kept can only be measured against the untreated fate of the same forest. Wildfire is stochastic and heterogeneous; plots cannot sample that variance, and growth-and-yield models cannot predict it. The only credible counterfactual is an observed one.

This repository holds that approach in full. Each treated area is paired at the outset with a fixed control area matched on pretreatment conditions, and both are observed — every pixel, every year, by the same remote-sensing product — for the life of the intervention. Field inventories test the remotely sensed record at each verification, and every correction runs one direction: it can only reduce creditable benefit. Residual uncertainty is charged once, as a single conservative deduction, before any benefit is calculated. The document lays the logic out end to end — observation to creditable benefit, all 87 equations in execution order — so that every reported number traces back to the data that produced it.

## Contents

- [`docs/methodology.md`](docs/methodology.md) — the complete quantification approach. This file is canonical; everything else derives from it.
- [`docs/methodology.qmd`](docs/methodology.qmd) — a thin [Quarto](https://quarto.org) wrapper for rendering. `quarto render docs/methodology.qmd` produces HTML; add `--to pdf` for print.
- [`docs/figs/`](docs/figs/) — all figures, numbered in document order.

## Status

We drafted this approach for the Verra VCS Program as **M0159, Improved Forest Management for Fire-Adapted Forests**, where it is under review. This document is M0159's technical complement: the same science, equations, and accounting, stripped of program-specific requirements so that it stands alone — a specification for implementation, a reference for peer review, and a quantification approach any crediting program or research application can adopt.

This approach builds upon the proof of concept in [Yackulic et al. (2025)](https://www.frontiersin.org/journals/forests-and-global-change/articles/10.3389/ffgc.2025.1498430/full), which applied the same natural experimental design to fuel-reduction treatments across the central Sierra Nevada over seven years.

## Citing this work

Duffy, K., Yackulic, E., & Plumb, S. (2026). *Fire-Adapted Forest Carbon: An Observed-Counterfactual Quantification Approach.* Version 1.0.

A DOI is forthcoming.

## License

This work is licensed under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) (Attribution–NonCommercial–NoDerivatives). You may share it with attribution; commercial use and distribution of modified versions require permission from the authors. See [LICENSE](LICENSE) for the full terms.

## Contact

Katharyn Duffy — katharyn@vibrantplanet.net

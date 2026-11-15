---
layout: software
title: Pipelines & Software
meta_description: Open research software for spectral energy distribution fitting and Bayesian inference of circumstellar dust around evolved stars.
---

# Research Pipelines & Software

I develop computational tools for the analysis of evolved stars, with an emphasis on transparent, reproducible inference of circumstellar dust properties and mass-loss rates.

## SEDust

[GitHub repository](https://github.com/hmahani/SEDust) · [Zenodo record](https://doi.org/10.5281/zenodo.22858441)

**SEDust** is a pipeline for fitting AGB-star spectral energy distributions with DUSTY models to derive stellar luminosities and mass-loss rates. It provides a systematic workflow for comparing observed multiwavelength photometry with pre-computed radiative-transfer model grids.

**Main capabilities**
- Fits observed broadband SEDs with DUSTY-based model grids.
- Estimates luminosity, circumstellar optical depth, and mass-loss rate.
- Supports analysis of oxygen-rich and carbon-rich dust assumptions.
- Provides a reproducible workflow suitable for application to stellar catalogues.

**Repository:** [github.com/hmahani/SEDust](https://github.com/hmahani/SEDust)  
**DOI:** [10.5281/zenodo.22858441](https://doi.org/10.5281/zenodo.22858441)  
**License:** MIT

## MCM-SEDust

**MCM-SEDust** is a Bayesian framework built to extend the SEDust approach using Markov chain Monte Carlo (MCMC) sampling. It is designed to estimate posterior distributions for circumstellar dust parameters, propagate parameter uncertainties, and allow more flexible modelling choices, including dust composition.

The framework uses the `emcee` ensemble sampler and supports posterior exploration and diagnostic visualisation. It is being developed for robust inference from multiwavelength photometry of evolved stars.

*Associated manuscript: “MCM-SEDust: An MCMC Framework for Bayesian Inference of Circumstellar Dust Properties in Evolved Stars” (in preparation).*

## Reproducibility and collaboration

I aim to make research workflows accessible and reusable. For code, implementation details, or potential scientific collaborations, please visit my [GitHub profile](https://github.com/hmahani) or [contact me by email](mailto:mahani@ipm.ir).

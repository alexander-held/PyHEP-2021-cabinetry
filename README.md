# `cabinetry` notebook talk at PyHEP 2021

Contribution to PyHEP 2021: [*Binned template fits with `cabinetry`* (Kyle Cranmer, Alexander Held)](https://indico.cern.ch/event/1019958/contributions/4421868/)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/alexander-held/PyHEP-2021-cabinetry/HEAD?filepath=talk.ipynb)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5076505.svg)](https://doi.org/10.5281/zenodo.5076505)

The `cabinetry` library provides a Python-based solution for building and steering binned template fits. It implements a declarative approach to construct statistical models. The instructions for building all template histograms required for a statistical model are executed using other libraries in the pythonic HEP ecosystem. Instructions can additionally be injected via custom code, which is automatically executed when applicable at key steps of the workflow. A seamless integration with the `pyhf` library enables `cabinetry` to provide interfaces for all common statistical inference tasks. The `cabinetry` library furthermore contains utilities to study and visualize statistical models and fit results.

This tutorial provides an overview of `cabinetry` and shows its use in the creation and operation of statistical models. It also demonstrates how to use `cabinetry` for common tasks required during the design of a statistical analysis model.

## Further resources
- `cabinetry` on GitHub: https://github.com/alexander-held/cabinetry/
- documentation: https://cabinetry.readthedocs.io/
- additional tutorial material: https://github.com/cabinetry/cabinetry-tutorials

## Acknowledgements

[![NSF-1836650](https://img.shields.io/badge/NSF-1836650-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1836650)

This work was supported by the U.S. National Science Foundation (NSF) cooperative agreement [OAC-1836650 (IRIS-HEP)](https://nsf.gov/awardsearch/showAward?AWD_ID=1836650).

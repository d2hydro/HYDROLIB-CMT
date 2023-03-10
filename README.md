# Case Management Tools (hydrolib-cmt)

Open Source Case Management Tools for [D3DFM/D-HYDRO](https://www.deltares.nl/en/software/delft3d-flexible-mesh-suite/)

CMT includes:

* Generation of one or multiple cases for D-HYDRO using an uniform directory structure
* Generation of cases as part of a StochasticTool (HydroConsult) workflow
* Generation of rainfal events from STOWA parameters
* Run D-HYDRO scenarios in single or parallel mode
* On-the-fly post-processing of results on desired location.

[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Release: latest](https://img.shields.io/github/v/release/d2hydro/HYDROLIB-CMT)](https://pypi.org/project/hydrolib-cmt)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/d2hydro/HYDROLIB-CMT/blob/main/LICENSE)

---

**Documentation**: [https://d2hydro.github.io/HYDROLIB-CMT/](https://d2hydro.github.io/HYDROLIB-CMT/)

**Source Code**: [https://github.com/d2hydro/hydrolib-cmt](https://github.com/d2hydro/hydrolib-cmt)

---

## Installation

### New environment

We recommend to build your environment using [Anaconda](https://www.anaconda.com/). You can build an environment ánd install CMT by conda in one go using this <a href="https://github.com/d2hydro/HYDROLIB-CMT/blob/51b142740e9930b0d08ef300c37ad23646b7b6c8/envs/environment.yml" target="_blank">environment.yml</a> from the command-line:
```
conda env create -f environment.yml
```

After creating your environment you can activate it with:
```
conda activate hydrolib
```

### Existing environment
In an activated existing hydrolib-environment hydrolib-cmt can be added with:
```
pip install hydrolib-cmt
```

## Get started

The repository contains a self-explanatory [Jupyter Notebook](https://github.com/d2hydro/HYDROLIB-CMT/blob/8e06a26b2c5eae892e17d0840550ad47b0e0c6cd/notebooks/stochasten_workflow.ipynb) (in Dutch). You can open it in an activated environment in the notebooks directory by:

```
jupyter notebook stochasten_workflow.ipynb
```

## About

Case Management Tools is developed and maintained by [D2Hydro](https://d2hydro.nl/) and freely available under an Open Source <a href="https://github.com/d2hydro/HYDROLIB-CMT/blob/main/LICENSE" target="_blank">MIT license</a>.

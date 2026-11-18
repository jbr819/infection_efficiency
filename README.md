This repository contains the data, model fitting and figure generation code used to generate the
results and figures presented in:

**Rich, J. et al. "A Generalised Linear Modelling Approach to Estimating Infection Efficiency in Plant Inoculation Experiments"**

## Contents

- `data/` — Data used in the analyses.
- `figures.ipynb` — Jupyter notebook containing the analysis code used to
  generate the figures presented in the paper.
- TODO: add `.R` scripts

## Requirements
The model fitting was performed using the `glmmTMB` libary for R.
The figure generation was performed using Python and Jupyter Notebook. 
The required Python packages are imported in `figures.ipynb`.

A LaTeX installation is also required to reproduce the figures, as LaTeX
is used for mathematical typesetting.

## Reproducibility

To reproduce the model fitting and figures presented in the paper:

1. Clone or download this repository.
2. Ensure that R, Python, Jupyter Notebook, and LaTeX are installed.
3. Run the R scripts to generate the model fit parameters.
4. Open `figures.ipynb`.
5. Run the code cells from start to finish.

The Jupyter notebook will load the data from the `data/` directory and reproduce the
analyses and figures presented in the manuscript.

## Citation

If you use the code or data from this repository, please cite the associated
paper:

**Rich, J. et al. "A Generalised Linear Modelling Approach to Estimating Infection Efficiency in Plant Inoculation Experiments"**

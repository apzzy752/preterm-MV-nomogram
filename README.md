# Preterm-MV-Nomogram

This repository hosts the **R code** for the study  
**“A Three-Factor Nomogram Predicts Mechanical Ventilation within 72 Hours in Preterm Infants.”**

## Directory
- `scripts/` Main analysis workflow (`lasso_selection.R`, `nomogram_build.R`, `dca_plot.R`)
- `figures/` Deposited output plots used in the manuscript (optional)

## Reproducibility
1. Install required packages via `scripts/00_install_packages.R`.
2. Run `scripts/01_analysis_pipeline.R` to reproduce all statistics and figures.  
   > **Note:** the pipeline expects a local CSV dataset named `preterm_MV_data.csv`,  
   > which contains de-identified clinical variables described in the manuscript.  
   > This dataset is not publicly posted due to privacy regulations but can be  
   > obtained from the corresponding author on reasonable request.

## License
MIT License (see `LICENSE` for details).

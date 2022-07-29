# Matching Methods for Environmental Epidemiology: A Tutorial

This repository contains all the materials necessary to reproduce our tutorial on matching methods for environmental epidemiology. The data and code are also archived on an Open Science Framework repository: https://osf.io/tvdnf/.

The repository is organized to render the annotated codes as a Distill website, which can be found at this link: https://lzabrocki.github.io/tutorial_matching_envi_epi/.

* The folder `inputs` contains the data, the functions, but also the outputs from the analysis such as data on covariate balance, analysis results and graphs.
* The folder `docs` contains the .html pages to render the website.
* `index.Rmd` is the homepage of the website.
* In `intuition.Rmd`, we use an example from[Jennifer Hill (2011)](https://www.tandfonline.com/doi/abs/10.1198/jcgs.2010.08162) to explain why covariates balance matter for identifying causal effects.
* In `data_sources_codebook.Rmd`, we present the sources of the datasets and the codebook of the variables.
* In `eda_covariates_balance.Rmd`, we explore the balance of covariates before matching.
* In `outcome_regression_analysis.Rmd`, we implement an outcome regression analysis, as often done in epidemiology.
* In `propensity_score_matching.Rmd`, we implement two propensity score matching procedures (without and with a caliper).
* In `coarsened_exact_matching.Rmd`, we implement a coarsened exact matching procedure.
* In `cardinality_matching.Rmd`, we implement a cardinality matching algorithm procedure.
* In `summary_results.Rmd`, we display the table of all results.

**Should you find any errors or have any questions, please do not hesitate to reach me.**




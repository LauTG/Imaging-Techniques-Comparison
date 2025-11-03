# Imaging Techniques Comparison in Diagnosis

**Objective.** Comparative statistical analysis of imaging modalities in a clinical dataset. The workflow evaluates agreement and diagnostic performance between methods and summarizes effect estimates with reproducible outputs.

## Data Workflow (ETL)
- Data import and structuring from tabular sources.
- Cleaning, recoding, factor preparation.
- Reproducible rendering via RMarkdown.

## Statistical Methods
- Descriptives: median [IQR], counts (%), stratified summaries.
- Agreement: Cohen's kappa / weighted kappa for inter-method agreement.
- Paired comparisons: McNemar test for binary paired outcomes.
- Regression: logistic regression for binary diagnostic targets; proportional odds (ordinal) where applicable.
- Performance: sensitivity/specificity with CIs when defined by a reference standard.

## R Packages (typical)
`tidyverse`, `ggplot2`, `readxl`, `irr`, `caret`, `Hmisc`, `kableExtra`


## Reproducibility
- This repository contains an anonymized RMarkdown
- No institution, site, or subject identifiers are included in narrative text; code blocks remain unmodified.

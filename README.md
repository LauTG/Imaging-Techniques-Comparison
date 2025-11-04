# Imaging Techniques Comparison in Diagnosis

![Made with RStudio](https://img.shields.io/badge/Made%20with-RStudio-blue?logo=rstudio)

This repository contains the **statistical report** of an anonymized comparative study assessing **diagnostic imaging modalities** in a clinical dataset.  
All references that could identify the study, institution, cohort, or clinical condition—as well as any conclusions referring to unpublished results—have been removed or generalized.

## Scope

- **Objective:** Comparative statistical evaluation of diagnostic imaging methods, focusing on agreement, performance metrics, and reproducible data summaries.  
- **Audience:** Scientific and technical teams involved in quantitative imaging or diagnostic validation.

## Workflow

1. **Data processing and cleaning:**
   - Import and structuring of tabular data sources.  
   - Variable recoding, factor preparation, and missing data management.  
   - Automated document generation with **RMarkdown** for reproducibility.

2. **Descriptive analysis:**
   - Summary statistics (median [IQR], counts, percentages) and stratified tables.  
   - Exploratory visualizations and comparative summaries.  

3. **Statistical modeling:**
   - **Agreement analysis:** Cohen’s kappa / weighted kappa for inter-method concordance.  
   - **Paired comparisons:** McNemar’s test for binary paired outcomes.  
   - **Regression modeling:** logistic regression for binary diagnostic targets; proportional odds models for ordinal outcomes when applicable.  
   - **Performance metrics:** sensitivity, specificity, and confidence intervals relative to a reference standard.

4. **Results communication:**
   - Tables and figures produced with `ggplot2`, `kableExtra`, and `Hmisc`.  
   - Clean and reproducible reporting through **RMarkdown**.

## Main Packages
`tidyverse`, `ggplot2`, `readxl`, `irr`, `caret`, `Hmisc`, `kableExtra`


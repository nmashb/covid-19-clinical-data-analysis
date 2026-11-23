# COVID-19 Clinical Data Analysis

## Overview
This project explores clinical blood parameters from 103 COVID-19 patients to investigate differences between patients who recovered and those who did not recover. The analysis was conducted using R.

## Objectives
- Explore patient demographics and clinical characteristics.
- Investigate the association between ventilation status and patient outcomes.
- Compare selected blood parameters between recovered and non-recovered patients.
- Apply statistical testing and effect size analysis to interpret the findings.

## Dataset
The dataset consists of 103 patient records containing patient outcomes, demographic information, treatment details, ventilation status and six blood parameters:

- Red cell distribution width (RDW)
- Monocytes
- White blood cell count (WBC)
- Platelet count
- Lymphocyte count
- Neutrophils

## Methods
- Data cleaning and validation
- Exploratory data analysis (EDA)
- Data visualisation using ggplot2
- Categorical data analysis
- Wilcoxon rank-sum tests
- Benjamini-Hochberg correction for multiple testing
- Effect size calculation

## Key Findings
- RDW and platelet count showed statistically significant differences between recovered and non-recovered patients after adjustment for multiple comparisons.
- RDW and platelet count had moderate effect sizes.
- Ventilation status was associated with patient outcomes in this dataset, although the association may be influenced by underlying disease severity.

## Tools
- R
- dplyr
- ggplot2
- tidyr
- rstatix

## Limitations
This analysis is based on a relatively small dataset of 103 patients. Observational associations do not establish causation. Data inconsistencies in clinical dates may also limit the reliability of temporal interpretations.

## Disclaimer
This project is intended only for statistical analysis purposes and does not provide clinical advice.

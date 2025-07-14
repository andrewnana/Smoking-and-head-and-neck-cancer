##  Disclaimer
This analysis is intended for educational and research purposes only and has not been peer-reviewed. While efforts have been made to ensure the accuracy of the methods and results, the author does not guarantee the correctness or completeness of the analysis. The author bears no responsibility or liability for any errors, omissions, or outcomes resulting from the use of this material. Use at your own discretion.
## Head and Neck Cancer Survival Analysis in R
This project explores the impact of smoking history on the survival outcomes of patients with Head and Neck Squamous Cell Carcinoma (HNSCC), using real-world clinical data from 215 patients at the University of Texas MD Anderson Cancer Center.
## Background
Head and neck cancers remain a major global health issue. Key risk factors include:
- Tobacco use
- Alcohol consumption
- Human papillomavirus (HPV) infection

Treatment plans are typically based on tumor stage, patient age, and other medical criteria. This study specifically investigates how **smoking history** influences patient survival.

> Reference: Leemans et al., 2011
## Objectives
- Exploratory data analysis
- Provide a demographic table
- Visualize survival probabilities using Kaplan-Meier curves
- Construct a Directed Acyclic Graph (DAG) for the selection of covariates
- Fit and interpret Cox proportional hazards models
- Apply multiple imputation for handling missing data

## Packages Used
This project uses the following **R packages**:
- survival # Survival models
- dplyr # Data manipulation
- table1 # Summary tables
- survminer # Kaplan-Meier visualization
- readxl# Reading Excel files
- dagitty # Causal DAGs
- stargazer # Regression output formatting
- pheatmap # Heatmaps
- gtsummary # Publication-ready tables
- mice # Multiple imputation for missing data


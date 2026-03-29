# baousers-DataAnalysis_2026
This R script performs data cleaning, missing value analysis, multiple imputation, and outlier detection on a biomedical dataset. The main tasks include: removing irrelevant columns, separating factor variables, assessing missing data patterns, imputing missing values using MICE (Multivariate Imputation by Chained Equations), and visualizing outliers.

The dataset DataSet_No_Details.csv contains 105 columns and over 500 rows (original includes record_id, outcome, various hormones, indices, lipids, antioxidants, and factor variables). Many columns have missing values. The data appear to originate from a clinical or biological study, with variables such as hormone1–hormone14, lipids1–lipids5, antioxidant1–antioxidant5, and categorical factors like factor_eth, factor_h, factor_pcos, factor_prl.

The script was developed using RStudio 2025.09.2-418 (based on R-4.5.2). Required packages include skimr, dplyr, visdat, naniar, mice, ggplot2, and tidyr.

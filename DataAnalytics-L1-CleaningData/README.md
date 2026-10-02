# Level 1 Task 3: Data Cleaning Pipeline

## Overview
This project demonstrates an end-to-end data cleaning workflow applied to a raw, messy customer dataset containing structural errors, missing values, duplicates, and extreme outliers.

## Key Actions Taken
* **Duplicate Removal:** Identified and dropped duplicate customer records.
* **Type Conversion & Imputation:** Converted non-numeric values in `Age` to missing values, imputed missing numerical entries (`Age`, `Annual_Income`, `Total_Spend`) using column medians.
* **Categorical Standardization:** Mapped inconsistent text values (`M`, `male`, `F`, `female`) to standardized labels (`Male`, `Female`) and imputed missing values using the mode.
* **Outlier & Anomaly Removal:** Corrected negative spending entries and replaced extreme income anomalies before imputation.
* **Date Parsing:** Standardized mixed date string formats into standard ISO date formats (`YYYY-MM-DD`).

## Deliverables
* `data_cleaning.ipynb`: Jupyter Notebook containing the data quality audit and cleaning script.
* `messy_dataset.csv`: Generated raw dataset containing dirty data edge cases.
* `cleaned_dataset.csv`: Final sanitized, analysis-ready dataset.
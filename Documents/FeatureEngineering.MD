# Feature Engineering

## Related Notebook

**Notebook:** `02_feature_engineering.ipynb`

## Purpose

The purpose of feature engineering is to create additional predictive variables that improve readmission prediction performance.

## Input File

`admission_cohort.csv`

## Features Created

- prior_admissions
- admission_month
- admission_dayofweek
- admission_hour
- weekend_admission
- elderly_patient
- long_stay
- complex_case
- high_severity
- high_mortality_risk

## Missing Value Handling

### Numerical Features
Median imputation

### Categorical Features
Unknown category replacement

## Output File

`model_dataset.csv`

## How to Run

Run `02_feature_engineering.ipynb`. The notebook creates `model_dataset.csv`.

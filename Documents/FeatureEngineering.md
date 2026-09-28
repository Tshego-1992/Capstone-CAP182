## Feature Engineering
Notebook: feature_engineering.ipynb

## Purpose
The purpose of feature engineering is to create additional predictive variables that improve readmission prediction performance.

## Input file
admission_cohort.csv

## Features created

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

## Missing value handling
## Numerical features
Median imputation
## Categorical features
Unknown category replacement

## Output file
model_dataset.csv

## How to run
Run feature_engineering.ipynb. The notebook creates model_dataset.csv.

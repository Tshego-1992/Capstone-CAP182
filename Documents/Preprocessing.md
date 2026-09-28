## Preprocessing

Notebook: preprocessing.ipynb
This notebook performs all preprocessing tasks required before feature engineering and model development.

## Purpose
The purpose of preprocessing is to prepare the MIMIC-IV data for machine learning by loading, cleaning, transforming, and merging datasets into a single admission-level dataset.

## Input Files
- patients.csv
- admissions.csv
- services.csv
- drgcodes.csv
- transfers.csv

## Preprocessing Steps
1. Load the datasets.
2. Remove duplicate records.
3. Convert admission and discharge timestamps to datetime format.
4. Calculate length of stay.
5. Create a 30-day readmission target variable.
6. Aggregate service information.
7. Aggregate DRG information.
8. Aggregate transfer information.
9. Merge all datasets into a single table.

## Output File

admission_cohort.csv

## How to Run

Run preprocessing.ipynb. The notebook creates admission_cohort.csv

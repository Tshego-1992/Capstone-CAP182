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
5. Create a 30-day readmission target variable:    
   Admissions were sorted by patient and admission date. The next hospital admission for each patient was identified and the number of days between discharge and the next admission was calculated. Patients who returned within 30 days were assigned: readmitted_30d = 1 .  All remaining patients were assigned: readmitted_30d = 0. This variable became the prediction target for the machine learning models.
6. Data Leakage Prevention:
During target creation, two temporary variables were generated:
next_admission
days_to_next
These variables contain future information and were used only to calculate the readmission target variable.
After the target variable was created, these columns were removed from the modelling dataset because they would not be available at the point when a prediction is made and would introduce data leakage.


7. Aggregate service information:  
   The services dataset contained multiple service records per admission. These records were aggregated into:
service_count
primary_service
This allowed the model to use information about the number of clinical services involved in the patient's care as well as the primary service responsible for treatment.  
8. Aggregate DRG information.   
9. Aggregate transfer information.   
 10. Merge all datasets into a single table.   

## Output File

admission_cohort.csv

## How to Run

Run preprocessing.ipynb. The notebook creates admission_cohort.csv

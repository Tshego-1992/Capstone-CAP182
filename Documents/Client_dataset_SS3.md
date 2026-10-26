CLIENT DATASET

The admissions dataset (request1_admissions_discharge.csv) was selected as the primary dataset because it contains the target variable Readmitted_30_Days, which indicates whether a patient was readmitted within 30 days of discharge.

The remaining datasets are linked using either Patient_ID or Admission_ID and provide additional predictive information that may improve model performance.

Target Variable: 0 = Not Readmitted Within 30 Days, 1 = Readmitted Within 30 Days 
Dataset size, class distribution and class imbalance are analysed and printed in the DATASET LOADING component of the code

The CSV files used to source the data are ideal for this machine learning model(logistic regression) because they provide a structured tabular format that can be easily loaded into Pandas dataFrames for preprocessing, feature engineering and modelling.
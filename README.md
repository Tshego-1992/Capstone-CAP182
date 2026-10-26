# STADIOcare Capstone data science project

## 1. Repository Structure
### Datasets  
  ─ Dataset.MD  
      (MIMIC IV public data for SS1 and SS2)  
  ─ Client data for SS3:  
      - request1_admissions_discharge.csv  
      - request2_patient_demographics.csv  
      - request3_medical_history_clinical.csv  
      - request4_medication_treatment.csv  
      - request5_followup_outpatient.csv  
      - request6_claims_billing.csv  
      - request7_procedures.csv  
### Documents
SS1 & SS2:  
  ─ Preprocessing.MD  
  ─ FeatureEngineering.MD  
  ─ Model1.MD  
  ─ Model2.MD  
  ─ Model1Performance.MD  
  ─ Model2Performance.MD  
  ─ Comparison.MD  
  ─ Requirements.txt  
  ─ STADIOcare data request  
SS3:  
  ─ Client_dataset_SS3.md    

### Experiments
  ─ (alternative public data source that can be used to rebuild the project)  
### Notebooks
  ─ preprocessing.ipynb  
  ─ feature_engineering.ipynb  
  ─ model1_logistic_regression.ipynb  
  ─ model2_random_forest.ipynb  
  ─ model_performance_comparison.ipynb  
  ─ statistical_analysis.ipynb   
  ─ SS3_PartB.ipynb  
### Video 
  ─ Link to the presentation video: https://stadiomultiversity-my.sharepoint.com/:f:/g/personal/26304837_stadio_ac_za/IgDs36_M24UmRoeF00lnDsEaAdLCVCNqmNVPdbgjrmZ0XJI?e=KNah6c  
### Reports
  ─ CAP182 SS2 PartA (Literature review)  
  [Click here to view the file](Reports/Tshegofatso_Mogomotsi_26304837_CAP182_SS2_PartA.pdf)  

  ─ CAP182 SS2 PartD (Model recommendations)  
  [Click here to view the file](Reports/Tshegofatso_Mogomotsi_26304837_CAP182_SS2_PartD.pdf)   
### Results
  ─ _model_performance_comparison.xlsx  
  ─ confusion_matrix_comparison.png   
  ─ model1_predictions_logistic_regression.xls  
  ─ model2_predictions_random_forest.xls  
### Statistical analysis  
  ─ model_performance_comparison.xlsx   
  ─ confidence_intervals.xlsx   
  ─ _mcnemar_test_results.xlsx    
  ─ roc_curve_comparison.png  
### Visualisations
  ─ confusion_matrix_comparison.png   
  ─ confusion_matrix_model1.png  
  ─ confusion_matrix_model2.png  
  ─ roc_curve_comparison.png   

## 2. Problem statement - PartB
The aim of this project is to build a predictive machine learning model that will predict whether a patient would be readmitted within 30 days of discharge at STADIOcare hospital. This will support proactive patient management and reduce healthcare pressures since STADIOcare has been experiencing operational inefficiencies, increasing staffing pressures, rising patient readmission rates, and growing financial scrutiny from medical schemes. 

## 3. Motivation - PartA

STADIOcare is currently experiencing a few challenges. Firstly, there's pressure on profitability as operational costs increase faster than tariffs. This means that the hospital must improve efficiency and how they use resources rather than relying on price increases to maintain financial performance. Secondly, the hospital faces a nursing shortage seen through the increasing labour costs, staff burnout, staff loss, and inefficient manual rostering processes. In addition, the hospital treats an older and very sick patient population whose chronic conditions contribute to longer hospital stays and higher rates of readmission after they are discharged.

Addressing these challenges is important because they directly affect hospital profitability, patient outcomes, employee wellbeing, and the sustainability of the hospital. If the hospital fails to respond effectively it could experience higher operational costs, increased staff turnover, reduced patient satisfaction, and greater financial risk. 

A machine learning model can offer an opportunity to analyse the hospital's large volumes of historical data to support decision making based on evidence. Predictive analytics can assist with forecasting patient demand and optimising nurse allocations. 

Therefore, this project is valuable for generating evidence that can support operational optimisation, improve resource allocation, enhance patient outcomes, and strengthen financial sustainability by applying data science techniques within the STADIOcare’s environment.

## 4. RAAIDD Log - PartE

| Category | ID | Description |
|-----------|----|-------------|
| Risk | R1 | Data quality issues could exist in the the hospital’s admissions, billing, scheduling, HR, clinical systems such as missing values, inconsistent data formating and duplicate records. |
| Risk | R2 | Delays in getting the data I’ll need from multiple business units can impact project timelines (assignment submission timelines) and analysis tasks. |
| Risk | R3 | Privacy and regulatory requirements may limit access to certain patient-level information needed for analysis unless if I opt for dummy data. |
| Action | A1 | I’ll need to collect datasets from the hospital’s admissions, billing, scheduling, HR, dispatch, radiology and patient experience systems |
| Action | A2 | Conduct data quality assessment on all datasets received. |
| Action | A3 | Integrate datasets into a consolidated dataset so that I can do cross-functional analysis |
| Action | A4 | I’ll need to clearly prioritise business use cases including readmission prediction, hospital occupancy forecasting, workforce optimisation and anomaly detection for billing. |
| Action | A5 | Appropriate data science models will need to be developed and evaluated for the hospital’s business problems. |
| Action | A6 | Present findings and recommendations to business stakeholders by using a report supported by visuals |
| Assumption | AS1 | Historical data is available to assess STADIOcare’s problems. |
| Assumption | AS2 | There’ll be unique identifiers exist that allow patient, billing, scheduling and operational data to be linked. |
| Issue | I1 | Some data sources may contain incomplete records, requiring cleansing and validation before modelling can begin. |
| Decision | D1 | The project will focus on data science opportunities that align directly with STADIOcare's strategic priorities of improving patient outcomes, operational efficiency and financial performance. |
| Dependency | DP1 | The data integration activities will depend on successful access and extraction of data from sources. |
| Dependency | DP2 | The development of models depends on completion of data cleansing and feature engineering. |
| Dependency | DP3 | Business recommendations depend on completion of model evaluation and stakeholder validation. |

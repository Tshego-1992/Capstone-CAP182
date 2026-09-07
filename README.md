# Capstone data science project

## 1. Repository Structure

### Datasets
Contains raw and processed datasets.
### Models
Contains trained machine learning models
### Experiments
Contains experiment work and experiment notes.
### Results
Contains model evaluation results, metrics, comparison reports etc.
### Visualisations
Contains charts generated and other visual scripts.
### Documents
Contains assignment documents, reports and project documentation.
### Comparison scripts
Scripts used to compare machine learning models and experiments.
### Statistical helper scripts
Scripts used to perform statistical analysis such as distribution analysis or hypothesis testing

## 2. Motivation - PartA
The industry of private health care operates in an environment that constantly challenging and healthcare institutions must balance quality patient care with financial stability long term. STADIOcare generates and stores large volumes of operational, clinical, financial, and workforce data through systems that handle admissions, billing imaging, dispatch and human resources. However, the hospital struggles to convert this information into actionable insights that can support effective decision making.
According to the client briefing document, STADIOcare is currently experiencing a few significant challenges. Firstly, margin compression continues to put pressure on profitability as operational costs increase faster than tariffs. This means that the hospital must improve efficiency and resource utilisation rather than relying on price increases to maintain financial performance. Secondly, the organisation faces a nursing shortage seen through the increasing labour costs, staff burnout, staff loss, and inefficient manual rostering processes. In addition, the hospital treats an older and very sick patient population whose chronic conditions contribute to longer hospital stays and higher rates of readmission after they are discharged.
The hospital is also experiencing increased scrutiny from medical schemes that monitor billing activities. Unusual billing patterns can trigger costly audits and investigations which creates additional financial and compliance risks. Another concern is that the hospital's information is kept across several independent systems that were not designed to work together which makes it difficult to obtain a comprehensive view of operations and identify trends that could support strategic decisions.
Addressing these challenges is important because they directly affect hospital profitability, patient outcomes, employee wellbeing, and the sustainability of the hospital. Failing to respond effectively could result in higher operational costs, increased staff turnover, reduced patient satisfaction, and greater financial risk. The ability to identify patterns and trends within existing data could provide management with valuable insights to improve operational performance.
Data science methods offer an opportunity to analyse large volumes of historical data to support decision making based on evidence. Predictive analytics can assist with forecasting patient demand, optimising nurse allocation, identifying patients at risk of readmission, and detecting unusual billing patterns that require further investigation. If we integrate information from the hospital’s multiple systems, then management can gain a more complete understanding of the hospital’s business performance and identify opportunities for improvement.
Therefore, this project aims to generate evidence that may support operational optimisation, improve resource allocation, enhance patient outcomes, and strengthen financial sustainability by applying data science techniques within the STADIOcare’s environment.


## 3. Problem statement - PartB


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

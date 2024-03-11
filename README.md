## Hospital Readmission Prediction
### Research Question
Is Diabetes a predictor of Hospital Readmission ?

### Dataset Description
![image](https://github.com/RiddhiTripathi/Hospital-Readmission-Prediction/assets/36181595/321c8649-28a9-4e59-8683-c008072ca695)

### Data Preprocessing
As a part of data cleaning, Dummy variables were created for the attributes having categorical data.
The dependent variable readmitted was converted into 0 (No) and 1 (Yes).
For the following variables dummy variable were created :
Glucose Test 	
A1C test 
Change
Readmitted
Age 
Diabetes Med
Medical Speciality
Diag_1
Diag_2
Diag_3

#### Predictive Model Determination
a) What is the outcome of interest (Y variable)?

Will the patient be readmitted to the Hospital or not? The Dataset contains a column: 'readmitted'.

b) What are covariates or predictors (X variables) you plan on including in your Model?

The following are the predictors: 'age', 'time_in_hospital', 'n_lab_procedures', 'n_procedures’,
‘n_medications', 'n_outpatient', 'n_inpatient', 'n_emergency', 'medical_specialty', 'diag_1', 'diag_2', 'diag_3',
'glucose_test', 'A1Ctest', 'change', 'diabetes_med'.

c) What statistical model(s) do you plan on using?

Logistic Regression (Logit function) and Decision Tree for Feature Engineering.

### Exploratory Data Analysis
#### Correlation Matrix
![image](https://github.com/RiddhiTripathi/Hospital-Readmission-Prediction/assets/36181595/05f09c6f-1858-4da5-81dd-346732e36aca)

### Statistical Analysis
#### Logistic Regression
![image](https://github.com/RiddhiTripathi/Hospital-Readmission-Prediction/assets/36181595/6211b51a-e3c1-4ef6-ad5c-406ec6c8ea86)

#### Step Function
![image](https://github.com/RiddhiTripathi/Hospital-Readmission-Prediction/assets/36181595/2acb7474-4dfe-4a4d-be2c-faf60f54d1d8)

#### Decision Trees
![image](https://github.com/RiddhiTripathi/Hospital-Readmission-Prediction/assets/36181595/9e7a3968-6739-4a76-997d-f80915b1c41e)

#### Confusion Matrix
###### Logistic Regression
![image](https://github.com/RiddhiTripathi/Hospital-Readmission-Prediction/assets/36181595/1d630be6-6d8b-4c57-a75e-c56c8a027494)

###### Decision Tree
![image](https://github.com/RiddhiTripathi/Hospital-Readmission-Prediction/assets/36181595/7520ce27-6905-44b4-9d1d-cf6dd61cf2fb)

### Conclusion
1.Most patients do not undergo Glucose or A1C Test and do not get diagnosed with Diabetes.Hence, It gets difficult to determine whether diabetic patients are at higher risk of readmission or not.

2.Conversely, data says that people already taking diabetes medication have been readmitted.

3.Most significant predictor variables: n_inpatient, n_outpatient, diabetes_med, n_emergency, time_in_hospital, age

4.Hospitals should follow up on the diagnosis and glucose test reports for patients already under diabetes medication to further analyze whether the patients are at higher risk of readmission.

5.Diabetes cannot indicate higher readmission rates.









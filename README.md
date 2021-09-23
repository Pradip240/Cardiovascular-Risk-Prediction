# Cardiovascular-Risk-Prediction
## Introduction:

Predicting coronary heart disease in advance helps raise awareness for the disease. Preventive measurements like changing diet plans and exercise can slow down the progression of CHD.
Early prediction can result in early diagnosis. So, we can treat the disease at an early stage and avoid more invasive treatment.


## Problem Statement:
The goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD).

## Data Description:
The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes. Variables Each attribute is a potential risk factor. There are both demographic, behavioural, and medical risk factors

### Demographic:
•	**Sex:** male or female("M" or "F")

•	**Age:** Age of the patient

### Behavioral:

•	**is_smoking:** whether or not the patient is a current smoker ("YES" or "NO")

•	**Cigs Per Day:** the number of cigarettes that the person smoked on average in one day

### Medical(History):

•	**BP Meds:** whether or not the patient was on blood pressure medication

•	**Prevalent Stroke:** whether or not the patient had previously had a stroke

•	**Prevalent Hyp:** whether or not the patient was hypertensive

•	**Diabetes:** whether or not the patient had diabetes (Nominal) Medical(current)

•	**Tot Chol:** total cholesterol level

•	**Sys BP:** systolic blood pressure

•	**Dia BP:** diastolic blood pressure

•	**BMI:** Body Mass Index

•	**Heart Rate:** heart rate

•	**Glucose:** glucose level

•	**CHD:** 10-year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”)


## Approach:-
### Data preparation:
•	Removed null values from the dataset

•	Removed duplicate entries

•	Used SMOTE and random under sampling to get a balanced dataset

### Feature engineering:
•	Extracted feature ‘Hypertension’ from systolic and diastolic blood pressure data

•	Extracted feature ‘Diabetese severity’ from diabetes and glucose column

•	Constructed new feature ‘Smoking Factor’ from number of cigarettes consumption


## Conclusion:-

Using XGBoost and finetuning parameters with grid search and cross-validation I got a Recall of 92%.

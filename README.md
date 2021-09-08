# Cardiovascular-Risk-Prediction
The dataset provided is from cardiovascular study on residents of the town of Framingham, Massachusetts.

The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD).

The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes. Variables Each attribute is a potential risk factor. There are both demographic, behavioural, and medical risk factors

The description of the data is given below:

Demographic:

Sex: male or female("M" or "F")

Age: Age of the patient

Behavioral:

is_smoking: whether or not the patient is a current smoker ("YES" or "NO")

Cigs Per Day: the number of cigarettes that the person smoked on average in one day

Medical(History):

BP Meds: whether or not the patient was on blood pressure medication

Prevalent Stroke: whether or not the patient had previously had a stroke

Prevalent Hyp: whether or not the patient was hypertensive

Diabetes: whether or not the patient had diabetes (Nominal) Medical(current)

Tot Chol: total cholesterol level

Sys BP: systolic blood pressure

Dia BP: diastolic blood pressure

BMI: Body Mass Index

Heart Rate: heart rate

Glucose: glucose level

10-year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”)

Conclusion:-

Starting with loading the data so far we have done EDA , null values treatment, encoding of categorical columns, feature selection and then model building.

In all of these models our accuracy revolves in the range of 75 to 97%.

And there is no such improvement in accuracy score even after hyperparameter tuning.

So the accuracy of our best model is 97% for XGboost which can be said to be good for this large dataset.

This performance could be due to various reasons like: no proper pattern of data, lack of data, not enough relevant features but maybe with enough data we can train out model even better.

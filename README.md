# Type2DiabetesPredictionUsingML

**Inspiration:**  Can you build a machine learning model to accurately predict whether or not the patients in the dataset have diabetes or not?

**Project:** Prediction of Type 2 Diabetes using Machine Learning
Kaggle datasets: Diabetes Prediction Dataset & PIMA Indian Diabetes Dataset
ML Algorithms like XGBoost, Random Forest, Decision Tree and Logistic Regression were utilized for building predictive models

**1. Diabetes Prediction Dataset:**

The Diabetes prediction dataset is a collection of medical and demographic data from patients, along with their diabetes status (positive or negative). This dataset can be used to build machine learning models to predict diabetes in patients based on their medical history and demographic information. This can be useful for healthcare professionals in identifying patients who may be at risk of developing diabetes and in developing personalized treatment plans. Additionally, the dataset can be used by researchers to explore the relationships between various medical and demographic factors and the likelihood of developing diabetes.The diabetes_prediction_dataset.csv file contains medical and demographic data of patients along with their diabetes status, whether positive or negative. The Dataset can be utilized to construct machine learning models that can predict the likelihood of diabetes in patients based on their medical history and demographic details.

**Dataset Description:**

**Gender** - the biological sex of the individual, which can have an impact on their susceptibility to diabetes. There are three categories in it male,female and other.
**Age** - Age ranges from 0-80 in dataset. diabetes is more commonly diagnosed in older adults.
**Hypertension** - a medical condition in which the blood pressure in the arteries is persistently elevated. It has values a 0 or 1 where 0 indicates they don't have hypertension and for 1 it means they have hypertension.
**Heart disease** - a medical condition that is associated with an increased risk of developing diabetes. It has values a 0 or 1 where 0 indicates they don't have heart disease and for 1 it means they have heart disease.
**Smoking history** - It is a risk factor for diabetes and can exacerbate the complications associated with diabetes. There are 5 categories in the dataset i.e not current,former,No Info,current,never and ever.
**Body Mass Index (BMI)** - measurement of body fat based on weight and height. Higher BMI values are linked to a higher risk of diabetes. The range of BMI in the dataset is from 10.16 to 71.55. BMI less than 18.5 is underweight, 18.5-24.9 is normal, 25-29.9 is overweight, and 30 or more is obese.
**Hemoglobin A1c (HbA1c) level** - measurement of a person's average blood sugar level over the past 2-3 months. Higher levels indicate a greater risk of developing diabetes. Mostly more than 6.5% of HbA1c Level indicates diabetes.
**Blood glucose level** - the amount of glucose in the bloodstream at a given time. High blood glucose levels are a key indicator of diabetes.
**Diabetes** - the target variable being predicted, with values of 1 indicating the presence of diabetes and 0 indicating the absence of diabetes.

**2. PIMA Indian Diabetes Dataset**

Pima Indian Diabetes Dataset is one of the ideal datasets for evaluating machine learning algorithms for predicting diabetes (UCI Machine Learning Repository, 1998). This data set has been used by many researchers in predictive analyses.
The dataset consists of data used for diabetes research on women of Pima Indian heritage, aged 21 and over, living in Phoenix, the 5th largest city of the State of Arizona in the USA. The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

**Dataset Description:**

**Pregnancies**: Number of times pregnant
**Glucose**: Plasma glucose concentration over 2 hours in an oral glucose tolerance tes
**BloodPressure**: Diastolic blood pressure (mm Hg)
**SkinThickness**: Triceps skinfold thickness (mm)
**Insulin**: 2-Hour serum insulin (mu U/ml)
**BMI**: Body mass index (weight in kg/(height in m)^2)
**Pedigree**: Diabetes pedigree function - A function that scores likelihood of diabetes based on family history.
**Age**: Age in years
**Outcome**: Class variable (0: the person is not diabetic or 1: the person is diabetic)


# diabetes-predictor-and-precautions

#Project Overview
The "DB Predictions and Precautions" project utilizes machine learning techniques to predict diabetes outcomes and provide corresponding precautionary measures. The project integrates multiple machine learning models to enhance prediction accuracy and offers a user-friendly interface for inputting data and receiving predictions along with precautionary advice.

#Dataset
The dataset used in this project is based on the well-known Pima Indians Diabetes Database. The dataset includes the following features:
Pregnancies: Number of times the patient was pregnant.
Glucose: Plasma glucose concentration after 2 hours in an oral glucose tolerance test.
BloodPressure: Diastolic blood pressure (mm Hg).
SkinThickness: Triceps skinfold thickness (mm).
Insulin: 2-Hour serum insulin (mu U/ml).
BMI: Body mass index (weight in kg/(height in m)^2).
DiabetesPedigreeFunction: Diabetes pedigree function.
Age: Age of the patient (years).
Outcome: Class variable (0 if non-diabetic, 1 if diabetic).
Additional Processing
Missing values in certain columns are imputed using the mean of the available data.
A synthetic column, DiabetesType, is created to classify the type of diabetes or lack thereof.

#Models Used
The following machine learning models were implemented and evaluated:
Logistic Regression (LR)
K-Nearest Neighbors (KNN)
Support Vector Classifier (SVC)
Decision Tree (DT)
Random Forest (RF)
Gradient Boosting Classifier (GBC)

#Model Performance
The models were evaluated based on their accuracy on the test set:
LR Test Accuracy: 72.73%
KNN Test Accuracy: 63.64%
SVC Test Accuracy: 72.08%
DT Test Accuracy: 58.44%
RF Test Accuracy: 73.38%
GBC Test Accuracy: 64.29%

#Precautions
The project includes a feature to provide precautionary measures based on the predicted type of diabetes:
Type 1 Diabetes: Recommendations for managing type 1 diabetes.
Type 2 Diabetes: Guidelines for preventing complications associated with type 2 diabetes.
Gestational Diabetes: Precautions for managing gestational diabetes during pregnancy.
No Diabetes (None): General health advice to maintain a healthy lifestyle and reduce the risk of developing diabetes.

#User Interface
A graphical user interface (GUI) is implemented using Tkinter, allowing users to input their health metrics and receive a diabetes type prediction along with relevant precautions.

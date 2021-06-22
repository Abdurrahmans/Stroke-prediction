# Stroke-prediction
## Problem
A stroke occurs when a blood vessel in the brain ruptures and bleeds, or when there’s a blockage in the blood supply to the brain. The rupture or blockage prevents blood and oxygen from reaching the brain’s tissues. Without oxygen, brain cells and tissue become damaged and begin to die within minutes.
## Technology Stack
python language
## Dataset
The dataset can be found in the repository or can be downloaded from Kaggle

The dataset contains 5110 real world observations and 10 different attributes:

1. gender: "Male", "Female" or "Other"
2. age: age of the patient
3. hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
4. heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
5. ever_married: "No" or "Yes"
6. Residence_type: "Rural" or "Urban"
7. avg_glucose_level: average glucose level in blood
8. bmi: body mass index
9. smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
10 stroke: 1 if the patient had a stroke or 0 if not
## Working of System
Logistic Regression
KNeighborsClassifier
RandomForestClassifier

1. Input: The dataset
2. Output: Classification into 0 (no stroke) or 1 (stroke)
Steps:

1. Loading the dataset and required packages
2. Pre-processing data to convert character to numeric and to remove null values
3. Dividing the dataset into training set and test set
4. Importing the Logistic Regression classifier and creating its object.
5. Fitting the training data to the classifier
6. Predicting the classifier output against the test data
7. Comparing the predicted results with the test results to get the accuracy

## Accuracy
Logistic Regression: 0.7612735815975875
KNeighborsClassifier: 0.9889894101970685
RandomForestClassifier: 0.9988779016761343

# Loan-eligibility-prediction-project

Loan Eligibility Prediction Project

Objective:

The goal of this project is to predict the eligibility of loan applicants based on various features using machine learning models.

Data:

Dataset: The project uses a dataset named loan.csv.

Features: Includes variables such as Gender, Married, Dependents, Education, Self_Employed, ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, 

Credit_History, and Property_Area.

Target Variable: The target variable is Loan_Status, indicating whether a loan application was approved or not.

Data Preprocessing:

Missing Values: Handled missing values using imputation. For example, the mode was used for categorical variables like Gender and Married.

Feature Engineering: Created new features such as TotalIncome and its logarithmic transformation to reduce skewness.

Encoding: Applied label encoding to categorical variables.

Scaling: Used standard scaling for feature normalization.

Model Training:

The dataset was split into training and testing sets. Several machine learning algorithms were implemented and evaluated:



Random Forest Classifier:

Achieved an accuracy of around 0.78.

Naive Bayes Classifier:

Achieved a similar performance with an accuracy score.

Decision Tree Classifier:

Performance was measured, and accuracy was recorded.

K-Nearest Neighbors Classifier:

Provided an accuracy of approximately 0.79.

Evaluation:

The models were evaluated based on accuracy metrics using the test data.



Conclusion:

The project effectively demonstrates the use of various machine learning models to predict loan eligibility, highlighting the importance of data preprocessing, 

feature engineering, and model evaluation in achieving reliable predictions.


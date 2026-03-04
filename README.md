# Loan-Approval-Prediction
Built a Loan Approval Prediction model using Logistic Regression and Decision Tree, handling imbalanced data with SMOTE and focusing on precision, recall, and F1-score to improve risk detection.

# Project Overview:
This project builds a Binary Classification Machine Learning model to predict whether a loan application should be Approved or Rejected based on applicant financial and demographic information.
The goal is to simulate a real-world banking scenario where institutions want to reduce credit risk while automating loan approval decisions.

# Objective:

Predict loan approval status (Approved / Rejected)

Handle missing values in real-world financial data

Encode categorical variables

Address imbalanced dataset issues

Compare classification models

Evaluate using precision, recall, and F1-score (not just accuracy)

# Dataset:

Source: Kaggle – Loan Approval Prediction Dataset ( https://www.kaggle.com/datasets/premptk/loan-approval-prediction-dataset )

# Technologies Used:

Python

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

imbalanced-learn (SMOTE)

# ⚙️ Project Workflow:

Data Loading

Data Cleaning (Handling Missing Values)

Encoding Categorical Variables

Train-Test Split

# Model Training:

Logistic Regression

Decision Tree

Handling Imbalanced Data using SMOTE

# Model Evaluation using:

Precision

Recall

F1-score

Confusion Matrix

# 📈 Model Performance

Model               	             Recall (Rejected)	           Accuracy

Logistic Regression	                    0.42	                     0.79

Decision Tree	                          0.42	                     0.68

Logistic + SMOTE	                      0.44                       0.77

Decision Tree + SMOTE	                  0.47	                     0.76

# 🧠 Key Insights

Logistic Regression achieved the highest overall accuracy (79%).

Decision Tree with SMOTE improved detection of risky applicants (Recall = 47%).

SMOTE slightly improved minority class performance.

Accuracy alone is not sufficient for imbalanced classification problems.

Recall is critical in financial risk prediction.

# 🏦 Business Understanding

In real banking systems:

Approving a risky applicant can cause financial loss.

Rejecting a safe applicant can affect customer trust.

This project highlights the importance of balancing precision and recall when making risk-based decisions.

# 🚀 Future Improvements

Apply advanced models like Random Forest or XGBoost

Perform feature engineering

Tune classification threshold

Use cross-validation

Perform hyperparameter tuning



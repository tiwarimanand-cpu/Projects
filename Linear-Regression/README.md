Medical Cost Prediction using Linear Regression

This project predicts medical insurance charges based on individual health attributes using a Linear Regression model in Python.

Problem Statement

The goal is to estimate medical insurance costs using real-world health data.

Dataset

Source: Kaggle Insurance Dataset

Input Features:

Age

BMI

Number of Children

Smoker (0 = No, 1 = Yes)

Region

Target Variable:

Charges

Workflow

Loaded dataset using Pandas

Handled missing and categorical values

Split data into training and testing sets

Trained Linear Regression model using Scikit-learn

Generated predictions and evaluated using R² score

Results

The model produced reasonable predictions on unseen data.

Technologies

Python, Pandas, NumPy, Matplotlib, Scikit-learn

How to Run
pip install -r requirements.txt
jupyter notebook medical_cost_prediction.ipynb
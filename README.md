# Airline_recommendation

This project aims to build a machine learning model that predicts whether a customer would recommend an airline based on various flight-related features and customer feedback. The goal is to assist airlines in improving customer satisfaction by identifying key factors influencing positive recommendations.

📁 Project Structure
Airline_recommendation.ipynb: The main Jupyter Notebook containing the end-to-end pipeline—from data exploration and preprocessing to model building, evaluation, and conclusion.

🔍 Overview
The notebook covers:

Exploratory Data Analysis (EDA): Insightful visualizations and correlation heatmaps to understand relationships between features.

Data Preprocessing:

Handling missing values

Encoding categorical variables

Feature scaling

Model Training:

KNN 

Gradient Boosting Classifier

Logistic Regression

Random Forest

Decision Tree

XGBoost

Support Vector Machine (SVM)

Model Evaluation:

Accuracy, Precision, Recall, F1-score

Confusion Matrices

Cross-validation

📊 Dataset
The dataset includes airline passenger feedback data with features such as:

overall	seat_comfort	cabin_service	food_bev	entertainment	ground_service	value_for_money 


Target: Likelihood of recommending the airline

The target variable is binary: 0 = Not Recommended, 1 = Recommended

✅ Key Findings
SVC and XGBoost performed best, achieving the highest accuracy and F1-score.

🧰 Technologies Used
Python

Pandas, NumPy

Scikit-learn

XGBoost

Matplotlib, Seaborn

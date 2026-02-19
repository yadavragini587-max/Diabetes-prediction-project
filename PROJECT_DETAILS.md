Project Overview

This project aims to predict medical insurance charges based on demographic and health-related factors using Machine Learning techniques.

The project follows a complete end-to-end data science workflow including:

Data Cleaning

Exploratory Data Analysis (EDA)

Feature Engineering

Model Building

Model Evaluation

Model Saving

🎯 Problem Statement

Medical insurance companies need to estimate charges for customers based on various factors such as age, BMI, smoking habits, etc.

This project builds a regression model to accurately predict insurance charges.

📊 Dataset Information

The dataset contains the following features:

Feature	Description
age	Age of the person
sex	Gender (male/female)
bmi	Body Mass Index
children	Number of dependents
smoker	Smoking status
region	Residential region
charges	Medical insurance cost (Target Variable)
🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Pickle

🔍 Project Workflow
1️⃣ Data Loading

Loaded dataset using Pandas.

2️⃣ Exploratory Data Analysis (EDA)

Distribution of insurance charges

Correlation heatmap

Impact of smoking on charges

3️⃣ Data Preprocessing

Label Encoding for categorical variables

Train-Test Split

Feature Scaling (for Linear Regression)

4️⃣ Model Building

Two regression models were trained:

Linear Regression

Random Forest Regressor

5️⃣ Model Evaluation

Models were evaluated using:

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

RMSE

R² Score

Random Forest performed better compared to Linear Regression.

📈 Key Insights

Smoking is the most significant factor affecting insurance charges.

Age has strong positive correlation with medical cost.

BMI moderately impacts charges.

Random Forest gives higher prediction accuracy.

💾 Model Deployment Ready

The trained model is saved as:

insurance_model.pkl

scaler.pkl

These files allow reuse of the trained model without retraining.

Project Structure
Insurance-Cost-Prediction/
│
├── data/
│   └── insurance.csv
│
├── notebook/
│   └── insurance_analysis.ipynb
│
├── model/
│   ├── insurance_model.pkl
│   └── scaler.pkl
│
├── README.md
└── requirements.txt

🚀 Future Improvements

Hyperparameter tuning

Streamlit Web App Deployment

Power BI Dashboard

Advanced Feature Engineering

Cross-validation improvement

👩‍💻 Author

Ragini Yadav
B.Sc Biotechnology
Aspiring Data Scientist

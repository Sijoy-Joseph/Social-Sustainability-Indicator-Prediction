📌 Project Title

Social Sustainability Indicator Prediction Using Machine Learning

👤 Author

Name: Sijoy Joseph

🧠 Problem Statement

Predicting social sustainability indicators is complex due to multidimensional socio-economic and geographic data. This project applies machine learning to predict the "value" of social indicators using global socio-economic features, aiding policy makers and stakeholders in decision-making.

🎯 Objective

To build and evaluate multiple machine learning regression models to accurately predict the social sustainability indicator value using cleaned, encoded, and feature-selected data.

📚 Data Description

Source: World Bank Social Sustainability Global Database

Original Columns: 21

Target Variable: value (Social Sustainability Indicator Value)

Data Type: Mixed (Numerical + Categorical)

🔍 Project Steps

1️⃣ Data Preprocessing

Imputation of missing values (numerical: median, categorical: mode)

Outlier detection and removal using IQR

Skewness checked and visualized before and after cleaning

2️⃣ Exploratory Data Analysis (EDA)

Distribution and boxplots for numerical columns

Correlation heatmap for numerical features

Count plots for all categorical features

3️⃣ Feature Engineering

One-hot encoding of categorical variables with integer type

Ensured all model inputs are numeric

4️⃣ Feature Selection

Used SelectKBest with f_regression to choose top 10 predictors

5️⃣ Model Training and Evaluation

Split data into training and testing sets

Applied feature scaling (StandardScaler)

Models Trained:

Linear Regression

Random Forest Regressor

Gradient Boosting Regressor

AdaBoost Regressor

MLP Regressor

Support Vector Regressor (SVR)

Metrics used: MAE, MSE, RMSE, R² Score

6️⃣ Hyperparameter Tuning

GridSearchCV used to tune Random Forest parameters

7️⃣ Model Saving

Best model (Random Forest) saved using joblib

8️⃣ Prediction on Unseen Data

Predicted values using test split to simulate unseen data scenario

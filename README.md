# QSAR Fish Toxicity Prediction using Statistical Machine Learning

## 📌 Project Overview
This project was completed as part of the course **Statistical Methods of Machine Learning**
The goal is to predict **acute aquatic toxicity (LC50)** for the fish *Pimephales promelas*
using QSAR descriptors and statistical learning techniques.
The project was initially implemented using R and has now been extended with a Python implementation to 
provide an additional approach to data analysis, model development and evaluation.

## 📊 Dataset
- Source: UCI Machine Learning Repository
- Observations: 908 chemical compounds
- Variables: 7
- Response Variable: LC50

### Features
- CIC0
- SM1_Dz
- GATS1i
- NdsCH
- NdssC
- MLOGP

## 🔍 Methods Used
- Exploratory Data Analysis (EDA)
- Data cleaning & outlier removal
- Correlation analysis (heatmap)
- Train-test split (85% / 15%)
- Linear Regression model
- Five-fold cross-validation for model comparison

## 📈 Model Evaluation
- R² ≈ 0.66
- RMSE used for performance evaluation
- Analysis of actual vs predicted LC50 values

## 🛠 Tools & Technologies
- R
- RStudio
- Statistical Learning Methods
🐍 Python Implementation

The project has been extended with a Python implementation using:

-Python
-Pandas and NumPy
-Matplotlib
-Scikit-learn

Machine Learning Models

The Python implementation includes:
- Linear Regression
- -idge Regression
- K-Nearest Neighbours (KNN)
- Random Forest Regressor
- Gradient Boosting Regressor

Python Model Evaluation

Linear Regression results on the cleaned dataset:

Dataset

R²       RMSE  Training
0.608    0.814
               Testing
0.659    0.793

Five-fold cross-validation was also performed to compare different regression models.
Model
Mean R²        Mean RMSE        Linear Regression
0.585          0.816            Ridge Regression
0.585          0.816            KNN
0.610          0.792            Random Forest
0.629          0.771            Gradient Boosting
0.621          0.779

The Random Forest model achieved the highest mean cross-validation R² among the evaluated models.

📈 Results and Visualisation

The analysis includes:
     -Feature distribution histograms
     -Correlation heatmap
     -Actual versus predicted LC50 plots
     -Training and testing performance evaluation
     -Comparison of multiple regression algorithms
     
🛠 Tools and Technologies

Original implementation:
     -R
     -RStudio
Extended implementation:
   -Python
   - Pandas
   - NumPy
   - Matplotlib
   -Scikit-learn

Machine Learning Models
The Python implementation includes:
  -Linear Regression
  -Ridge Regression
  -K-Nearest Neighbours (KNN)
  -Random Forest Regressor
  -Gradient Boosting Regressor

📁 Project Structure
R implementation – Original statistical machine learning analysis
Python implementation – Extended analysis and regression models

🎯 Learning Outcomes
Applied statistical machine learning techniques to an environmental toxicity prediction problem.
Gained experience in data preprocessing, exploratory analysis and regression modelling.

Implemented and evaluated machine learning algorithms using both R and Python.

Compared linear and ensemble-based regression models using cross-validation.

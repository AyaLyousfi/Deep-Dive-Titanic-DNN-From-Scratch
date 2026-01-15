# Deep-Dive-Titanic-DNN-From-Scratch
# 🚢Titanic Survival Prediction: A Deep Dive with Optuna

[![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-blue.svg)](https://www.kaggle.com/competitions/titanic/data)

##  Project Overview
This project applies machine learning techniques to predict the survival of passengers on the Titanic. The dataset is sourced from the famous [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data).

It goes beyond basic modeling by incorporating **Optuna** for advanced hyperparameter tuning and **SMOTE** to handle class imbalance, ensuring a robust and accurate prediction model.

##  Tech Stack
* **Python 3.x**
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn, Missingno
* **Machine Learning:** Scikit-learn
* **Optimization:** Optuna
* **Imbalance Handling:** Imbalanced-learn (SMOTE)

## Key Features
1.  **Exploratory Data Analysis (EDA):** - Visualizing survival rates by gender, class, and age.
    - Analyzing missing data patterns using `missingno`.
2.  **Data Preprocessing:**
    - Handling missing values.
    - Categorical variable encoding (`LabelEncoder`).
    - Feature scaling (`MinMaxScaler`).
3.  **Handling Class Imbalance:**
    - Implementation of **SMOTE** (Synthetic Minority Over-sampling Technique) to ensure the model doesn't become biased toward the majority class.
4.  **Hyperparameter Optimization:**
    - Utilization of **Optuna** to automatically search for the best model hyperparameters, maximizing performance metrics.


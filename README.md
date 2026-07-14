# SoS-2026
Predictive modeling of school dropout rates in India using UDISE+ data. Covers data preprocessing, feature engineering, regression modeling, hyperparameter tuning, cross-validation and model evaluation to identify key factors influencing student dropout
# School Dropout Prediction using Machine Learning

## Overview

This project develops a machine learning model to predict school dropout rates in India using educational indicators from the UDISE+ (Unified District Information System for Education) dataset. The objective is to identify the factors that contribute to student dropout and evaluate the effectiveness of different regression models in predicting dropout rates.

The project follows a complete end to end machine learning workflow, including data collection, preprocessing, exploratory data analysis, feature engineering, model development, hyperparameter tuning, and performance evaluation.

---

## Objectives

* Collect and prepare educational data from UDISE+.
* Analyze relationships between school level indicators and dropout rates.
* Build predictive regression models for dropout rate estimation.
* Compare model performance using standard evaluation metrics.
* Identify the most influential features affecting student dropout.

---

## Project Workflow

1. **Data Collection**

   * Collected educational statistics from the UDISE+ dataset.

2. **Data Cleaning and Preprocessing**

   * Handled missing values.
   * Removed irrelevant features.
   * Encoded and transformed variables where required.
   * Prepared the dataset for machine learning.

3. **Exploratory Data Analysis (EDA)**

   * Analyzed feature distributions.
   * Studied correlations between variables.
   * Visualized important trends affecting dropout rates.

4. **Model Development**

   * Implemented multiple regression algorithms.
   * Trained models using appropriate train test splits.

5. **Hyperparameter Tuning**

   * Applied GridSearchCV with cross validation.
   * Selected optimal model parameters.

6. **Results and Discussion**

   * Evaluated models using:

     * Mean Absolute Error (MAE)
     * Root Mean Squared Error (RMSE)
     * R² Score
   * Compared model performance and interpreted feature importance.

---


## Tools and Technologies

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Scikit learn
* UDISE+ Dataset

---

## Machine Learning Pipeline

* Data Cleaning
* Feature Engineering
* Train Test Split
* Model Training
* Cross Validation
* Hyperparameter Optimization
* Model Evaluation
* Feature Importance Analysis

---

## Dataset

The project uses publicly available educational data from the **UDISE+ (Unified District Information System for Education)** portal, maintained by the Ministry of Education, Government of India.

---

## Results

Several regression models were evaluated and compared using standard performance metrics. Hyperparameter tuning and cross-validation were employed to improve model generalization. Feature importance analysis helped identify the educational indicators that have the greatest influence on school dropout rates.

---

## Future Improvements

* Incorporate district wise socioeconomic indicators.
* Explore advanced ensemble methods such as XGBoost and LightGBM.
* Develop an interactive dashboard for visualization.
* Deploy the trained model as a web application for educational policy analysis.

---

## Author

This project is for learning process



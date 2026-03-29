# PDAN8411w Linear Regression  
**Student:** Andiswa Sibusisiwe Phewa  
**Student Number:** ST10123828  
**Module:** PDAN8411w – Programming for Data Analytics
**Institution:** IIE Rosebank College  
**Year:** 2026  



## Overview  
This repository contains the work completed for **Part 1** of the PDAN8411w Programming for Data Analytics assessment. The objective of the task was to evaluate the suitability of the medical insurance dataset for Linear Regression, conduct a full exploratory data analysis, select appropriate features, train a regression model, and evaluate its performance.

The analysis was completed using Python in Jupyter Notebook.



## Contents of the Repository  

| File | Description |
|------|-------------|
| **PDAN8411w_Part1_ST10123828.ipynb** | Jupyter Notebook containing the full analysis for Part 1, including EDA, feature selection, model training, evaluation, and refinement. |
| **insurance.csv** | Dataset used to train and evaluate the Linear Regression model. |
| **PDAN8411w_Report_ST10123828.pdf** | Written report summarising the EDA, model development, results, and interpretation according to IIE Harvard referencing requirements. |



## Summary of What Was Completed in Part 1  

### 1. Dataset Evaluation  
The dataset was examined to determine whether it was suitable for Linear Regression. This involved assessing data quality, checking for missing values, reviewing data types, and confirming that the target variable (charges) is continuous. The dataset was found to be suitable.

### 2. Exploratory Data Analysis  
A detailed EDA was conducted to understand the structure and behaviour of the data. This included:  
- Summary statistics and structural checks  
- Distribution analysis for numerical features  
- Outlier detection using boxplots  
- Analysis of categorical variables  
- Correlation analysis for numerical relationships  

These steps helped identify the variables most likely to influence medical charges.

### 3. Feature Selection  
Categorical variables were encoded using one-hot encoding. Relationships between predictors and the target variable were assessed using statistical insights and domain reasoning. Strong and weak predictors were identified for model training.

### 4. Model Training  
A Linear Regression model was trained using the cleaned and prepared dataset. An 80/20 train-test split was used to ensure fair model evaluation. The model was fitted using the selected features, and coefficients were analysed.

### 5. Model Evaluation  
The model’s performance was assessed using appropriate regression metrics, including:  
- R² Score  
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)

The results were interpreted to determine the model’s strengths and limitations.

### 6. Model Refinement  
A refined model was created by adjusting the feature set to address areas where performance could be improved. The refined model’s metrics were compared to the original model to assess whether the changes were beneficial.



## Notes  
The notebook and report are intended to be read together. The notebook contains all Python code and outputs, while the report presents the findings in a formal structure appropriate for academic submission.

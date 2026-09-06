# Jupyter Notebooks — Dashboard Development

This folder contains the Jupyter notebooks used for the data science and machine learning development of the Stroke Risk Prediction Dashboard.

The notebooks were used to explore the dataset, perform statistical analysis, develop predictive models and investigate model explanations before integrating the results into the Streamlit dashboard.

## Notebooks

### 01 — Descriptive Statistics

`01_descriptive_statistics.ipynb`

This notebook explores the processed stroke dataset using descriptive statistics and visualizations.

The analysis includes:

- Dataset exploration
- Patient characteristics
- Age distribution
- Stroke prevalence
- Heart disease and hypertension
- Smoking status
- Work and residence types
- Glucose and BMI
- Descriptive questions and visualizations

The notebook was used to identify patterns and generate analytical results for the Descriptive Analytics component of the dashboard.

### 02 — Predictive Statistics

`02_predictive_statistics.ipynb`

This notebook focuses on the predictive modelling of stroke risk.

The analysis includes:

- Dataset preparation
- Selection of input features
- Definition of the stroke target variable
- Machine learning classification
- Comparison of predictive models
- Model evaluation
- Accuracy, precision, recall and F1-score
- Training and prediction time
- Selection of the final predictive model

The results were used to support the Predictive Analytics component of the dashboard.

### 03 — Diagnostic Analysis and Explainability

`03_diagnostic_and_explainability.ipynb`

This notebook contains diagnostic analysis and model explainability.

The analysis includes:

- Dataset preparation
- Relationships between variables
- Diagnostic analysis
- Correlation analysis
- Machine learning analysis
- SHAP-based model explanations

SHAP was used to understand which input features contributed to individual stroke-risk predictions and to support the Prescriptive Analytics component of the dashboard.

## Processed Dataset

`processed_data.csv`

This file contains the processed version of the stroke dataset used during the analysis and dashboard development.

## Tools

The notebooks were developed using:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- SHAP
- Jupyter Notebook

## Purpose

The notebooks provided the analytical and machine learning foundation for the Stroke Risk Prediction Dashboard. The results were subsequently integrated into the Streamlit application.

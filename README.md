# 🦠 Mortality and Clinical Data Analysis in COVID-19 Patients
This project explores the "Mortality_incidence_sociodemographic_and_clinical_data_in_COVID19_patients" dataset,
analyzing sociodemographic, clinical, and laboratory data to uncover trends and insights into patient outcomes, 
including mortality and length of stay (LOS). The analysis focuses on identifying critical factors affecting patient prognosis during the COVID-19 pandemic.
## Project Overview
This project aims to develop Machine Learning models to predict critical patient outcomes, 
including mortality risk and hospital length of stay (LOS) for COVID-19 patients, using sociodemographic, 
clinical, and laboratory data. By leveraging this dataset, the project seeks to identify key predictors of adverse outcomes 
and provide actionable insights to healthcare professionals for improving patient management and resource allocation.
## Objectives
1. Feature Engineering:
  * Process and clean the dataset to handle missing values, outliers, and categorical data encoding.
  * Scale and normalize continuous features like CRP, ferritin, and troponin for improved model performance.
    
2.Exploratory Data Analysis (EDA):
  * Investigate relationships between features and target variables (e.g., mortality and LOS).
  * Visualize distributions, correlations, and thresholds for laboratory markers.

3.Modeling:
  * Predict mortality risk: Classification task using features like age, severity, and biomarkers.
  * Predict hospital length of stay: Regression task for LOS prediction and classification for binary LOS (LOS_Y).

4.Model Interpretation:
  * Identify important predictors using feature importance (e.g., SHAP values, permutation importance).
  * Evaluate thresholds for biomarkers like CRP and ferritin to predict adverse outcomes.

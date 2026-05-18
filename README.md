# Supplementary Materials for the Master's Thesis

This repository contains supplementary implementation materials for the master's thesis:

**Development of a System for Assessing the Employee Engagement Index and Analyzing Its Financial Impact on Company Performance Using Machine Learning Methods**

## Files

### `SQL_Feature_Engineering_Pipeline.docx`

This file contains the SQL feature-engineering pipeline used to construct the employee-week analytical dataset.  
The pipeline prepares employee cohort data, meeting activity features, schedule coverage indicators, offer/voice features, quality-control features, regional context variables, and the final `employee_week_feature_dataset`.

The SQL dialect is PostgreSQL / Greenplum. Source table names are anonymized due to internal information security and NDA restrictions.

### `Python_Analysis_Modelling_Pipeline.ipynb`

This notebook contains the Python analytical pipeline used after SQL-based dataset construction.  
It includes data validation, exploratory analysis, outlier diagnostics, proxy engagement-index construction, financial outcome analysis, OLS modelling, segmentation, scenario analysis, and machine-learning models for forecasting future engagement dynamics and strong EI drops.

The notebook is provided as a reproducibility artifact and does not include confidential production data.

## Data Availability

The original production data cannot be published due to confidentiality, internal information security requirements, and NDA restrictions.  
The repository therefore contains only anonymized code and analytical logic.

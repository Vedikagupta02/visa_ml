# Visa Application Prediction System

## Overview
This project aims to develop a machine learning model to predict visa application outcomes, helping streamline the visa approval process for the Office of Foreign Labor Certification (OFLC).

## Business Context
Business communities in the United States face high demand for human resources. The Immigration and Nationality Act (INA) of the US permits foreign workers to work in the country, but the process of reviewing visa applications is becoming increasingly challenging due to the growing number of applicants. This project aims to facilitate this process through data-driven solutions.

## Project Objectives
1. Develop a classification model to predict visa application outcomes
2. Identify key factors influencing visa approval decisions
3. Provide recommendations for visa application success

## Dataset Description
The dataset contains various attributes about visa applicants and their employers:

### Features
- `case_id`: Unique identifier for each visa application
- `continent`: Applicant's continent of origin
- `education_of_employee`: Educational qualification of the applicant
- `has_job_experience`: Whether the applicant has prior job experience
- `requires_job_training`: Whether job training is required
- `no_of_employees`: Number of employees in the employer's company
- `yr_of_estab`: Year the employer's company was established
- `region_of_employment`: Intended region of employment in the US
- `prevailing_wage`: Average wage for similar positions in the area
- `unit_of_wage`: Unit of wage measurement (Hourly, Weekly, Monthly, Yearly)
- `full_time_position`: Whether the position is full-time
- `case_status`: Final status of the visa application (Certified/Denied)

## Project Structure
- `AdvancedMachineLearningEasyVisa.ipynb`: Main Jupyter notebook containing the analysis and model development
- `README.md`: Project documentation

## Requirements
- Python 3.x
- Jupyter Notebook
- Required Python packages (installed via pip):
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn



## Key Achievements

- **High Model Performance**: Achieved F1 scores of over 80% using Gradient Boosting (GBM), with the best model achieving 82.3% F1 score, demonstrating strong predictive capability for visa approvals.
- **Data Imbalance Handling**: Successfully addressed class imbalance through SMOTE oversampling, enhancing model performance across all algorithms.

## Model Performance Highlights

- Best Model: Gradient Boosting (GBM) with F1 score of 0.823
- Consistent Performance: Ensemble methods consistently outperformed single decision trees
- Improved Metrics: Oversampling increased F1 scores across all models

## Getting Started
1. Clone the repository:
```bash
git clone https://github.com/Vedikagupta02/visa_ml.git
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open and run the Jupyter notebook:
```bash
jupyter notebook AdvancedMachineLearningEasyVisa.ipynb
```

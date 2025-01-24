# Georgia-Recidivism-Analysis
A comprehensive analysis of recidivism rates in Georgia using machine learning and statistical techniques. The project explores demographic, behavioral, and systemic factors contributing to recidivism, leveraging data cleaning, EDA, and predictive modeling to uncover actionable insights for criminal justice interventions.

## Overview
This project examines recidivism rates in Georgia from 2013 to 2015, leveraging machine learning and data analytics techniques. Key objectives include identifying demographic, behavioral, and systemic factors contributing to recidivism, and predicting recidivism likelihood with high accuracy.

## Dataset
- **Source**: [NIJ's Recidivism Challenge Dataset](https://data.ojp.usdoj.gov/Courts/NIJ-s-Recidivism-Challenge-Full-Dataset/ynf5-u8nk)
- **Description**:
  - Includes demographic, behavioral, and systemic attributes such as age, gender, prior convictions, substance abuse, and education level.
  - Time frames analyzed: 1 year, 2 years, and 3 years post-release.

## Methodology
1. **Data Cleaning**:
   - Addressed null values with interpolation or averages.
   - Dropped columns with excessive missing data.
2. **EDA**:
   - Explored correlations between recidivism and factors like supervision levels, demographics, and substance abuse.
3. **Modeling**:
   - Machine learning models: Logistic Regression, Random Forest, Gradient Boosting, and Support Vector Machines.
   - Techniques: Hyperparameter tuning and cross-validation.
4. **Visualization**:
   - Correlation matrices and demographic breakdowns.
   - Recidivism rates across supervision levels and risk scores.

## Results
1. **Top Model**: Logistic Regression with hyperparameter tuning achieved the highest accuracy (72.2%) and AUC (0.7832).
2. **Insights**:
   - Substance abuse and employment history strongly correlate with recidivism.
   - Higher risk scores and supervision levels are associated with increased recidivism.

## Tools and Technologies
- **Programming Languages**: Python, R
- **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn
- **Data Platform**: Databricks DBFS


# Jamboree-Admission-Prediction

Welcome to the Jamboree Business Case Study repository! This project focuses on predicting the chances of students getting admitted to Ivy League colleges based on key academic and personal factors. The analysis is performed from an Indian applicant's perspective, leveraging regression models and statistical methods.

## About The Project

Jamboree, a leader in test prep and admissions counseling, offers students a feature to check their chances of getting into Ivy League universities. This project leverages that data to build a predictive model using various regression techniques such as Linear Regression, Ridge, Lasso, and ElasticNet.

## Dataset Description

1. GRE Score (out of 340)--> Graduate Record Examinations score
2. TOEFL Score (out of 120)-->	Test of English as a Foreign Language score
3. University Rating (out of 5)-->	Rating of the University
4. SOP (out of 5)-->	Strength of Statement of Purpose
5. LOR (out of 5)-->	Strength of Letter of Recommendation
6. CGPA (out of 10)-->	Undergraduate GPA
7. Research (0 or 1)-->	Research experience indicator
8. Chance of Admit (0 to 1)-->	Estimated probability of getting an admission

## Tech Stack

1. Python (pandas, numpy, seaborn, matplotlib)
2. scikit-learn (Linear Regression, Ridge, Lasso, ElasticNet)
3. statsmodels
4. Jupyter Notebook

## Project Workflow

1. Data Cleaning & Profiling
   1. Removed irrelevant columns
   2. Handled missing values
   3. Identified data types & summary statistics

2. Exploratory Data Analysis (EDA)
   1. Univariate and bivariate analysis
   2. Boxplots and histograms
   3. Correlation heatmaps

3. Feature Scaling
   1. StandardScaler applied to normalize features
  
4. Modeling
   1. Built Linear Regression model
   2. Applied Ridge, Lasso & ElasticNet regularization
   3. Evaluated using R², RMSE, MAE, and Adjusted R²

5. Model Diagnostics
   1. Multicollinearity Check (VIF)
   2. Residual Analysis (Homoscedasticity, Normality)
   3. Breusch-Pagan & Jarque-Bera tests

## Insights

1. **Top Predictors:** CGPA, GRE Score, and TOEFL Score are the strongest indicators of admission probability.
2. **Multicollinearity:** No significant multicollinearity was found (VIF < 5 for all features).
3. **Model Assumptions:** Slight heteroscedasticity and non-normality in residuals were detected.

## Recommendations

1. Students should focus on improving CGPA, GRE Score, and LOR quality.
2. Add additional features such as work experience, internships, and extracurriculars to enhance predictive power.
3. Further investigation into heteroscedasticity and non-normal residuals can improve model robustness.

   
   




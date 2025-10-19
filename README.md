# Employee Attrition Analysis | Machine Learning with Logistic Regression

![Employee Attrition report](./Employee-Attrition.jpg) 

## Objective
Predict employee attrition using HR data, and identify key factors contributing to employees leaving or staying with the company.

## Steps Involved
- Data preparation: Cleaning, feature selection, encoding categorical variables.
- Exploratory analysis: Univariate, bivariate analysis, and correlation checks to identify influential features.
- Model building: Logistic regression applied to training data for binary attrition classification.
- Evaluation: Confusion matrix, accuracy, precision, recall, F1-score, feature importance, and business insights.

## Tools Used
- Python (Jupyter Notebook)
- pandas, numpy (data processing)
- scikit-learn (modeling, train-test split, logistic regression, metrics)
- seaborn, matplotlib (visualization)

## Conclusion
- The logistic regression model achieved 86% accuracy and robust prediction for employees who stayed, but struggled with detecting those who left due to class imbalance.
- "OverTime" and "MaritalStatus" were top predictors of attrition, while "JobSatisfaction" and "WorkLifeBalance" helped retention.
- Recommended next steps include handling class imbalance, applying advanced models, and using findings for targeted HR interventions.


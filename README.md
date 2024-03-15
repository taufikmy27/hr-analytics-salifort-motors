# HR Analytics: Predicting Employee Turnover at Salifort Motors

## Overview
The aim of this project is to predict whether an employee will leave Salifort Motors. Initial analysis using a logistic regression model achieved a precision of 80%, recall of 83%, f1-score of 80% (all weighted averages), and an accuracy of 83% on the test set. Further refinement through feature engineering led to a decision tree model reaching an AUC of 93.8%, precision of 87.0%, recall of 90.4%, f1-score of 88.7%, and accuracy of 96.2% on the test set. The random forest model showed a modest improvement over the decision tree model.

## Business Understanding
Salifort Motors aims to reduce employee turnover by understanding and addressing the key factors that lead to employee departures. High turnover rates not only increase recruitment costs but also affect team productivity and morale. By accurately predicting potential departures, HR strategies can be tailored to enhance employee satisfaction and retention, thereby saving on costs and maintaining operational efficiency.

## Data Understanding
The dataset comprises 14,999 entries with 10 features that describe each employee's work environment and satisfaction level at Salifort Motors. These features include 'satisfaction_level', 'last_evaluation', 'number_project', 'average_monthly_hours', 'time_spend_company', 'Work_accident', 'left' (target variable), 'promotion_last_5years', 'Department', and 'salary'. This comprehensive dataset allows for a detailed analysis of factors influencing employee turnover.

## Modeling and Evaluation
Three models were explored to predict employee turnover: logistic regression, decision tree, and random forest. The logistic regression model served as a baseline, with subsequent models employing feature engineering for improved prediction accuracy. The decision tree model, benefiting from this feature engineering, achieved significant gains in all evaluation metrics, particularly in AUC and accuracy. The random forest model further refined these results, slightly outperforming the decision tree model in overall prediction capability. Evaluation focused on accuracy, precision, recall, f1-score, and AUC to ensure a comprehensive understanding of model performance.

## Conclusion
The project's findings indicate that it's possible to predict employee turnover with high accuracy at Salifort Motors. The decision tree and random forest models, with their superior performance metrics, provide valuable insights into the key factors contributing to employee departure. Implementing targeted HR interventions based on these insights can help Salifort Motors reduce turnover rates. Future work could explore additional modeling techniques, more complex feature engineering, and deeper analysis into department-specific turnover patterns to further enhance predictive accuracy and business strategy alignment.


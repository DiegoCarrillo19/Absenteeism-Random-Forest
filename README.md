# Absenteeism-Random-Forest

Project Description
This project aims to predict employee absenteeism using an HR dataset. We use a decision tree model (and later an optimized random forest) to identify the key variables associated with high absenteeism.

The idea was inspired by the AIHR article:
https://www.aihr.com/blog/hr-data-sets-people-analytics/

Objective
1. Predict whether an employee will have high absenteeism.
2. Identify the most important features influencing this behavior.
3. Provide explanatory visualizations and export data for analysis in Power BI.
   
Methodology
1. Preprocessing:
   * Encoding categorical variables.
   * Binarizing the target (AbsentHours).
     
2. Modeling:
   * Initial Decision Tree.
   * Random Forest with hyperparameter tuning (GridSearchCV).

3. Evaluation:
   * Precision, recall, F1-score.
   * Confusion matrix.

4. Interpretation:
   * Decision tree visualization.
   * Feature importance analysis.
   * Export to Power BI.
  
Results
1. Accuracy of best model (Optimized Random Forest): 82%
2. Most influential features:
   * Age
   * LengthService
   * Genre_M
  
Real-World Applications
This analysis helps HR teams to:
1. Identify absenteeism patterns across roles or departments.
2. Implement data-driven preventive policies.
3. Support transparent decision-making in employee management.

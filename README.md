# Adult-Census-Income-Prediction
Predicting income levels based on census data using machine learning models.


## Project Summary
In this project, we worked with the [Adult Census Income dataset](https://archive.ics.uci.edu/dataset/2/adult) to predict whether an individual earns more than $50K annually. The dataset, originally from the [U.S. Census Bureau](https://www.census.gov/en.html), contains demographic and financial attributes, such as age, education, capital gains, and hours worked per week. We processed the data, performed exploratory data analysis (EDA), and built several binary classification models (Logistic Regression, LASSO & Ridge Regression, Decision Tree, Random Forests, and XGBoost) using R.

## Key Findings
- Model Performance: Ensemble methods like Random Forest and XGBoost outperformed simpler models like Logistic Regression and LASSO, with Random Forest achieving a misclassification rate of 13.87% and XGBoost 12.95%. However, these models are more complex and harder to interpret.

- Misclassification Rate Limitation: Given the imbalanced data, the misclassification rate isn't a reliable metric. While models show high sensitivity (>90%), their specificity is lower, meaning they struggle to correctly classify individuals in the high-income class (>50K).

- Better Metrics for Imbalanced Data: We recommend using Precision, Recall, F1-score, and AUC-ROC as more effective metrics, as they account for both the minority class and the trade-offs between false positives and false negatives.

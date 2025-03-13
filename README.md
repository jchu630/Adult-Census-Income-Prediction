# Adult-Census-Income-Prediction
Predicting income levels based on census data using various machine learning models.

[Adult Census Income Prediction](https://jchu630.github.io/Adult-Census-Income-Prediction/Adult_Census_Income.html)

## Project Rundown
In this project, we will work with the [Adult Census Income dataset](https://archive.ics.uci.edu/dataset/2/adult) to predict whether an individual earns more than $50K annually. The dataset, originally from the [U.S. Census Bureau](https://www.census.gov/en.html), contains demographic and financial attributes, such as age, education, capital gains, and hours worked per week. We will process the data, perform exploratory data analysis (EDA), and build several binary classification models (Logistic Regression, LASSO & Ridge Regression, Decision Tree, Random Forests, and XGBoost) using R.

## Key Findings
- Model Performance: Ensemble methods like Random Forest and XGBoost outperformed simpler models like Logistic Regression and LASSO, with Random Forest achieving a misclassification rate of 14.06% and XGBoost 12.95% (85.94% and 87.05% accuracy, respectively).

- Misclassification Rate Limitation: However, given the imbalanced data, the misclassification rate is not a reliable metric. While models show high sensitivity (>90%), their specificity is lower, meaning they struggle to correctly classify individuals in the high-income class (>50K).

- Better Metrics for Imbalanced Data: We recommend using Precision, Recall, F1-score, and AUC-ROC as more effective metrics, as they account for both the minority class and the trade-offs between false positives and false negatives.

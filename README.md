# Company-Bankruptcy-Prediction-Classification-Project

The Capstone project is based on classification on a Bankruptcy dataset. The
dataset had been generated in a brief period of one decade between 1999 to
2009. It has 6,819 records spread across 96 variables.
The following steps are involved in the project:

1. A preliminary/exploratory analysis of the dataset. Because the primary aim
was to make predictions and the dataset was too large, each distinct
feature was not analyzed. There were no missing values in the dataset.
While most of the variables in the dataset were in the range of 0 and 1, a
few had huge ranges and were therefore normalized. It was held that most
of the other variables were either ratios or percentages.

2. Class imbalance in the outcome variable was dealt with by oversampling.
SMOTE was employed for the same. Six ML models including Logistic
Regression, Support Vector Machine, Gradient Boosting, Random Forest,
Ada Boost, and Light GBM were used in the same order. The corresponding
cross validation scores revealed that Light GBM outperformed all others.

3. Dimensionality reduction was done using PCA. 30 principal components
were selected. CV scores on the new model suggested that Random Forest
was the best performer. After Hyperparameter tuning, the model gave an
accuracy of almost 78%.

# Santander-Customer-Transaction-Prediction
Task: To classify whether customers make a particular transaction, irrespective of the amount of money transacted.

Dataset (highly imbalanced):
-200 anonymized numerical columns, 1 unique ID code column, and a target column.
-Performed extensive EDA and derived insights.
-Oversampling of data points after stratified split.

Performance metric:
ROC AUC score 

Model Implementation:
-Applied Logistic Regression, Random Forests, and Gaussian Naive Bayes model with basic feature engineering techniques and Gaussian transformation of features; achieved the highest AUC of 0.88 with this approach. 
-With advanced feature engineering and GBDT model, achieved an AUC of 0.91.
-Model hyper-parameter tuning techniques: random search, halving grid search, Optuna (bayesian optimization).

-In the top 10% of Kaggle submissions.

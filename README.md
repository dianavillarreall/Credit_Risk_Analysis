# Credit_Risk_Analysis
## Overview of the loan prediction risk analysis:
### Purpose of the analysis
For this analysis, we used imbalanced-learn and scikit-learn to create models using resampling with the purpose to predict credit risk. We were able to obtaim the result by doing the following:
-Oversampling the given data utilizing the RandomOverSampler and SMOTE algorithms.
-Under sampling the given data using the ClusterCentroids algorithm.
-Use both approaches of over and under sampling utilizing the SMOTEENN algorithm.
-Compare two machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier to predict credit risk.
## Results:
### RandomOverSampler model
- Balance accuracy score: 65%
- Precision is 1% for high-risk and 100% for low-risk
- Recall is 74% for high-risk and 55% for low-risk

### SMOTE Model
- Balance accuracy score: 66%
- Precision is 1% for high-risk and 100% for low-risk
- Recall is 63% for high-risk and 64% for low-risk

### ClusterCentroids Model
- Balance accuracy score: 64%
- Precision is 1% for high-risk and 100% for low-risk
- Recall is 70% for high-risk and 58% for low-risk

### SMOTEENN Model
- Balance accuracy score: 67%
- Precision is 1% for high-risk and 100% for low-risk
- Recall is 78% for high-risk and 55% for low-risk

### BalancedRandomForestClassifier Model
- Balance accuracy score: 83%
- Precision is 3% for high-risk and 100% for low-risk
- Recall is 77% for high-risk and 88% for low-risk

### EasyEnsembleClassifier Model
- Balance accuracy score: 93%
- Precision is 7% for high-risk and 100% for low-risk
- Recall is 91% for high-risk and 95% for low-risk

## Summary of the Analysis
All the models that we used to perform the credit risk analysis showed bad precision in determining if a credit risk is high. The Easy Ensemble AdaBoost Classifier Model had the highest recall score, for this reason it would be the best machine learning model to choose for further credit card analysis.

# Credit_Risk_Analysis

This project uses different techniques to train and evaluate models with unbalanced classes using credit card dataset. In this analysis we use the following models for our evaluation:

- Oversampling ( RandomOverSampler and SMOTE algorithms)
- Undersampling ClusterCentroids algorithm)
- Combinational approach(SMOTEENN algorithm)
- Two machine learning models that reduces bias to predit credit risk( BalancedRandomForestClassifier and EasyEnsembleClassifier)

# Result
## RandomOverSampler Model
The average precision and recall is 99% and 67%. Below is the confusion matrix and classification reports for this model. The f1 score is 79%. The number of false positive or low risk creit cards that predicted high risk is 5720.
- Balanced Accuracy score: 63.75%
- Precision for high risk: 1%
- Recall for high risk: 61%


# Credit_Risk_Analysis

This project uses different techniques to train and evaluate models with unbalanced classes using credit card dataset. In this analysis we use the following models for our evaluation:

- Oversampling ( RandomOverSampler and SMOTE algorithms)
- Undersampling ClusterCentroids algorithm)
- Combinational approach(SMOTEENN algorithm)
- Two machine learning models that reduces bias to predit credit risk( BalancedRandomForestClassifier and EasyEnsembleClassifier)

# Result
## RandomOverSampler Model
The average precision and recall is 99% and 66%. Below is the confusion matrix and classification reports for this model. The f1 score is 79%. The number of false positive or low risk creit cards that predicted high risk is 5821.
- Balanced Accuracy score: 65.76%
- Precision for high risk: 1%
- Recall for high risk: 66%

![Image](https://github.com/faridah-m/Credit_Risk_Analysis/blob/main/RandomOverSampler%20Model.PNG)
![Image](https://github.com/faridah-m/Credit_Risk_Analysis/blob/main/RandomOverSampler%20Model.2PNG.PNG)

## SMOTE Oversampling


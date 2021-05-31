# Credit_Risk_Analysis

This project uses different techniques to train and evaluate models with unbalanced classes using credit card dataset. In this analysis we use the following models for our evaluation:

- Oversampling ( RandomOverSampler and SMOTE algorithms)
- Undersampling ClusterCentroids algorithm)
- Combinational approach(SMOTEENN algorithm)
- Two machine learning models that reduces bias to predit credit risk( BalancedRandomForestClassifier and EasyEnsembleClassifier)

# Result
## RandomOverSampler Model
The average precision and recall is 99% and 66%. Below is the confusion matrix and classification reports for this model. The f1 score is 79%. The number of low risk credit cards that predicted high risk is 5821.
- Balanced Accuracy score: 65.76%
- Precision for high risk: 1%
- Recall for high risk: 66%

![Image](https://github.com/faridah-m/Credit_Risk_Analysis/blob/main/RandomOverSampler%20Model.PNG)
![Image](https://github.com/faridah-m/Credit_Risk_Analysis/blob/main/RandomOverSampler%20Model.2PNG.PNG)

## SMOTE Oversampling
The average precision and recall is 99% and 65%. Below is the confusion matrix and classification reports for this model. The f1 score at 78% for this class. The number of low risk credit cards that predicted high risk is 6040.
- Balanced Accuracy score: 62.24%
- Precision for high risk: 1%
- Recall for high risk: 60%

![Image](https://github.com/faridah-m/Credit_Risk_Analysis/blob/main/SMOTE%20Oversamling.PNG)
![Image](https://github.com/faridah-m/Credit_Risk_Analysis/blob/main/SMOTE%20Oversamling2.PNG)

## Undersampling
The average precision and recall is 99% and 44%. Below is the confusion matrix and classification reports for this model. The f1 score is 60% . The number of  low risk credit cards that predicted high risk is 9682.
- Balanced Accuracy score: 51.03%
- Precision for high risk: 1%
- Recall for high risk: 59%

![Image](https://github.com/faridah-m/Credit_Risk_Analysis/blob/main/Undersampling.PNG)
![Image](https://github.com/faridah-m/Credit_Risk_Analysis/blob/main/Undersampling2.PNG)

## Combination (Over and Under) Sampling
The average precision and recall is 99% and 57%. Below is the confusion matrix and classification reports for this model. The f1 score is 73%. The number of low risk credit cards that predicted high risk is 7293.
- Balanced Accuracy score: 63.76%
- Precision for high risk: 1%
- Recall for high risk: 70%

![Image](https://github.com/faridah-m/Credit_Risk_Analysis/blob/main/Combination%20(Over%20and%20Under)%20Sampling.PNG)
![Image](https://github.com/faridah-m/Credit_Risk_Analysis/blob/main/Combination%20(Over%20and%20Under)%20Sampling2.PNG)

## Balanced Random Forest Classifier
The average precision and recall was 99% and 90%. Below is the confusion matrix and classification reports for this model. The f1 score is 94% . The number of low risk credit cards that predicted high risk is 1630.
- Balanced Accuracy score: 80.30%
- Precision for high risk: 4%
- Recall for high risk: 70%

![Image](https://github.com/faridah-m/Credit_Risk_Analysis/blob/main/Balanced%20Random%20Forest%20Classifier.PNG)

## Easy Ensemble AdaBoost Classifier
The average precision and recall was 99% and 94%. Below is the confusion matrix and classification reports for this model. The f1 score is 97%. The number of low risk credit cards that predicted high risk is 979.
- Balanced Accuracy score: 92.54%
- Precision for high risk: 7%
- Recall for high risk: 91%

![Image](https://github.com/faridah-m/Credit_Risk_Analysis/blob/main/Easy%20Ensemble%20AdaBoost%20Classifier.PNG)

# Summary
This analysis was looking for a lower number of high risk credit cards that were predicted low risk. To do this, we looked at higher percentage of recall for high ris with a good accuracy. Out of all models, The Easy Ensemle AdaBoost has the highest accuracy score at 92.54% and the least false negative for high risk along with the highest recall percentage (%70). From this perspective, Easy Ensemble model is the one to choose, , however 979 or 6% of low risk credit cards were falsely predicted high risk and that would be lost opporunities for the credit card company or bank.

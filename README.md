# Credit Risk Analysis Using Machine Learning
## Overview
The purpose of this project is to implement and evaluate several machine learning models or algorithms to predict credit risk. The credit card credit dataset from LendingClub, a peer-to-peer lending services company will be used to implement the following:
- Oversample the data using the Random Over Sampler and SMOTE algorithms
- Undersample the data using the Cluster Centroids algorithm
- Use a combinatorial approach of over- and under sampling using the SMOTEENN algorithm.
- Compare Balanced Random Forest Classifier and Easy Ensemble Classifier machine learning models that reduce bias to predict credit risk

## Results

### Logistic Regression using Naive Random Over Sampling

- Balanced accuracy score:0.66
- Precision Scores high risk : 0.01
                   low risk  : 1.00
- Recall Scores high risk: 0.74
                low risk: 0.58

**Balanced accuracy score**

![Native_Random_Oversampling_balanced accuracy score.png](https://github.com/smj452/Credit_Risk_Analysis/blob/main/Resources/Native_Random_Oversampling_balanced%20accuracy%20score.png)

**Confusion matrix**

![Native_Random_Oversampling_confusion matrix.png](https://github.com/smj452/Credit_Risk_Analysis/blob/main/Resources/Native_Random_Oversampling_confusion%20matrix.png)

**Imbalanced classification report**

![Native_Random_Oversampling_imbalanced classification](https://github.com/smj452/Credit_Risk_Analysis/blob/main/Resources/Native_Random_Oversampling_imbalanced%20classification%20report.png)

### SMOTE Oversampling
- Balanced accuracy score: 0.65
- Precision Scores high risk : 0.01
                   low risk  : 1.00
- Recall Scores high risk: 0.62
                low risk: 0.68

**Balanced accuracy score**

![SMOTE_Oversampling_balanced accuracy score.png](https://github.com/smj452/Credit_Risk_Analysis/blob/main/Resources/SMOTE_Oversampling_balanced%20accuracy%20score.png)

**Confusion matrix**

![SMOTE_Oversampling_confusion matrix.png](https://github.com/smj452/Credit_Risk_Analysis/blob/main/Resources/SMOTE_Oversampling_confusion%20matrix.png)
**Imbalanced classification report**

![SMOTE_Oversampling_imbalanced classification report.png](https://github.com/smj452/Credit_Risk_Analysis/blob/main/Resources/SMOTE_Oversampling_imbalanced%20classification%20report.png)

### Undersampling

- Balanced accuracy score: 0.547
- Precision Scores high risk : 0.01
                   low risk  : 1.00
- Recall Scores high risk: 0.68
                low risk: 0.41


**Balanced accuracy score**

![Undersampling_balanced accuracy score.png](https://github.com/smj452/Credit_Risk_Analysis/blob/main/Resources/Undersampling_balanced%20accuracy%20score.png)

**Confusion matrix**

![Undersampling_confusion matrix.png](https://github.com/smj452/Credit_Risk_Analysis/blob/main/Resources/Undersampling_confusion%20matrix.png)

**Imbalanced classification report**

![Undersampling_imbalanced classification report.png](https://github.com/smj452/Credit_Risk_Analysis/blob/main/Resources/Undersampling_imbalanced%20classification%20report.png)

### Combination (Over and Under) Sampling

- Balanced accuracy score: 0.64
- Precision Scores high risk : 0.01
                   low risk  : 1.00
- Recall Scores high risk: 0.72
                low risk: 0.57

**Balanced accuracy score**

![Combination (Over and Under) Sampling_balanced accuracy](https://github.com/smj452/Credit_Risk_Analysis/blob/main/Resources/Combination%20(Over%20and%20Under)%20Sampling_balanced%20accuracy%20score.png)


**Confusion matrix**

![Combination (Over and Under) Sampling_confusion matrix.png](https://github.com/smj452/Credit_Risk_Analysis/blob/main/Resources/Combination%20(Over%20and%20Under)%20Sampling_confusion%20matrix.png)


**Imbalanced classification report**

![Combination (Over and Under) Sampling_imbalanced classification](https://github.com/smj452/Credit_Risk_Analysis/blob/main/Resources/Combination%20(Over%20and%20Under)%20Sampling_imbalanced%20classification%20report.png)

### Balanced Random Forest Classifier

- Balanced accuracy score: 0.78
- Precision Scores high risk : 0.03
                   low risk  : 1.00
- Recall Scores high risk: 0.70
                low risk: 0.87


**Balanced accuracy score**

![Balanced Random Forest Classifier_balanced accuracy score.png](https://github.com/smj452/Credit_Risk_Analysis/blob/main/Resources/Balanced%20Random%20Forest%20Classifier_balanced%20accuracy%20score.png)


**Confusion matrix**

![Balanced Random Forest Classifier_confusion matrix.png](https://github.com/smj452/Credit_Risk_Analysis/blob/main/Resources/Balanced%20Random%20Forest%20Classifier_confusion%20matrix.png)


**Imbalanced classification report**

![Balanced Random Forest Classifier_imbalanced classification](https://github.com/smj452/Credit_Risk_Analysis/blob/main/Resources/Balanced%20Random%20Forest%20Classifier_imbalanced%20classification%20report.png)

### Easy Ensemble AdaBoost Classifier

- Balanced accuracy score: 0.93
- Precision Scores high risk : 0.09
                   low risk  : 1.00
- Recall Scores high risk: 0.92
                low risk: 0.94

**Balanced accuracy score**

![Easy Ensemble AdaBoost Classifier_balanced accuracy score.png](https://github.com/smj452/Credit_Risk_Analysis/blob/main/Resources/Easy%20Ensemble%20AdaBoost%20Classifier_balanced%20accuracy%20score.png)


**Confusion matrix**

![Easy Ensemble AdaBoost Classifier_confusion matrix.png](https://github.com/smj452/Credit_Risk_Analysis/blob/main/Resources/Easy%20Ensemble%20AdaBoost%20Classifier_confusion%20matrix.png)


**Imbalanced classification report**

![Easy Ensemble AdaBoost Classifier_imbalanced classification](https://github.com/smj452/Credit_Risk_Analysis/blob/main/Resources/Easy%20Ensemble%20AdaBoost%20Classifier_imbalanced%20classification%20report.png)

## Summary

### Summary of the results of the machine learning models

- Undersampling has the lowest balanced accuracy score of 0.54.
- Easy Ensemble AdaBoost Classifier has the highest balanced accuracy score of 0.93
- Easy Ensemble AdaBoost Classifier has the highest precision of 0.09, Balanced Random Forest Classifier has a precision of 0.03. All other models have a precision of 0.01 for high credit risk.
- Easy Ensemble AdaBoost Classifier has the highest recall scores of 0.92(high risk)and 0.94(low risk)
- Undersampling has the lowest recall scores of 0.68(high risk) and 0.41(low risk).


Thus from the results of the machine learning models, Easy Ensemble AdaBoost Classifier can be used to predict credit risk since the balanced accuracy score, the precision and recall scores is highest among the models.









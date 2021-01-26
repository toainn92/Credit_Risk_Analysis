# Credit_Risk_Analysis

## Overview of the Analysis
The purpose of this analysis to apply machine learning to sovle real-world challenge: credit card risk. Different techniques were employed to train and evaluate models with unbalanced classes. In this anlaysis, RandomOverSampler and SMOTE algorithms will be used to oversample the data, ClusterCentroids will be used to undersample the data. Then, a combinatorial approach of over and undersampling will be conducted with SMOTEENN algorithm. Next, the two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifer, to predict credit risk.

## Results

### Native Oversampling
- With the Native Random Oversampling, the balanced accuracy score is 0.65.
- With the confusion matrix below, the high risk applications has a precision of 0.01, recall of 0.69, and f1 score of 0.02.
- With the confusion matrix below, the low risk applications has a precision of 1.00, recall of 0.61, and f1 score of 0.76
![](Images/Native_Oversampling.PNG)

### SMOTE Oversampling

![](Images/SMOTE_Oversampling.PNG)

### Under Sampling

![](Images/Under_Sampling.PNG)

### Balanced Random Forest Classifier
![](Images/Balanced_Random_forest_Classifier.PNG)

### Easy_Ensemble_AdaBoost_Classifier
![](Images/Easy_Ensemble_AdaBoost_Classifier.PNG)

### Combination_Sampling
![](Images/Combination_Sampling.PNG)




## Summary

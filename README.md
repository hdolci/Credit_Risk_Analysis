## Overview

This analysis is to understand how to utilize Machine Learning to predict credit risk for potential customers of LendingClub. Machine Learning techniques will be applied to a large unbalanced data set to learn patterns. Some of the Machine Learning algorithms include SMOTE, BalancedRandomForestClassifier, and RandomOverSampler.


## Results

Six machine learning models were used and the outcome are as follows(alphabetacal order):

* BalancedRandomForestClassifer: 78.9% accuracy, 3% precision, 70% recall and 6% F1 Score
<img src="https://raw.githubusercontent.com/hdolci/Credit_Risk_Analysis/main/Screenshots/BalancedRandomForestClassifier.png" width="50%" height="50%">

* ClusterCentroids: 54.5% accuracy, 1% precision, 69% recall and 1% F1 Score

<img src="https://raw.githubusercontent.com/hdolci/Credit_Risk_Analysis/main/Screenshots/ClusterCentroids.png" width="50%" height="50%">

* EasyEnsembleClassifier: 93.2% accuracy, 9% precision, 92% recall, and 16% F1 Score

<img src="https://raw.githubusercontent.com/hdolci/Credit_Risk_Analysis/main/Screenshots/EasyEnsembleClassifier.png" width="50%" height="50%">

* RandomOverSampler: 64.0% accuracy, 1% precision, 66% recall and 2% F1 Score

<img src="https://raw.githubusercontent.com/hdolci/Credit_Risk_Analysis/main/Screenshots/RandomOversampler.png" width="50%" height="50%">

* SMOTE: 65.2% accuracy, 1% precision, 61% recall and 2% F1 Score

<img src="https://raw.githubusercontent.com/hdolci/Credit_Risk_Analysis/main/Screenshots/SMOTE.png" width="50%" height="50%">

* SMOTEENN: 64.5% accuracy, 1% precision, 72% recall and 2% F1 Score

<img src="https://raw.githubusercontent.com/hdolci/Credit_Risk_Analysis/main/Screenshots/SMOTEENN.png" width="50%" height="50%">



## Summary

From the analysis, EasyEnsembleClassifer model yielded the best results with an accuracy rate of 93.2% when predicting High-Risk candidates. This would be the model I recommend since the precision is 9%.




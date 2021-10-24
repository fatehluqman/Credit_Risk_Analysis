# Credit_Risk_Analysis

## Overview of the analysis
The purpose of the analysis to evaluate the performance of six different machine learning models and make a recommendation on whether they should be used to predict credit risk.
The six models being evaluated are: Naive Random Oversampling, SMOTE Oversampling, Cluster Centroid Under sampling, SMOTEENN Sampling, Balanced Random Forest Classifying and Easy Ensemble Classifying

## Results

### RandomOverSampler
* Balanced Accuracy Score: 66.0%
* High Risk: 1% Precision, 74% Recall
* Low Risk: 100% Precision, 58% Recall

### SMOTE
* Balanced Accuracy Score: 65.4%
* High Risk: 1% Precision, 62% Recall
* Low Risk: 100% Precision, 68% Recall

### ClusterCentroids
* Balanced Accuracy Score: 54.5
* High Risk: 1% Precision, 69% Recall
* Low Risk: 100% Precision, 40% Recall

### SMOTEENN
* Balanced Accuracy Score: 74.5%
* High Risk 1% Precision, 72% Recall
* Low Risk: 100% Precision, 57% Recall

### BalancedRandomForestClassifier
* Balanced Accuracy Score: 68.3%
* High Risk: 88% Precision, 37% Recall
* Low Risk: 100% Precision, 100% Recall

### EasyEnsembleClassifier
* Balanced Accuracy Score: 93.1%
* High Risk: 9% Precision, 92% Recall
* Low Risk: 100% Precision, 94% Recall

## Summary
The goal of this analysis was to determine which model was able to predict whether credit was high risk or not. 
To achieve this, we would need to evaluate the Recall/Sensitivity of each model for High Risk Credit. The model with the higher Recall score did the best job at capturing the most High-Risk credit. 
Based on this the EasyEnsembleClassifier with a Recall/Sensitivity of 92% would be the best model to use. The only short coming for the EasyEnsembleClassifier was the low Precision score of 9% which would mean that a large number of actual Low Risk Credit was being predicted as High Risk.

# Credit_Risk_Analysis

## Overview of the analysis
The purpose of the analysis to evaluate the performance of six different machine learning models and make a recommendation on whether they should be used to predict credit risk.
The six models being evaluated are: Naive Random Oversampling, SMOTE Oversampling, Cluster Centroid Under sampling, SMOTEENN Sampling, Balanced Random Forest Classifying and Easy Ensemble Classifying

## Results

### RandomOverSampler
* Balanced Accuracy Score: 66.0%
* High Risk: 1% Precision, 74% Recall
* Low Risk: 100% Precision, 58% Recall
![RandomOverSampler](https://user-images.githubusercontent.com/62673123/138577497-6f8b63b0-8baa-41b0-9489-405dba356a29.PNG)

### SMOTE
* Balanced Accuracy Score: 65.4%
* High Risk: 1% Precision, 62% Recall
* Low Risk: 100% Precision, 68% Recall
![SMOTE](https://user-images.githubusercontent.com/62673123/138577502-78564c93-42b8-41de-a924-aef7a2672ae0.PNG)

### ClusterCentroids
* Balanced Accuracy Score: 54.5
* High Risk: 1% Precision, 69% Recall
* Low Risk: 100% Precision, 40% Recall
![ClusterCentroids](https://user-images.githubusercontent.com/62673123/138577507-c6935012-e22b-499b-a733-58e765f377f5.PNG)

### SMOTEENN
* Balanced Accuracy Score: 74.5%
* High Risk 1% Precision, 72% Recall
* Low Risk: 100% Precision, 57% Recall
![SMOTEENN](https://user-images.githubusercontent.com/62673123/138577510-f5d75b89-70b8-41f1-9eca-51de16dc57b1.PNG)

### BalancedRandomForestClassifier
* Balanced Accuracy Score: 68.3%
* High Risk: 88% Precision, 37% Recall
* Low Risk: 100% Precision, 100% Recall
![BalancedRandomForestClassifier](https://user-images.githubusercontent.com/62673123/138577514-ee74a73a-73a6-4d27-91de-05ce1adbff4a.PNG)

### EasyEnsembleClassifier
* Balanced Accuracy Score: 93.1%
* High Risk: 9% Precision, 92% Recall
* Low Risk: 100% Precision, 94% Recall
![EasyEnsembleClassifier](https://user-images.githubusercontent.com/62673123/138577527-c89037dd-ba07-40eb-8a04-9dde5f43f843.PNG)

## Summary
The goal of this analysis was to determine which model was able to predict whether credit was high risk or not. 
To achieve this, we would need to evaluate the Recall/Sensitivity of each model for High Risk Credit. The model with the higher Recall score did the best job at capturing the most High-Risk credit. 
Based on this the EasyEnsembleClassifier with a Recall/Sensitivity of 92% would be the best model to use. The only short coming for the EasyEnsembleClassifier was the low Precision score of 9% which would mean that a large number of actual Low Risk Credit was being predicted as High Risk.

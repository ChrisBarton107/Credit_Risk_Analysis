# Credit_Risk_Analysis

## Overview
The purpose of the analysis was to predict credit risk using supervised learning algorithms with various machine learning models

## Results
The analysis used six machine learning algorithms including:<br>
- RandomOverSampler: Oversampling
- SMOTE: Overrsampling
- Cluster Centroids: Undersampling
- SMOTEENN: Oversampling & undersampling combinatorial approach
- Balanced Random Forest Classifier: Reduction bias
- Easy Ensemble AdaBoost Classifier: Reduction bias<br>

All precision, recall, and F1 summary statistics are based on high-risk detection

### RandomOverSampler
<img src="https://github.com/ChrisBarton107/Credit_Risk_Analysis/blob/main/Resources/ROS.png" alt="drawing" height="300" width="500"/><br>
- Balanced Accuracy Score: 65%
- Precision: 1%
- Recall/Sensitivity: 63%
- F1: 2%

### SMOTE (Synthetic Minority Oversampling Technique)
<img src="https://github.com/ChrisBarton107/Credit_Risk_Analysis/blob/main/Resources/SMOTE.png" alt="drawing" height="300" width="500"/><br>
- Balanced Accuracy Score: 65%
- Precision: 1%
- Recall/Sensitivity: 64%
- F1: 2%

### Cluster Centroids
<img src="https://github.com/ChrisBarton107/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroids.png" alt="drawing" height="300" width="500"/><br>
- Balanced Accuracy Score: 52%
- Precision: 1%
- Recall/Sensitivity: 69%
- F1: 2%

### SMOTEENN (Synthetic Minority Oversampling Technique - Edited Nearest Neighbor)
<img src="https://github.com/ChrisBarton107/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN.png" alt="drawing" height="300" width="500"/><br>
- Balanced Accuracy Score: 62%
- Precision: 1%
- Recall/Sensitivity: 69%
- F1: 2%

### Balanced Random Forest Classifier
<img src="https://github.com/ChrisBarton107/Credit_Risk_Analysis/blob/main/Resources/BRFC.png" alt="drawing" height="300" width="500"/><br>
- Balanced Accuracy Score: 79%
- Precision: 4%
- Recall/Sensitivity: 67%
- F1: 7%

### Easy Ensemble Classifier
<img src="https://github.com/ChrisBarton107/Credit_Risk_Analysis/blob/main/Resources/EEC.png" alt="drawing" height="300" width="500"/><br>
- Balanced Accuracy Score: 93%
- Precision: 7%
- Recall/Sensitivity: 91%
- F1: 14%

## Summary
Ensemble models, including the Balanced Random Forest Classifier and Easy Ensemble Classifier, demonstrated superior recall performance in high risk credit decisions when compared to the other models in the analysis. Despite this superior performance, these models still demonstrated low precision, making them potential liabilities in real-life situations. These models are unrealiable in their intended tasks and I would not recommend them for predicting credit risk

# Credit_Risk_Analysis

## Overview of the analysis
The purpose of this project is to predict credit card risk with the machine various learning techniques. 

## Result 
### Random Oversampler
![스크린샷(107)](https://user-images.githubusercontent.com/85276431/138642452-14b9c067-fbe7-4798-b6bd-e2c3cbd0bdb1.png)
Accuracy Score : 57%

High Risk Precision: 1%

High Risk Recall: 44%

### SMOTE
![스크린샷(108)](https://user-images.githubusercontent.com/85276431/138642781-71dfd6b0-60fa-4e2d-aae3-6a784b8ac92c.png)
Accuracy Score : 64%

High Risk Precision: 1%

High Risk Recall: 54%

### Cluster Centroids
![스크린샷(109)](https://user-images.githubusercontent.com/85276431/138642917-a74edb84-828a-42c6-9063-2c18ce8a735a.png)
Accuracy Score : 64%

High Risk Precision: 1%

High Risk Recall: 54%

### SMOTEENN
![스크린샷(110)](https://user-images.githubusercontent.com/85276431/138643262-6631e0fe-f690-4762-8972-18b3338b4214.png)
Accuracy Score : 65%

High Risk Precision: 1%

High Risk Recall: 70%

### Balanced Random Forest Classifier
![스크린샷(114)](https://user-images.githubusercontent.com/85276431/138643619-df8a4a8d-7c94-4319-b30b-6ec577a95a7a.png)
Accuracy Score : 68%

High Risk Precision: 88%

High Risk Recall: 37%

### Easy Ensemble AdaBoost Classifier
![스크린샷(115)](https://user-images.githubusercontent.com/85276431/138643781-b4da9ce0-dbad-4a34-99ce-81e34e8d38aa.png)
Accuracy Score : 68%

High Risk Precision: 88%

High Risk Recall: 37%

## Summary
All five models show below 70% of accuracy score. Thus, I could conclude prediction models are not suitable for predicting credit card risk. Easy Ensemble AdaBoost Classifier and Balanced Random Forest Classifier showed highest accuracy score of 68% among other models but not enough. If I have to use one of those models, I would choose either Easy Ensemble AdaBoost Classifier or Balanced Random Forest Classifier, but still need to find out more precise and accurate method to predict. 

# Credit-Card-Fraud-Detection
Fraudulent Credit Card transactions detection using PyCaret and other ML models

#### In this project we will be making predictions using Machine Learning Techniques, and Auto ML Technique to detect credit card fraud. Importantly, we'll be using PyCaret and balanced sampling. 

## Context 
#### Credit card fraud happens even with the current level of security inplace. This project aims to detect these fraudulent credit card activities based on transaction patterns so that such transactions are flagged and necessary mitigating factors are initiated to stop the transactions. By flagging these transactions, customers are not charged for items that they did not purchase.

## Dataset

### Source
 - https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

### Overview
##### The dataset contains transactions made by credit cards in September 2013 by European cardholders.

##### This dataset presents transactions that occurred within two days. We have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced.

##### This dataset contains only numerical input variables which are the result of a PCA transformation, 'Time', and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. 

## Tasks: 
- Data Analysis
- Feature Engineering
- Model Building and Prediction using ML Techniques
- Model Building and Prediction using PyCaret(Auto ML)

## Result ummary
We received an accuray of  99.96% which is atleast 0.01 % higher than most models avalable online. Also, the confusion matrix shows that our model is not overfitted. This number should not be surprising as our data was balanced towards one class. The accuracy in our credit card fraud detection when oversampling with SMOTE is used is 99.99% for both 'random forest' techniqueand NN architecture.
https://github.com/olalekanfayemi/Credit-Card-Fraud-Detection/blob/main/NN%20result.PNG

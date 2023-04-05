# Bank Marketing Campaign Project - by Amira Asta and Vatsal Mandalia
# Data Science Internship, Data Glacier

## Business problem:
A bank wants to increase its financial revenue stream and hence it is offering a term deposit plan to its existing clients to purchase. This will give a financial stability to the bank because of the cash inflow, and it will also be able to invest in any other financially lucrative scheme.

## Task:
Our task is to help the bank by building a classification model which predicts the chances of customers would opt for this product, and to understand the profile of such customers whom the bank's marketing team could target through different media channels.

## Project Workflow:
* Business understanding
* Data preparation - cleaning and transformation
* Exploratory Data Analysis - [View presentation](https://github.com/vatsalmandalia/Bank-Marketing-Campaign-DSEnthusiasts2021/files/11156009/EDA.presentation.pdf)
* Model selection and model building
* Results from the models
* Conclusion and recommendation

## Conclusion:
* Algorithms like Logistic Regression, K-Nearest Neighbors, Naive Bayes Classifier and Bagging and Boosting ensemble methods are used in model building process.
* Without scaling and hyperparameter tuning, Naive Bayes Classifier showed a better AUC score of 0.63 for default parameters. Similar process done for ensemble algorithms with result indicating Gradient Boosting performing better against others.
* Scaled the data using StandardScaler and enhanced performance of Gradient Boosting Classifier to 0.80 AUC score. 

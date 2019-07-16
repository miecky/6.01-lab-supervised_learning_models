# 6.01-lab-supervised_learning_models


#### Define the Problem
In this lab, I leveraged data in order to identify potential customers for financial institutions. Specifically, I used regression models and classificaiton models to find the important features for predicting potential customers' incomes and 401k eligibilities, respectively.

#### Data
[./401ksubs.csv]

#### Methodology

**Regression models** for predicting income include:

- multiple linear regression model without regularization
- lasso regression
- ridge regression
- k-nearest neighbors model
- decision tree
- set of bagged decision trees
- random forest
- Adaboost model
- support vector regressor

**Classification models** for predicting 401k eligibility include:

- logistic regression model
- k-nearest neighbors model
- decision tree
- set of bagged decision trees
- random forest
- Adaboost model
- support vector classifier

#### Findings

Net Financial Assets and marital status are two dominating features for predicting one's income. However, because the R2 score is low, additional feature study is recommended.

Net financial assets and income are two dominating features for predicting 401k eligibility.

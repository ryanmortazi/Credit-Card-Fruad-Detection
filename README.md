# How to deal with imbalanced data in a classification problem?

## Recognizing fraudulent credit card transactions: 
You can download the dataset from here --> https://drive.google.com/file/d/1cuv4l1kcIeVaGuPWrYRMXwoHr6zaOBVN/view?usp=sharing
## Dataset Details:
The datasets contains transactions made by credit cards in September 2013 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
## Objective:
In this notebook, we want to identify fraudulent credit card transactions. Also, in this notebook it will demonstrated how use underbalancing technique to tackle imbalanced data and how to measure the accuracy using the Area Under the Precision-Recall Curve (AUPRC)

## Challenge:
The class is highly imbalanced ratio.

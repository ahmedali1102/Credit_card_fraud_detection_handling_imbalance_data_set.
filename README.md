video explanation of the above project 
https://1drv.ms/v/c/46e17f20539c6739/ETnVT6kbsM1LpgqqZxb1TxoBNPazBRmOPaFoeL4Lip1KWA?e=Kx83T6

# Handling Imbalance data 

This file contain 3 ways to treat the imbalance data which means the majority of data is the target variable or dependent variable is more then the minority class  

## Introduction
The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation.

Due to confidentiality issues, there are not provided the original features and more background information about the data.

Features V1, V2, ... V28 are the principal components obtained with PCA;
The only features which have not been transformed with PCA are Time and Amount. Feature Time contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature Amount is the transaction Amount, this feature can be used for example-dependant cost-senstive learning.
Feature Class is the response variable and it takes value 1 in case of fraud and 0 otherwise.

I didn't uploaded the data because the file exceed more than 25 mb 
you can get the data from here :- https://www.kaggle.com/code/gpreda/credit-card-fraud-detection-predictive-models/input

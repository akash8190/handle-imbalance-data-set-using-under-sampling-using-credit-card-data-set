# handle-imbalance-data-set-using-under-sampling-using-credit-card-data-set
In this problem we simply balance the imbalance datasets using under sampling  technique

## credit card dataset


The datasets contains transactions made by credit cards in September 2013 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

dataset link  https://www.kaggle.com/mlg-ulb/creditcardfraud

## oversampling

Oversampling, which consists in over-sizing the minority class by adding observations


Visual explanation of under-sampling and over-sampling


![alt text]    ( https://miro.medium.com/max/620/1*yYMSLDHkxY_4OkPqQt7S0g.png)

       

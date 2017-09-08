# Credit-card-fraud-detection-system
We try to predict whether a credit card transaction is fraudulent or not based on the available data.
The datasets contains transactions made by credit cards in September 2013 by european cardholders.
The problem with this dataset is the imbalance in target variable. Only 492 transactions out of the total 284807 transactions, i.e  0.172% of the transactions are fraudulent ones, making it difficult to train our models.
I have used used various undersampling and oversampling techniques to solve this problem.
Individually, Tomeks link and repeated edited nearest neighbour undersampling were the best with f1-score of 0.81 and 0.79 for the minority class.
A combination of SMOTE oversampling and repeated edited nearest neighbour gave me and f1-score of 0.82 for the minority class.

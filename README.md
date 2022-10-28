# Online-Transaction-Fraud-Detection

## Aim
Develop a model for predicting fraudulent transactions for a financial company and use insights from the model to develop an actionable plan.

## Dataset
https://www.kaggle.com/datasets/miznaaroob/fraudulent-transactions-data

## About Dataset

The below column reference:

step: represents a unit of time where 1 step equals 1 hour
type: type of online transaction
amount: the amount of the transaction
nameOrig: customer starting the transaction
oldbalanceOrg: balance before the transaction
newbalanceOrig: balance after the transaction
nameDest: recipient of the transaction
oldbalanceDest: initial balance of recipient before the transaction
newbalanceDest: the new balance of recipient after the transaction
isFraud: fraud transaction

Data for the case is available in CSV format having 6362620 rows and 11 columns

## Content
First I imported all the required libraries and dataset for this project. Then I did some EDA to find which mode of transaction results into most fraudulent transactions. Then I worked throught to treat any inconsistency in the data. Then I proceeded to build the model.

### Libraies
1.Pandas - for data analysis

2.Numpy - for data analysis

3.matplotlib - for data visualization

4.seaborn - for data visualization




## Conclusion

I worked on xgboost model to classify Fraudulent and Non fraudulent transactions and I observed an accuracy of 0.9981.

I was successfully able to find the most accurate model to detect fraudlent transactions.

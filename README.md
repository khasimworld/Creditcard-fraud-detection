# Creditcard-fraud-detection



Kaggle data set was used to predict fraud transactions. 
L1-regularized logistic regression has a 97.36% chance of distinguishing between a positive class observation and a negative class one.

Data set used: https://www.kaggle.com/mlg-ulb/creditcardfraud

The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

![Credit](https://github.com/shaikkhasim/Creditcard-fraud-detection/blob/master/Pics/credit.JPG)

<p align="center">
  <img  src="https://github.com/shaikkhasim/Creditcard-fraud-detection/blob/master/Pics/class.JPG">
</p>


## Algorithm used: 

Loistic regression (L1 & L2)

## Model Evaluation Metrics

### ROC
<p align="center">
  <img src="https://github.com/shaikkhasim/Creditcard-fraud-detection/blob/master/Pics/roc.JPG">
</p>

### Precision-Recall Curve
<p align="center">
  <img  src="https://github.com/shaikkhasim/Creditcard-fraud-detection/blob/master/Pics/pr%20curve.JPG">
</p>

### F1-Score
<p align="center">
  <img  src="https://github.com/shaikkhasim/Creditcard-fraud-detection/blob/master/Pics/f1%20score.JPG">
</p>

### Confusion matrix
<p align="center">
  <img  src="https://github.com/shaikkhasim/Creditcard-fraud-detection/blob/master/Pics/confusion.JPG">
</p>


#### From the confusion matrix, we see that the Logistic Regressor got the following results:

Out of the 113299 actual instances of 'Not fraud', it predicted correctly 113282 of them.

Out of the 192 actual instances of 'Fraud', it predicted correctly 111 of them.

###### There will be a continuous improvement to this model based on the knowledge I again in the future.

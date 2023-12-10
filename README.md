# Predicting-sale-price
## 🚜 Predicting the sale Price of bulldozer-price-regression¶
Machine Learning project with the gold of predicting the sale price of bulldozers.

1. Promblem difination
How well can we predict the future sale price of a bulldozer,given its characteristics and previous examples of how similar bulldoxers have been sold for?

2. Data
The data dowloaded from the Kaggle Bluebook for Bulldozers Competition: https://www.kaggle.com/competitions/bluebook-for-bulldozers/data

Train.csv is the training set, which contains data through the end of 2011.
Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.
3. Evaluation
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

Note:The goal for most regression evaluation metrics is to minimize the error.For example,our goal for this project will be to build a machine learning model which minimises RMSLE.

4. Features
Kaggle provide a date dictionary detailing all of the feature of the dataest . You view this data dictionary on Google sheets

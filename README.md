# ADS505-finalproject
We used a Marketing Campaign dataset from Kaggle and used it to tailor digital marketing.

## Our main objective:
Apply various predictive modeling methods to our data, to predict which customers are likely to buy the company’s products, after various marketing campaigns. 

## Our main goals are:
 To create a predictive model that identifies customers that are likely and not likely to buy products
increase overall profits by only sending marketing to customers likely to buy
This also increases customer satisfaction by not receiving marketing messages for the products of least interest.

## Pre-processing and Modeling
The dataset was pretty much clean, we did make a couple of changes like changing the year_birth to the age column, and the Dt_customer to Days since enrollment. 
Used this dataset to run couple of logistic regression models and decided on the final number of predictors for our model training. 

Models trained and ran: 
Logistic Regression, Random Forest, Decision Trees, KNN, Ada Boost, LDA 
Compared accuracy, precision, recall and the confusion matrices as our performance metrics.
Logistic Regression performed the best.
The probability of responses were studied and revenue was calculated for different probability thresholds to which the marketing campaigns can be sent.



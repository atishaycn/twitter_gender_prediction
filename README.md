# twitter_gender_prediction

- Implementing a machine learning solution to predict the gender of a user using their user profile and some of their tweets
-	Performing steps like feature extraction, feature selection and, text normalization to get better results from the dataset
-	Utilizing cross-validation and ensemble methods(boosting) to obtain better predictive performance and build a robust model


Download the data file and the ipython notebook. Place them in the same directory and run the commands in the notebook. 

You can try out different analysis by using one of the following & modifying the cell:

1) - df1 = dfRead[dfRead.tweet_gender.isin(['male', 'female'])]

2) - df1 = dfRead[dfRead.tweet_gender.isin(['male', 'female', 'brand'])]

3) - df1 = dfRead[dfRead.tweet_gender.isin(['male', 'brand'])]

4) - df1 = dfRead[dfRead.tweet_gender.isin(['female', 'brand'])]



![Alt text](https://raw.githubusercontent.com/atishaycn/twitter_gender_prediction/master/logistic_regression_important_features_female.png "Top distinguishing features to predict user is female")

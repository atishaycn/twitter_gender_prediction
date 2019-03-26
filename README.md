# twitter_gender_prediction

This is a personal project for one of my courses during my master studies. The goal is to predict twitter user's gender based on their Twitter profile and tweets content. The first step was to clean and explore the data. There were three variables in gender: Male, Female, Brand. Brand representing that the account is of a company rather than a person. This was followed by a lot of exploratory data analysis and Data Visualization to really understand the data before starting with predictive modeling. Once I had enough feel of the data, I started with natural language processing on the user's bio and their tweets as well to extract useful features. After extracting these features, I began the process to visualize them. This led me to choose the features that might be important for my predictive model. I ran various algorithms with parameter tuning for the different combination of my features to reach a maximum of ~71% accuracy which was amongst the best with other research on this topic. In the end, I looked at the most important factors which differentiate Male & Female, Person(Male + Female) & Brand and discovered interesting insights. 

- Implemented a machine learning solution to predict the gender of a user using their user profile and some of their tweets
-	Performed steps like feature extraction, feature selection and, text normalization to get better results from the dataset
-	Utilized cross-validation and ensemble methods(boosting) to obtain better predictive performance and build a robust model


Download the data file and the ipython notebook. Place them in the same directory and run the commands in the notebook. 

You can try out different analysis by using one of the following & modifying the cell:

1) - df1 = dfRead[dfRead.tweet_gender.isin(['male', 'female'])]

2) - df1 = dfRead[dfRead.tweet_gender.isin(['male', 'female', 'brand'])]

3) - df1 = dfRead[dfRead.tweet_gender.isin(['male', 'brand'])]

4) - df1 = dfRead[dfRead.tweet_gender.isin(['female', 'brand'])]



Top distinguishing features to predict user is female

![Alt text](https://raw.githubusercontent.com/atishaycn/twitter_gender_prediction/master/logistic_regression_important_features_female.png "Top distinguishing features to predict user is female")






Top distinguishing features to predict user is male

![Alt text](https://raw.githubusercontent.com/atishaycn/twitter_gender_prediction/master/logistic_regression_important_features_male.png "Top distinguishing features to predict user is male")


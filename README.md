# Twitter-sentiment-analysis

Here is how a sample output looks like when above program is run:

Positive tweets percentage: 22 %
Negative tweets percentage: 15 %


Positive tweets:
RT @JohnLebron: Amazing—after years of attacking Donald Trump the media managed
to turn #InaugurationDay into all about themselves.
#Make....
RT @vooda1: CNN Declines to Air White House Press Conference Live YES! 
THANK YOU @CNN FOR NOT LEGITIMI…
. @realdonaldtrump #Syria #Mexico #Russia & now #Afghanistan. 
Another #DearDonaldTrump Letter worth a read @AJEnglish 


Negative tweets:

RT @Slat: Donald Trump’s administration: “Government by the worst men.” 
RT @RVAwonk: Trump, Sean Spicer, etc. all lie for a reason. 
Their lies are not just lies. Their lies are authoritarian propaganda.  
RT @KomptonMusic: Me: I hate corn 
Donald Trump: I hate corn too


We follow these 3 major steps in our program:

Authorize twitter API client.

Make a GET request to Twitter API to fetch tweets for a particular query.

Parse the tweets. Classify each tweet as positive, negative or neutral.

Now, let us try to understand the above piece of code:

First of all, we create a TwitterClient class. This class contains all the methods to interact with Twitter API and parsing tweets. We use __init__ function to handle the authentication of API client.
Finally, parsed tweets are returned. Then, we can do various type of statistical analysis on the tweets. For example, in above program, we tried to find the percentage of positive, negative and neutral tweets about a query.

Full Code Explanation:
This code first creates a Random Forest Regressor Object :
then Separates class label (train) and attributes (target) from the dataset.

Fits the model on the train data set and targets the predicted AQI value.

Model Configuration

Utilizes RandomForestRegressor algorithm with bootstrap sampling.

Important parameters like ccp_alpha and max_depth are explained.

Fine-tune model settings for impurity reduction and feature usage.

Sales Prediction

Further application with a RandomForestRegressor for sales prediction.

Parameters like bootstrap, criterion, max_depth, and max_features explained.

Specifies min_impurity_decrease and min_impurity_split for controlling model behavior.

AdaBoost Regressor

Imports necessary modules for AdaBoostRegressor.

Model configuration using AdaBoostRegressor with a random forest base estimator.

Explains parameters such as learning_rate, loss, and n_estimators.

Fits the model using gradient descent algorithm for 50 training iterations.


# Twitter-sentiment-analysis

Random Forest and AdaBoost Regressor for Air Quality Prediction :
Creates a RandomForestRegressor object to predict air quality index (AQI) values.
Separates class label (train) and attributes (target) from the dataset.
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

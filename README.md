# supervised-machine-learning-challenge


Predict Model Performance:
You will be creating and comparing two models on this data: a Logistic Regression, and a Random Forests Classifier.

Process: 
After loading in the imports, I imported in the csv data using Pandas. I created a prediction for model performance betweeen the two models (Logistic Regression and Random Forests Classifier). My initial prediciton was that the Random Forests Classifier would perform the best out of the two models, due to its relieance on esemble learning (takes random samples and has many decision tress) and emphasis on feature selction (aids in elimnating unimportant variables).

First, I defined the feature and target sets, then split the data into x_train, x_test, y_train and y_test. 

To run the linear regression model, I imported the sklearn.lindear_model for logistic regression and fit the training data. I validated the model by printing the training and testing score. 

I repeated the same process, thsi time importing sklearn.ensemble for the random forest classifier. After this, I ran the model and printed the training and test scores. 

In conclusion, I found that the The Linear Regression model performed better because of slightly higher score, although highly similar. My prediction of the Random Forest Classifier model was not correct, however both models had high performing scores of over 99%.

# credit-card-fraud-detection
Using logistic regression to identify fraudulent transactions  in credit cards

Data used: https://www.kaggle.com/dalpozz/test-different-sampling-techniques/data

Key steps:
- import the key libraries pandas, scikit-learn
- split data into features and target
- shuffle data into training and testing sets using Stratified Shuffle Split method in scikit-learn
- normalize data: Make the distribution of the values of each variable similar by subtracting 
    the mean and by dividing by the standard deviation
- Train the logistic regression model on testing data
- Now fit and predict the model on training data
- Print the classification report

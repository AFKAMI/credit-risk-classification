# credit-risk-classification
![149666189-fbae54b6-b123-4905-8348-e59ec94cdb1c](https://github.com/AFKAMI/credit-risk-classification/assets/126113162/a4e7fadc-5708-4844-908e-c2d1aaff0ec6)

# Background
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

# Split the Data into Training and Testing Sets

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

Split the data into training and testing datasets by using train_test_split.


# Create a Logistic Regression Model with the Original Data


Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by generating a confusion matrix.

Print the classification report.

# Credit Risk Analysis Report

1. purpose of this analysis is to evaluate the credit risk and by using a machine learning model to determine the risk of loan approval.  
2. describe the accuracy score, the precision score, and recall score of the machine learning model.
   * Accuracy score of 95.20% tells  how many times the ML model was correct overall comapre.
   * Precision of 92% is how good the model is at predicting the 0 is healthy loan and 1 is high-risk loan. 
   * Recall score of 95% tells how many times the model was able to detect a loan risk. 
3. Summary the results from the machine learning model.
based on accuracy score of 95% I would recommend this model to predict the loan risk. we can evaluate the customers risk factor for determination of loan eligibility based on number 1 (healthy loan) vs 0 (high_risk loan)

# credit-risk-classification
Data Bootcamp Week 20 HW

# Purpose of the analysis: 
The purpose of the analysis is to train and evaluate a model based on loan risk. With this model a peer-to-peer lending service company can indentify the creditworthiness of borrowers. 

# The dataset: 
The dataset consisted of 77,536 loans. Columns included were 'loan_size', 'interest_rate', 'borrower_income', 'debt_to_income', 'num_of_accounts', 'derogatory_marks', 'total_debt', and 'loan_status'. Loan Status is the prediciton the system is predicting and the remaining columns will assist with making these predicitons. 

# Stages of Process
- Prepare the data by importing the file, establishing and reading the dataframe, understandingg the information of the file, desribing the various data from the dataframe, and value_counts of loan_status column. 
- Then create a scaler to fit the machine learning model better. 
- Seperate the data for x and y labels. 
- Use the train_test_split to split the data. 
- Define a doClassification to assist with the learning model. 
- Import the machine learning model with LogisticRegression.
- Initiate the model. 
- Fit the model. 
- Use the model for predictions. 
- Evaluate predictions. 

# Machine Learning Methods Used: 
- LogisticRegression
- Train_test_split
- RandomForest
- KNeighborsClassifier
- Confusion Matrix

# Results: 
- Accuracy Score: 1.0
- Precision: 0: 1.0 , 1: 1.0
- Recall: 0: 1.0 , 1: 1.0

# Summary
According to the results of the model this is a well performed model with full acuracy. This does concern me with the 1.0 accuraacy in that there may be an error somewhere within the scaler or the linear regression. 

Both classes had a precision and a recall in 1.0. Although this shows a promising model it would be necessary to compare to other dataset to ensure accruacy. 
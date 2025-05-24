# credit-risk-classification
Code sources: Chat_GPT, Expert Learning, Class solutions
Overview of the Analysis
Purpose:
The goal of this analysis was to see if a machine learning model could accurately predict whether someone would get approved for a loan based on their financial information.

Data Information:
The dataset included details like borrower income, loan size, interest rate, total debt, debt-to-income ratio, number of accounts, and derogatory marks. We used this financial data to predict the loan_status.

What We Were Predicting:
The loan_status column had binary values — 0 for loans that were not approved, and 1 for loans that were approved. Most of the loans in the dataset were not approved, so the data was a little imbalanced.

Steps in the Machine Learning Process:

Loaded the data into Python using Pandas.

Separated the features (X) from the target variable (loan_status, y).

Split the data into training and testing sets using train_test_split.

Trained a logistic regression model using the training data.

Made predictions on the test data.

Evaluated the model using accuracy, precision, recall, and a confusion matrix.

Method Used:
We used LogisticRegression from the sklearn library. This model is commonly used for binary classification problems — in this case, predicting whether a loan would be approved (1) or not (0).

Results
Model Used: Logistic Regression

Accuracy: 99%

Precision:

Class 0 (not approved): 100%

Class 1 (approved): 85%

Recall:

Class 0: 99%

Class 1: 91%

Summary
The logistic regression model performed very well, with a 99% accuracy score. It was excellent at identifying when a loan shouldn't be approved (class 0) and performed reasonably well at recognizing approved loans (class 1).

Recommended model: Logistic Regression — it's accurate, simple, and effective for this type of binary classification task.


# Credit_Risk_Analysis

Results:

The naive random oversampling has an accuracy score of 64.3%, a precision of nearly 100%, and a recall of 69%.

The smote oversampling algorithm has an accuracy score of 64.7% with a precision of nearly 100% and a recall of 73%.

The cluster centroid method, an undersampling method, has an accuracy score of 64.7% with precisions and recall of nearly 100% and 52% respectively.

Instructions
Deliverable 1: Use Resampling Models to Predict Credit Risk
Using your knowledge of the imbalanced-learn and scikit-learn libraries, you’ll evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. First, you’ll use the oversampling RandomOverSampler and SMOTE algorithms, and then you’ll use the undersampling ClusterCentroids algorithm. Using these algorithms, you’ll resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

Follow the instructions below and use the credit_risk_resampling_starter_code.ipynb file to complete Deliverable 1.

Open the credit_risk_resampling_starter_code.ipynb file, rename it credit_risk_resampling.ipynb, and save it to your Credit_Risk_Analysis folder.

Using the information we’ve provided in the starter code, create your training and target variables by completing the following steps:

Create the training variables by converting the string values into numerical ones using the get_dummies() method.
Create the target variables.
Check the balance of the target variables.

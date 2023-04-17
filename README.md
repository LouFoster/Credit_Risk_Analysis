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

![image](https://user-images.githubusercontent.com/117233641/232632372-b3807bf5-77dd-44bc-86c7-975b86cce367.png)

Create the target variables.

Check the balance of the target variables.

![image](https://user-images.githubusercontent.com/117233641/232632610-9bca2ad3-7807-48bf-a678-580101679a95.png)


Next, begin resampling the training data. First, use the oversampling RandomOverSampler and SMOTE algorithms to resample the data, then use the undersampling ClusterCentroids algorithm to resample the data. For each resampling algorithm, do the following:

Use the LogisticRegression classifier to make predictions and evaluate the model’s performance.

Calculate the accuracy score of the model.

![image](https://user-images.githubusercontent.com/117233641/232632913-e80e0759-e70a-4751-a9aa-dfdd7087899c.png)


Generate a confusion matrix.

Print out the imbalanced classification report.

Save your credit_risk_resampling.ipynb file to your Credit_Risk_Analysis folder.


##Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk

Follow the instructions below and use the information in the credit_risk_resampling_starter_code.ipynb file to complete Deliverable 2.

1.)Continue using your credit_risk_resampling.ipynb file where you have already created your training and target variables.

2.) Using the information we have provided in the starter code, resample the training data using the SMOTEENN algorithm.

3.) After the data is resampled, use the LogisticRegression classifier to make predictions and evaluate the model’s performance.
Calculate the accuracy score of the model, generate a confusion matrix, and then print out the imbalanced classification report.

![image](https://user-images.githubusercontent.com/117233641/232633203-73b73b82-c0bb-41f4-912d-0aec90f9a696.png)
  
  

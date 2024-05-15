# Credit-Risk-Classification

## Overview of the Analysis
* The objective of this analysis is to employ diverse techniques for training and evaluating a model focused on loan risk. Additionally, we will utilize machine learning to analyze a historical lending dataset from a peer-to-peer lending services company. The goal is to construct a model capable of assessing the creditworthiness of borrowers.

* This dataset captures essential information related to loan applications, borrower characteristics, and credit risk.

![Screenshot 2024-05-14 204558](https://github.com/Seif-Ma/credit-risk-classification/assets/152819459/f383823e-8f5a-4bc6-9d11-4b98249fc85a)

* The Logistic Regression Algorithm is a highly effective tool for our machine learning model because it is commonly employed to estimate the probability of a target variable in classification tasks
* the stages of the machine learning process:
    * Data Splitting:
      -  The first step involves splitting the dataset into training and testing subsets.
     
    * Model Instantiation:
      -  Create an instance of the logistic regression model by using the LogisticRegression class.
    * Model Training (Fitting):
      -  With the model instantiated, we proceed to train it using our training data (X_train and y_train). The fit method adjusts the model’s coefficients based on the input features and corresponding target labels.
    * Evaluating Model Performance:
      -  Finally, create a pandas DataFrame to compare the predicted values (Prediction) with the actual target labels (Actual). This comparison allows us to assess how well the model performs on the test data.

## Results
![Screenshot 2024-05-14 212151](https://github.com/Seif-Ma/credit-risk-classification/assets/152819459/af8d1caa-1138-4e39-8330-ca90dbd904d5)  
* Healthy Loan `0`:
    - The presission for healthy loan is 1, which means that when the model predicts a loan as healthy, it is correct 100% of the time.
    - The recall for healthy loan is also 1, indicating that the model correctly identifies 100% of the actual healthy loans.
* High-risk loan `1`:
    - The precission for high-risk loans is 0.87, meaning that when the model predicts a loan as high-risk, it is correct 87% of the time.
    - The recall for high-risk loans is 0.95, indicating that the moddel correctly identifies 95% of the actual high-risk loans.

## Summary
In summary, the logistic regression model performs well in predicting both healthy loans and high-risk loans. The overall accuracy of 99% indicates strong performancce.

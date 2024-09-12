# Module 20 Report 

## Overview of the Analysis

**Purpose of the analysis** - The goal of this analysis to determine if the Logistic Regression machine learning model can more accurately predict healthy loans versus high-risk loans using the original dataset that is resampled to increase the size of the minority class. 
* Explain what financial information the data was on, and what you needed to predict. 
* **The Dataset** - The dataset used to perform the analysis consists of information on 77,536 loans. The data includes columns for loan size, interest rate, borrower income, debt to income ratio, number of accounts, derotatory marks, total debt, and loan status. The category that we are attempting to predict with our analysis is **loan status**. The data provided in the remaining columns will be used as features to train the data and inform the predictions. 
* **Stages of the Machine Learning Process** - The stages of the machine learning process are very scripted. if followed in order, they provide you with an accurate assessment of the model's ability to make predictions. The stages of the machine learning process are as follows: 

- Prepare the data - import the file, establish the DataFrame, evaluate the columns and features. 

- Separate the data into features and labels - The label are what you are attempting to predict, is the status of the loan healthy(0) or high-risk(1). The features are all of the remaining data you will use to train and test the model.

- Use the train test split function to separate the features and labels data into training and testing datasets. 

- import the machine learning model from the library - in this instance, we will be importing LogisticRegression from SKLearn. 
- Import the machine learning model to separate the features and labels data into training and testing datasets. 

- Import the machine learning model from the library - In this instance , we will be importing LogisticRegression from SKLearn
- Instantiate the model. 

- Fit the model using the training data. 

- Use the model to make predictions using the features test data.
 
- Evaluate the predictions - Evaluations using the features test data. 

- Evaluate the predictions - Evaluations are done by calculating and comparing metrics like accuracy score, a confusion matrix, and a classification report. 


**Machine Learning Methods Utilized** 
The primary model used in this analysis is:

- LogisticRegression model from SKLearn 

Supporting functions used in this analysis are: 

- train test split from SKLearn 

Models are evaluated using the following functions: 

- Confusion matrix from SKLearn 
- Classification report from SKLearn 

## Results 
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models. 

* Machine Learning Model - Logistic Regression: 
* ** Accuracy Scores: 99%
* **Precision Scores:**
	*Class 0 (Healthy Loans): 100%
	*Class 1 (High risk Loans): 85%
	**Recall Scores**
	*Class 0 (Healthy Loans): 100%
	*Class 1 (High risk Loans): 85%

## Summary

The model has a high rate in using the original data to predicting the values of the healthy loans. Precision was 100% and recall was 99%.

The model is pretty good at predicting the values of high risk loans, but not as good as predicting the healthy loans. Precision was 85% and recall was 91% 

Given this information, it appears that the Logistic Regression model does a great job at predicting both healthy and high risk loans, given the features that are used to train the data.

The module is recommended for you by the company.
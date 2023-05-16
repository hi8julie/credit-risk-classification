# credit-risk-classification
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

![shutterstock_567634105](https://github.com/hi8julie/credit-risk-classification/assets/118202453/afac630b-fc7e-4dc0-b887-d91a572765bf)


# Credit Risk Analysis Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of the analysis is to train and evaluate a model based on loan risk and build a model that can identify the creditworthiness of borrowers. 
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

* Logistic Regression Model:

<img width="299" alt="report 1" src="https://github.com/hi8julie/credit-risk-classification/assets/118202453/ca668f04-b160-48b7-9cde-c6d53f0620ec">


* Logistic Regression Model with Resampled Training Data:

<img width="255" alt="report 2" src="https://github.com/hi8julie/credit-risk-classification/assets/118202453/997d7fbd-5fef-408d-ba58-e24f4b9fd0d3">


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.


## Instructions
The instructions for this Challenge are divided into the following subsections:

- Split the Data into Training and Testing Sets
- Create a Logistic Regression Model with the Original Data
- Predict a Logistic Regression Model with Resampled Training Data
- Write a Credit Risk Analysis Report

## Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

1. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
2. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
3. Split the data into training and testing datasets by using train_test_split.

## Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

1. Fit a logistic regression model by using the training data (X_train and y_train).
2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
3. Evaluate the model’s performance by doing the following:
  - Calculate the accuracy score of the model.
  - Generate a confusion matrix.
  - Print the classification report.
4. Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

## Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.

Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:
 - An overview of the analysis: Explain the purpose of this analysis.
 - The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.
 - A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

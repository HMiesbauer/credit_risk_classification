# credit_risk_classification
Train and evaluate a model based on loan risk

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    *The purpose of the analysis was to create a model that would predict loan risk.

* Explain what financial information the data was on, and what you needed to predict.
    *The financial information the data was on credit loans. You needed to predict how often a low-risk loan would be issued versus a high risk loan.
  
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
    * The variables I was trying to predict were high-risk loans and low-risk loans 
  
* Describe the stages of the machine learning process you went through as part of this analysis.
    * Data preprocessing: scaling the data, splitting the data into training and testing data
    * Model selection: I selected LogisticRegression
    * Model training: the model was trained to detect patterns in the dataset
    * Model evaluation: the model was evaluated for its fitness in use for the dataset
  
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
    *In this model I used a LogisticRegression model. 

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy: The accuracy showed that the model classified 99% of the loans correctly
    * Precision: Precision was 1.0 for low-risk loans. This means all the predictions made for low-risk loans were correct. On the other hand, the prediction for high-risk loans was only 85% correct.
    * Recall scores: The model correctly identified 99% of the low-risk loans and 91% of the high-risk loans.

## Summary

Summarize the results of the machine learning model, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
    *Neither. The dataset was skewed toward low-risk loans thus the model did a poor job at predicting high-risk loans. 
  
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
    *I would agree that performance depends on the problem we're trying to solve. It's more important to predict the 1s because that's where your risk lies. Identifying the high-risk loans allows certain business decisions to be made such as how many loans is the business willing to potentially have default. Or what should the payment schedule be for the high-risk loan customers vs. the low-risk loan customers? Will the business allow a grace period for the high-risk loans? Will the business need to set higher rate terms for the high-risk loans?

If you do not recommend any of the models, please justify your reasoning.

# credit-risk-classification
Use various ML techniques to train and evaluate a model that identifies credit worthiness of borrowers.


## Overview
In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:
The purpose of this analysis is to classify loan applications as either Healthy of High-risk. These predictions were made based on the financial information provided.
  * Data:
      * Loan size
      * interest rate
      * borrower income
      * debt-to-income
      * number of accounts
      * derogatory marks
      * total debt
      * loan status
  In order to make these predictions a Logistic Regression model was trained on the provided data. Random oversampling was employed to deal with the unbalanced data, as there was much more data available for healthy loans compared to the high-risk category.
  Logistic Regression is a statistical model that determines the probability of an event taking place by having the log-odds for the event be a linear combination of one or more indepentant variables. The variables in this senario are list above under Data.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * For model one, the precision and accuracy for healthy loans was 1.00 and 0.99, respectively, versus 0.85 and 0.91 for high-risk loans.
  * The F1 score for healthy loans was 1.00 and it was 0.88 for high-risk loans
  * This model does very well at identify a healthy loan, but scores quite a bit lower when it comes to high-risk category
 
![image](https://github.com/StanJohn04/credit-risk-classification/assets/121142680/146d8808-e81b-42cf-8de2-be2d3e5059fb)




* Machine Learning Model 2:
  * For model one, the precision and accuracy for healthy loans was 1.00 and 0.99, respectively, versus 0.84 and 0.99 for high-risk loans.
  * The F1 score for healthy loans was 1.00 and it was 0.91 for high-risk loans
  * This model does very well at identify a healthy loan, but scores quite a bit lower when it comes to high-risk category
    
![image](https://github.com/StanJohn04/credit-risk-classification/assets/121142680/2cf9f29d-6dcc-462d-b8ed-2696fd2545c9)


## Summary
* Model 2 performs better, based on the classification reports for both models. 
* Because of this I would recommend using model 2 in order to predict the credit worthiness of borrowers. The higher F1 score for high-risk loans will make it slightly better at identify this class which is very important when determing credit worthiness. Model 2 also does veyr well at predicting healthy loans, meaning the small inconsistencies for high-risk loans can be offset by correctly predicting the healthy loans.

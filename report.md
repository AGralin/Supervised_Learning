# Module 12 Report Template

## Overview of the Analysis

* This analysis uses info about customers to see if we can predict if they will default on a loan or not.
* There is information regarding loan size, interest rate, income, debt to income, number of accounts, derogatory marks, and total debt.
* The variable that we wanted to predict was 'loan_status' where a 1 is a default.
* The analysis uses a LogisticRegression model, and 'RandomOverSampler' to resample the data.


## Results

* Machine Learning Model 1:
  * The first model worked very well at predicting those that did not default (f1 = 1.0), and moderatly well at predicting a default (f1 = .88). There is reason to believe the model is overfit because of an f1 score equal to one.



* Machine Learning Model 2:
  * The second model also did a very good job predicting those that did not default (f1 = 1.0). It also did a better job of predicting a default (f1 = .91)

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Both the models did well enough to predict defaults, but they both worked almost perfeclty at predicting those that did not default which means the data may have been overfit.
* Although, the thing we wanted to predict was the defaults. Both models did a good job of predicting for them (.88 and .91 respectively)
* I would recommend the second model because it was slightly more accurate (by 3 percent).

# Credit-Risk-Analysis
UW Fintech Bootcamp - Module 12 Challenge

---

## Overview of the Analysis

When evaluating customers for credit risk, we deal with very unbalanced data sets.  The fact of the matter is the majority of people and companies are not at a high risk of defaulting on credit, which makes it quite hard to build a model that will properly account for and help identify credit risks.  

* The purpose of this analysis is to build a model that will help identify potential credit risks.
* Using a dataset of more than 75,000 loans, we collected data about the loan size, debt to income ratio, number of accounts and the current status of loan (good standing or default).
* Since we are trying to predict whether a future loan will go into default, we are using loan status as the evaluation mark, and the remaining data is being used to craft the prediction.
* To conduct this evaluation and build the model we are using the traditional Model - Fit - Predict formula.
* We have decided to use the Logistic Regression Model on both the original, as well as the oversampled data.

## Results
As mentioned above we conducted 2 Machine Learning Models.  The first one of the standard data

* Machine Learning Model 1 (original data):
  * Balanced Accuracy Score - 95.2%  
  * Precision (Bad Loans) - 85%
  * Recall (Bad Loans) - 91%

* Machine Learning Model 2 (oversampled data):
  * Balanced Accuracy Score - 99.4%
  * Precision (Bad Loans) - 84%
  * Recall (Bad Loans) - 99% 

## Summary
Overall it appears that using the oversampled data will be a better litmus test for idenitfying bad loans:

* The oversampled data set had an improved Balanced Accuracy Score of nearly 400bp
* As mentioned above the data improvement is really noticably on the recall score for the bad loans where there was in increase from 91% to 98%

In a scenario such as this where we are looking to identify bad loans, with a data set similar to this, I would recommend utilizing a logistic regression model combined with oversampling the data.
---

## Contributors

The majority of this project has been done independently.

---

## License

Program is free to use without license.  Only request is that you notify author of use and application.
  
To discuss usage or general inquires please contact the author at jonm5214@gmail.com

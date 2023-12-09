# Credit-risk-classification

# Module 12 Report Template

## Overview of the Analysis

CREDIT RISK ANALYSIS REPORT

Overview

The main goal of this analysis is to train and evaluate a model that assesses loan risk. The dataset used in this project consists of historical lending activity from peer-to -peer lending services company. It includes various variables such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt and loan status.
To determine the creditworthiness of borrowers, a logistic regression model is being employed. This model categorizes borrowers as either high-risk (unhealthy loan/defaulting) or low-risk (healthy loan).
Model I created for this project the loan status was dependent variable (y), with loans being identified as either defaulting (1) or healthy (0). The remaining variable were used as predictors (x). Model had an imbalanced distribution between the outcomes. The model was trained and then evaluated for its performance.

Now let’s talk about the results. 

Results

1.	the balanced accuracy score achieved was 95%. This score takes into account both sensitivity (true positive rate) and specificity (true negative rate). It is great measure of the model’s performance, especially when dealing with imbalanced datasets. Since the dataset has a higher number of rejected loans (75,036) compared to accepted loans (2,500), it is considered imbalanced. In such cases the balanced accuracy score is a reliable metric to evaluate the model’s performance.
2.	Another measure of model’s performance is accuracy. My model achieved an accuracy score of 99%, meaning it correctly predicted 99% of all loans in the dataset.
3.	Looking at the confusion matrix, the model accurately accepted 18,663 healthy loans and rejected 563 high-risk-loans. However, it also incorrectly rejected 102 healthy loans and incorrectly accepted 56 high-risk-loans.
4.	Precision focusses on how well the predictions match reality while recall (or sensitivity) accesses how well reality matches predictions. For default loans my model achieved a precision score of 85% and a recall score of 91%. For healthy loans, the precision score is 100% and the recall score is 99%
5.	Lastly the F1 score, which is a weighted average of precision and recall, the score achieved is 88%.

Conclusion

Model has a balanced accuracy of 95%. I used balanced accuracy for this model because the distribution data between the healthy and default classes was not balanced.
In the model, I aimed to maximize the identification of low-risk loans as healthy and minimize the number of high-risk loans given out. Model accepted 56 high-risk loans. 
When considering F1 score, which takes into account both precision and recall, 88% was true for my model.

* Machine Learning Model:
  * Description of Model Accuracy, Precision, and Recall scores.
  
 References.
 https://fastercapital.com/startup-topic/Learning-and-Credit.html
 Data for this dataset was generated by edX Boot Camps LLC
 




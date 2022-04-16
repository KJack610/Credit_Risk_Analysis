Credit_Risk_Analysis
Overview of the loan prediction risk analysis:
The purpose of this analysis to apply machine learning to credit card risk, an unbalanced classification problem because of the number of good loans that outnumber risky loans. In this anlysis, both was oversampling and undersampling methods were used to build and evaluate models using resampling and compare models that reduce credit risk to predict redict risk.
Results:
Balance Score and Precision & Accuracy Scores
1. Naive Random Oversampling with RandomOverSampler
  a. balanced accuracy score: 66%
  b. high risk precision score: 1%. Recall: 74%
  c. low risk precision score: 100%. Recall: 58%
  d. Average precision score: 99%. Recall: 58%
2.  Oversampling with SMOTE
  a. balanced accuracy score: 65%
  b. high risk precision score: 1%. Recall: 62%
  c. low risk precision score: 100%. Recall: 68%
  d. Average precision score: 99%. Recall: 68%
3.  Undersampling  with ClusterCentroids
  a. balanced accuracy score: 59%
  b. high risk precision score: 1%. Recall: 64%
  c. low risk precision score: 100%. Recall: 53%
  d. Average precision score: 99%. Recall: 53%
4.  Combinational using SOMOTEEN
  a. balanced accuracy score: 64%
  b. high risk precision score: 1%. Recall: 72%
  c. low risk precision score: 100%. Recall: 57%
  d. Average precision score: 99%. Recall: 57%
5. Balanced Random Forest usign Balanced RandomForestClassifier
  a. balanced accuracy score: 78%
  b. high risk precision score: 3%. Recall: 57%
  c. low risk precision score: 100%. Recall: 88%
  d. Average precision score: 99%. Recall: 88%
6. Enesemble with Easy EnsemebleClassifier
  a. balanced accuracy score: 92%
  b. high risk precision score: 9%. Recall: 89%
  c. low risk precision score: 100%. Recall: 94%
  d. Average precision score: 99%. Recall: 94%


Summary:
There is a summary of the results
The accurracy scores for the first modules were less than 75%, bwetween 59% and 64%. The undersampling models had accuracy scores were less than the first four models. The accurracy scores for the 5th and 6th models were the highest.
Recommendation: 
Best mdoel to use is the esemble model because it had the highest accuracy score and the highest average recall score. 

# Credit_Risk_Analysis

## Overview of the loan prediction analysis:
- Loan prediction using the machine learning techniques we trained the machine with the previous dataset. so, machines can analyze and understand the process. Then we train the machine and evaluate models to predict the credit risk.  In this case, we use several machine learning models and different techniques to create a training and test group from a given dataset and implement the logistic regression, decision tree, random forest, and SVM algorithms by adopting the following procedure. 

   - Oversampling the data using the RandomOverSampler and SMOTE algorithms and Undersampling the data using the ClusterCentroids algorithms. 
   - Use a combinational approach to oversampling and undersampling using SMOTEENN algorithm.
   - Compare the two machine learning models to reduce the risk BalancedRandomForestClassifier and EasyEnsembleClassifier.

## Results: 

## Summary: 
- The highest compared balanced accuracy between 0 and 1 to the closest 1 is the best machine learning model. All the models used to perform the credit risk analysis show weak precision in determining if credit risk is high. The Ensemble models brought a lot more improvement, especially in the sensitivity of the High-risk credits. The EasyEnsembleClassifier model shows a recall of 93% so it detects almost all high-risk credit. 

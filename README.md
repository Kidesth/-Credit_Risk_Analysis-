# Credit_Risk_Analysis

## Overview of the loan prediction analysis:
- Loan prediction using the machine learning techniques we trained the machine with the previous dataset. so, machines can analyze and understand the process. Then we train the machine and evaluate models to predict the credit risk.  In this case, we use several machine learning models and different techniques to create a training and test group from a given dataset and implement the logistic regression, decision tree, random forest, and SVM algorithms by adopting the following procedure. 

   - Oversampling the data using the RandomOverSampler and SMOTE algorithms and Undersampling the data using the ClusterCentroids algorithms. 
   - Use a combinational approach to oversampling and undersampling using SMOTEENN algorithm.
   - Compare the two machine learning models to reduce the risk BalancedRandomForestClassifier and EasyEnsembleClassifier.

## Results: 
![random over sampling](https://user-images.githubusercontent.com/107454933/204739118-48bb2630-caba-4bb9-8c17-8323f86fb66b.png)
![SMOTE oversampling](https://user-images.githubusercontent.com/107454933/204739165-8fdef8c7-10a2-472b-a20a-62f95cbbce61.png)
![Undersampling pngscore](https://user-images.githubusercontent.com/107454933/204739183-ec20f1d1-afbf-4912-afd0-559c364f5789.png)
![combined over and Under sampling](https://user-images.githubusercontent.com/107454933/204739221-7022b16f-77c7-4514-9053-6ee0fe04200d.png)
![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/107454933/204739248-a0d816fe-3c05-453f-a5dd-d508ea766919.png)
![Easy Ensemble AdaBoost classifier](https://user-images.githubusercontent.com/107454933/204739278-cdc08ce6-3d3e-4698-ad94-399cdc6ca96f.png)


## Summary: 
- The highest compared balanced accuracy between 0 and 1 to the closest 1 is the best machine learning model. All the models used to perform the credit risk analysis show weak precision in determining if credit risk is high. The Ensemble models brought a lot more improvement, especially in the sensitivity of the High-risk credits. The EasyEnsembleClassifier model shows a recall of 93% so it detects almost all high-risk credit. 

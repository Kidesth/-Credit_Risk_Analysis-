# Credit_Risk_Analysis

## Overview of the loan prediction analysis:
- Loan prediction using the machine learning techniques we trained the machine with the previous dataset. so, machines can analyze and understand the process. Then we train the machine and evaluate models to predict the credit risk weather the application was consider "Low" or "High" risk. In this case, we use several machine learning models and different techniques to create a training and test group from a given dataset and implement the logistic regression, decision tree, random forest, and SVM algorithms by adopting the following procedure. 

   - Oversampling the data using the RandomOverSampler and SMOTE algorithms and Undersampling the data using the ClusterCentroids algorithms. 
   - Use a combinational approach to oversampling and undersampling using SMOTEENN algorithm.
   - Compare the two machine learning models to reduce the risk BalancedRandomForestClassifier and EasyEnsembleClassifier.

## Results: 

### Naive Random Oversampling
![random over sampling](https://user-images.githubusercontent.com/107454933/204739118-48bb2630-caba-4bb9-8c17-8323f86fb66b.png)
  - Balance Accuracy Score : 0.6390117682133347
  - The "High risk" percision rate was only 1% with the recall 61% giving the model F1 score was 2%
  - The "low risk" percision rate of 100% with the recall 67%.
   
### SMOTE(Synthetic Minority Oversampling Technique) Model  
![SMOTE oversampling](https://user-images.githubusercontent.com/107454933/204739165-8fdef8c7-10a2-472b-a20a-62f95cbbce61.png)
  - Balance Accuracy Score : 0.631475841119048
  - The "High risk" percision rate was only 1% with the recall 61% giving the model F1 score was 2%
  - The "low risk" percision rate of 100% with the recall 65%.
  
### Undersampling (Cluster Centroids algorithm)
![Undersampling pngscore](https://user-images.githubusercontent.com/107454933/204739183-ec20f1d1-afbf-4912-afd0-559c364f5789.png)
  - Balance Accuracy Score : 0.631475841119048
  - The "High risk" percision rate was only 1% with the recall 61% giving the model F1 score was 1%
  - The "low risk" percision rate of 100% with the recall 57%.
   
### Combination Oversampling and Under Sampling(SMOTEENN)
![combined over and Under sampling](https://user-images.githubusercontent.com/107454933/204739221-7022b16f-77c7-4514-9053-6ee0fe04200d.png)
 - Balance Accuracy Score : 0.590320332297924
 - The "High risk" percision rate was only 1% with the recall go up 70% giving the model F1 score was 2%
 - The "low risk" percision rate of 100% with the recall 57%.
  
### Balanced Random Forest Classifier
![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/107454933/204739248-a0d816fe-3c05-453f-a5dd-d508ea766919.png)
 - Balance Accuracy Score : 0.7877672625306695
 - The "High risk" percision rate was only 4% with the recall go up 67% giving the model F1 score was 7%
 - The "low risk" percision rate of 100% with the reca 91%.
  
### Easy Ensemble AdaBoost Classifier
![Easy Ensemble AdaBoost classifier](https://user-images.githubusercontent.com/107454933/204739278-cdc08ce6-3d3e-4698-ad94-399cdc6ca96f.png)
 - Balance Accuracy Score :0.925427358175101
 - The "High risk" percision rate was only 7% with the recall go up 91% giving the model F1 score was 14%
 - The "low risk" percision rate of 100% with the reca 94%.

## Summary: 
- The highest compared balanced accuracy between 0 and 1 to the closest 1 is the best machine learning model. All the models used to perform the credit risk analysis show weak precision in determining if credit risk is high. The Ensemble models brought a lot more improvement, especially in the sensitivity of the High-risk credits. The EasyEnsembleClassifier model shows a recall of 93% so it detects almost all high-risk credit. 

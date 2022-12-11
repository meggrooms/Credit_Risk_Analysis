# Credit Risk Analysis
Predicting credit risk using Machine Learning models
----

Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
  
----
### Overview

The credit industry can be very risky, classifying potential customers as a good or poor risk is vital to the financial health of the credit provider. In this module I used various libraries and algorithms to build and evaluate models to predict each person's credit risk. These include:
<br>
• imbalanced-learn<BR>
• scikit-learn<BR>
• RandomOverSampler<BR>
• SMOTE algorithms<BR>
• ClusterCentroids algorithm<BR>
• SMOTEENN algorithm<BR>
• BalancedRandomForestClassifier<BR>
• EasyEnsembleClassifier<BR>

<BR>
  
----  
### **Results**
The respective balanced accuracy, precision, and recall scores for each model are as follows: 
<br><BR>
  
<strong>Splitting Data Into Training & Testing Samples</strong>
<BR><BR><br>
<img src ="https://github.com/meggrooms/Credit_Risk_Analysis/blob/main/images/image_01_train_test.png">
  <BR><BR>
    
**Naive Random Oversampling**
<BR><BR><br>
<img src="https://github.com/meggrooms/Credit_Risk_Analysis/blob/main/images/resample_Native_Random_Oversample%20(1).png?raw=true">
<BR>
• Balanced Accuracy: 0.66<BR>
  <br><BR>
  

**SMOTE Oversampling**
 <BR><BR><BR>
<img src="https://github.com/meggrooms/Credit_Risk_Analysis/blob/main/images/Resample_02_SMOTE_oversample.png">
<BR>
• Balanced Accuracy: 0.64
  
<BR><BR>
  
  

**ClusterCentroids**
 <BR><BR><BR>
<img src="https://github.com/meggrooms/Credit_Risk_Analysis/blob/main/images/ClusterCentroids.png">
<BR>
• Balanced Accuracy: 0.53
<br><BR>
  
  
  
**SMOTEEN**
<BR><BR><BR>
<img src="https://github.com/meggrooms/Credit_Risk_Analysis/blob/main/images/Resample_04_Combo_sampling.png">
<BR>
• Balanced Accuracy: 0.53
<BR><BR>
  
  
**RandomForest Classifier Priority**
<BR><BR><BR>
<img src="https://github.com/meggrooms/Credit_Risk_Analysis/blob/main/images/image_02_RandomForest.png">
<BR>
• Balanced Accuracy: 0.79
<BR><BR>
    
  
  
**Easy Ensemble AdaBoost Classifier**
<BR><BR><BR>
<img src = "https://github.com/meggrooms/Credit_Risk_Analysis/blob/main/images/image_03_easy%20ensemble_AdaBoost%20(1).png">
<BR>
• Balanced Accuracy: 0.93
<BR><BR>  
  
  
    
----  
### Summary
Balanced accuracy spands from 0-1, with 1 being the perfect prediction. Based on the models I ran, **the Easy Ensemble AdaBoost Classifier was most accurate** with a balanced accuracy of 0.93. The other models have a balanced accuracy of under 0.80, making them far less accurate as they are not as close to 1 as the EEABC.
  
  
When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model. For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were below .80 balanced accuracy. The precision for all models were similar and within an appropriate range. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the final best machine learning model to choose for further credit card analysis  
  
  
  
  
  
  
  
  
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
<br>  
  
  
  
  
  
  
  
  
  
  
  

# Credit_Risk_Analysis

## Overview of Analysis

The objective of this exercise was to apply different machine learning models to solve the real world challenge of credit card risk. In doing so, we tested credit risk using the following machine learning techniques:

 - Naive Random Oversampling
 - SMOTE Oversampling
 - Undersampling
 - SMOTEENN
 - Balanced Random Forest Classifier
 - Easy Ensemble AdaBoost Classifier


## Results

| Machine Learning Model | Accuracy | Precision | Recall | F1 |
| ---------------------- | -------- | --------- | ------ | -- |
| Naive Random Oversampling | .62 | .99 | .62 | .76 |
| SMOTE | .69 | .99 | .69 | .81 |
| Undersampling | .40 | .99 | .40 | .56 |
| SMOTEENN | .57 | .99 | .57 | .72 |
| Balanced Random Forest Classifier | .79 | .99 | .87 | .93 |
| Easy Ensemble AdaBoost Classifier | .93 | .99 | .94 | .97


### Naive Random Sampling

![Naive](https://github.com/jzaragoza21/Credit_Risk_Analysis/blob/main/Naive_Random_Oversampler.PNG)

### SMOTE

![SMOTE](https://github.com/jzaragoza21/Credit_Risk_Analysis/blob/main/SMOTE.PNG)

### Undersampling

![Undersampling](https://github.com/jzaragoza21/Credit_Risk_Analysis/blob/main/Undersampling.PNG)

### SMOTEENN

![SMOTEENN](https://github.com/jzaragoza21/Credit_Risk_Analysis/blob/main/SMOTEENN.PNG)

### Balanced Random Forest Classifier

![Forest](https://github.com/jzaragoza21/Credit_Risk_Analysis/blob/main/Balanced_Random_Forest_Classifier.PNG)

### Easy Ensemble AdaBoost Classifier

![AdaBoost](https://github.com/jzaragoza21/Credit_Risk_Analysis/blob/main/AdaBoost.PNG)


## Summary


Given this analysis is for approving credit card and the risk involved in doing so, we should place a greater importance on sensivity (recall) rather than precision. By this measurement, the best model to use for assessing credit card risk is the Easy Ensemble AdaBoost Classifier. The Adaboost model produced the highest F1 and accuracy scores of 93 and 97 percent respectively. This suggests the model is likely the best one for preventing fraudulent loan applications or identifying the most high-risk applications. Additionally, the precision rate for the high-risk applications is also the highest of all the models at 9 percent, while recall rate is also the highest of all the models at 94 percent.

Having said that, the Balanced Random Forest Classifier also had an exceptional F1 score of 93 percent and the second highest accuracy score of 79 percent. In addition to this, The SMOTE model also produced a respectable F1 score of 81 percent. If we were to move forward with any of these models, however, one challenge would be to improve the precision score for high-risk applications. 

# Credit_Risk_Analysis
Used supervised machine learning to create models and assess credit risks.

## Overview
I used multiple libraries and algorithms to create different models using a credit card credit dataset from LendingClub, a lending services company. With these models I can then determine which can be used to efficiently predict which applications will be approved or denied. This was done using Naive oversampling, SMOTE, undersampling, under-over sampling, Balanced random forest classifier, and Adaboost classifier algorithms.

**Technologies:** 
* imbalanced-learn
* scikit-learn
* Random Over sampler
* SMOTE
* Cluster Centroids
* SMOTEEN
* Balanced Random Forest Classifier
* Easy Ensemble Classifier

## Results
Here are the 6 models alongs with their imbalanced classification reports that include accuracy, precision and recall scores. 

**Naive Random Oversampling**
![nos](https://user-images.githubusercontent.com/112291075/214176095-0adee37a-e3e4-46e6-8496-e2ed44a34274.PNG)
* This model returned an accuracy score 0.65.
* The precision score is low for high-risk loans and high for low-risk loans.
* The recall score for this model is 0.62/0.67.

**SMOTE Oversampling**
![smote](https://user-images.githubusercontent.com/112291075/214176791-3a5e3045-4d25-4a3e-8073-0496bf001d6a.PNG)
* The balanced accuracy score for this model was, 0.63.
* The precision score was once again, low for high-risk loans vs high for low-risk loans.
* The recall score for this model is 0.62/0.63.

**Undersampling**
![undersampling](https://user-images.githubusercontent.com/112291075/214177241-6a685bb4-a114-484e-a550-b413703288bd.PNG)
* The balanced accuracy score this model was 0.63.
* The precision score was yet again low for high-risk loans vs high for low-risk loans.
* The recall score for this model is 0.57/0.47.

**Over and Under sampling**
![combo](https://user-images.githubusercontent.com/112291075/214178052-53247757-906a-492e-8a34-553dc8993283.PNG)
* The balanced accuracy score for this model was 0.52.
* The precision score was again low for high-risk loans vs high for low-risk loans.
* The recall score for this model was 0.7/0.58.

**Balanced Random Forest Classifier**
![random_forest](https://user-images.githubusercontent.com/112291075/214178176-7100cbc7-aaf5-4657-8eb2-4aa13f4ff599.PNG)
* The balanced accuracy score for this model was 0.79.
* The precision score was low for high-risk loans vs high for low-risk loans.
* The recall score for this model was 0.67/0.91.

**Easy Ensemble AdaBoost Classifier**
![adaboost](https://user-images.githubusercontent.com/112291075/214178398-05d35b64-f531-482c-bcd7-cb8aacbb0e9f.PNG)
* The balanced accuracy score for this model was 0.93
* The precision score was low for high-risk loans vs high for low-risk loans.
* The recall score for this model was 0.91/0.94.

## Summary
After comparing all 6 model against each other the model that is closest to 1 in the balanced accuracy score as well as the recall score was the final "Easy Ensemble AdaBoost Classifier" with an accuracy score of 0.93, and a recall score of 0.94 making it the most accurate model by a long shot. For the precision score all models were about the same with low score for high-risk loans and high scores for low-risk loans. In conclusion, I would recommend the use of the Easy Ensemble AdaBoost Classifier model as a good way of approving and denying applications in the future. 

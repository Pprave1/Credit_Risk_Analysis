# Credit_Risk_Analysis
## Overview of the Project

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. So, need to employ different techniques to train and evaluate models with unbalanced classes.

Therefore, various libraries and algorithms were used to build and evaluate models using resampling like imbalanced-learn; scikitlearn; RandomOverSampler; SMOTE; ClusterCentroids; SMOTEENN; BalancedRandomForestClassifier; EasyEnsembleClassifier (bias reduction models).

## Results

The results for all the six machine learning models with its respective balanced accuracy,precision,and recall scores are as follows:
For Deliverable 1 ,created training and targeted variables and used LogisticRegression classifier to make predictions and evaluated the model's performance ,calculated the accuracy score;generated a confusion matrix and an imbalanced classification report.

    ### Naive Random Oversampling
    
    
    ![random_oversampling.png](Images/random_oversampling.png)
    
   Balanced Accuracy : 0.6434595968752392
   Precision : Precision low for high risk loans and high for Low-risk loans.
   Recall : 0.64/0.64
   
   ### SMOTE Oversampling
   ![smote_oversampling.png](Images/smote_oversampling.png)
   
   
    Balanced Accuracy : 0.6295480458158583
   Precision : Precision low for high risk loans and high for Low-risk loans.
   Recall : 0.61/0.65
   
   
   ### Undersampling
   
   
   
   

   

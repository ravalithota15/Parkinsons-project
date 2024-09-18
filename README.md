**** Parkinsons-project****

**Parkinson's Disease Classification**:

This repository contains machine learning models for classifying Parkinson's disease based on speech features. Models included are CatBoost, SVM, Random Forest, and XGBoost. The project demonstrates data 
preprocessing, feature selection, SMOTE for class balancing, and performance evaluation.


**Features:**

    Data Preprocessing: Handling missing values, scaling features.  
    Feature Selection: Identifying and selecting top features using correlation.
    Model Training: Implementations of CatBoost, SVM, Random Forest, and XGBoost.
    Cross-Validation: Stratified K-Fold cross-validation for robust performance evaluation.
    Class Balancing: Using SMOTE to address class imbalance.
    Performance Metrics: Accuracy, confusion matrix, precision, recall, and F1-score.
    

**Requirements**:

    pandas
    numpy
    scikit-learn
    imblearn
    catboost
    xgboost

**Results**:

  The models are evaluated using cross-validation with the following metrics:
  
    Mean Accuracy
    
    Mean Confusion Matrix
    
    Mean Precision
    
    Mean Recall
  
  Mean F1-score

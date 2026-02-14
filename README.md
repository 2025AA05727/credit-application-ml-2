# Problem statement
Implement multiple classification models -Build an interactive Streamlit web application to demonstrate your models.

# Dataset description
Credit Card Approval Prediction: Credit score cards are a common risk control method in the financial industry. It uses personal information and data submitted by credit card applicants to predict the probability of future defaults and credit card borrowings. The bank is able to decide whether to issue a credit card to the applicant.

# Models used
      Model                     Accuracy   AUC       Precision   Recall   F1       MCC 
    Logistic Regression         0.8827     0.5485    1.0000      0.0035   0.0070   0.0556
    Decision Tree               0.8507     0.6492    0.3707      0.3858   0.3781   0.2933
    kNN                         0.8801     0.7336    0.4804      0.2284   0.3096   0.2741
    Gaussian Naive Bayes        0.7990     0.5271    0.1457      0.1457   0.1457   0.0318
    Random Forest (Ensemble)    0.8630     0.7862    0.4064      0.3566   0.3799   0.3041
    XGBoost (Ensemble)          0.7670     0.7484    0.2762      0.6049   0.3792   0.2899

# Observation about model performance
- Logistic Regression : It is simple and fast but may not capture complex relationships in the data.

- Decision Tree       : It is easy to interpret but less stable compared to ensemble methods.

- KNN                 : It is simple but not ideal for datasets with more fetures.

- Naive Bayes         : It is fast but less accurate because of its strong assumptions.

- Random Forest       : It provides stable performance and is suitable for structured tabular data.

- XGBoost             : It is the best-performing model on this dataset due to its boosting approach.

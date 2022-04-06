# Bank Clients Churn Prediction

**Goal**: based on historical data (*CustomerId, Surname, CreditScore, Geography, Gender, Age, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary*) build a model predicting clients' churn (*Exited*)

**Criterea**: key metric - *F1*-score, cut-off value 0.59; additionaly check AUC-ROC

Data Source: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

## Result
- Data prepared:
    - numeric features normalized
    - categorial features processed with OHE
    - features and targets determined, data split in subsets
- Models not taking into account class disbalance have been created and analysed - all models' F1-scores do not satisfy quality condition
- 3 ways to fight disbalance have been assessed:
    - Class weighting did not acqure satisfactory result
    - 4 times Upsampling and Downsampling were most effective in terms of meeting F1 criteria
    - Hyperparameters chosen for best Random Forest model
- Chosen best model has passed testing:
    - F1-score = 0.62, above cut-off value
    - Confusion matrix prove sufficient model quality, model passed sanity test
    - ROC-AUC = 0.86, noticeably higher than for random model

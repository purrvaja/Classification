# Classification

This notebook goes through various classification techniques with the use of the [bank marketing dataset.](https://archive.ics.uci.edu/ml/datasets/bank+marketing) 

The following research questions were identified from the dataset, and have been answered throughout the analysis using eda, and machine learning methods; 

 - Do demographic factors such as the level of education, marital status, and type of job affect the success of the marketing campaign?
 - Does a customer’s previous banking behaviour such as taking out a loan, or defaulting impact their decision on whether to subscribe to the term deposit or not?
 - Does the time period in which the customer is contacted increase the effectiveness of the campaign?
 - Which features are the most important when determining the effectiveness of the marketing campaign?
 - Can the outcome of the marketing campaign be predicted using classification models? Which model performs the best?

 

### Modelling

The models have been optimized using hyper-parameter tuning and Recursive Feature Elimination (RFE with cross validation) for feature selection.

The following evaluation metrics were observed; 
|Algorithm |ROC-AUC |
|-|--|
| Logistic Regression |0.76
CART|0.70
Random Forest|0.77
|XGBoost |0.76

It was concluded that the **Random Forest** classifier performs the best whilst the XGBoost and logistic regression models also having almost the same performance. 

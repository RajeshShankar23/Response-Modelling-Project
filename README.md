# Response-Modelling-Project
# Project Report and Actionable Insights
# Objective of the Project
Leverage the spend behavior and past campaign responses to build a response model that can
be used to devise a strategy that enhances the response rates and improves profitability of
marketing campaigns
# Baseline Event Rate
The Response Rate from the data is 14.9%
# Algorithms Used :
In this project we have used Logistic Regression, Decision Trees, Random Forests and Gradient
Boosting Algorithms
# Final Model Algorithm
Among the models that we tried building the GBM Algorithm performed the best in terms of
F1_Score, Area under ROC Curve and overall Model Gini
Therefore we have kept GBM as the final model algorithm
# Grid Search CV parameters
Maximum Depth of Tree - 5
Minimum Sample Size for Nodes to be Split - 75 Observations
# Model Performance Measures
Accuracy - 0.86
Precision - 0.58
Recall - 0.25
F1 Score - 0.35
AUC - 0.61
Gini - 0.22
# Model Probability Discrimination Measures
Steady Event Rate Rank Ordering (Yes/No) - Yes
Rank Ordering Reversals in Top 3 Deciles (Yes/No) - No
Model Lift over baseline event rate in the Top Decile - 5.8
Cumulative Event Capture in the Top 3 Deciles - 90%
Maximum KS Statistic Value - 0.74
Does KS Statistic Maximize within Top 3 Deciles (Yes/No) - Yes
# Top 10 drivers from the Model
Income
MntMeatProducts
AcceptedCmp3_1
MntFishProducts
MntFruits
Cust_Tenure_8.0
NumCatalogPurchases_10
Marital_Status_Together
Marital_Status_Single
Marital_Status_Married
APT Stratgey Framework using the Model
![image](https://github.com/RajeshShankar23/Response-Modelling-Project/assets/70463933/46bf07eb-8103-4b1a-a325-03dccd98add7)


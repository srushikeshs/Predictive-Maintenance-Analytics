# Predictive-Maintenance-Analytics

## Background
Predictive Maintenance becomes crucial for organizations to design and deploy efficient maintenance policy to prevent expensive outages from happening and alleviate the damage caused by breakdowns. 

## About the Data
Used the AI4I 2020 Predictive Maintenance Dataset which is a synthetic dataset that reflects real predictive maintenance data encountered in industry. 
The dataset contains various equipment parameters and has various equipment failure labels. 

## Objective
Perform EDA to identify factors affecting equipment failure and create new features. Apply machine learning models to predict tool wear, heat dissipation, overstrain, and power failures.

## Conclusion
A simple Decision Tree model is able to predict most of the failures. However, the model isn't able to capture the tool wear failure due to sporadic nature of the failure and imbalanced target value. From the graph in cell 20, we observed that the tool failure can happen anytime after 200 minutes of usage.
1) We can tackle the issue by proactively changing the tool after using it for 200 minutes to avoid potential failure.
2) Remodeling the Decision Tree after unsampling the target value by SMOTE technique.

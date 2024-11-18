# credit-risk-classification


Credit Risk Classification with Machine Learning

Overview of the Analysis
The purpose of this analysis was to evaluate the performance of a machine learning model to classify credit risks as either "healthy loans" (0) or "high-risk loans" (1). 
The model aims to assist financial institutions in making informed lending decisions.

# Results:

Logistic Regression Model Performance:
Accuracy Score: 99%
Precision:
Class 0 (Healthy Loan): 100%
Class 1 (High-Risk Loan): 85%
Recall:
Class 0: 99%
Class 1: 91%
F1-Score:
Class 0: 100%
Class 1: 88%
Confusion Matrix:
Predicted 0	Predicted 1
Actual 0	18,663	102
Actual 1	56	563

# Summary:

The logistic regression model effectively identifies "healthy loans" with near-perfect accuracy (99% recall and 100% precision).
For "high-risk loans," the model achieved an 85% precision and a 91% recall, leading to an F1-score of 88%.

Despite its strong overall performance, the model exhibits some limitations due to the significant class imbalance in the dataset. 
With 75,036 "healthy loans" compared to only 2,500 "high-risk loans," the model has a bias toward predicting the majority class. 
This could lead to missed opportunities to identify high-risk loans, which are critical for mitigating financial risks.

# Recommendation:

While the logistic regression model performs well overall, it may benefit from techniques to address class imbalance, such as:

Over-sampling the minority class or under-sampling the majority class.

This model can serve as a starting point, but additional tuning and improvements are recommended for deployment in a production environment.

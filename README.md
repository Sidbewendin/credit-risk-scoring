Credit Risk Scoring Project

This project focuses on predicting credit risk using machine learning techniques on customer financial data.

The goal is to identify clients who are more likely to default, while taking into account real business constraints. In credit risk, it is more important to detect risky clients than to simply maximize overall accuracy.

Approach

I followed a complete data science workflow:

Data preprocessing using pipelines (handling missing values, encoding, scaling)
Training a first model using Logistic Regression as a baseline
Training a second model using XGBoost for improved performance
Evaluating models using accuracy, recall, and ROC-AUC
Adjusting the decision threshold to better detect risky clients

Models

Logistic Regression was used as a baseline model. It performed well, especially in detecting risky clients.

XGBoost provided better overall performance, but initially missed more risky clients.

To fix this, I adjusted the decision threshold, which significantly improved recall for the risky class.

Results

The final model achieves:

Accuracy around 71–76% depending on the threshold
ROC-AUC around 0.80
Recall for risky clients improved up to 0.80

Tools used

Python
Pandas, NumPy
Scikit-learn
XGBoost
Matplotlib, Seaborn

Author

SIDBEWENDIN YAMEOGO
PhD in Computer Science – Machine Learning & NLP

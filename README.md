# fraudlent_prediction-project
The NovaPay Fraud Detection project aims to develop an intelligent machine learning system capable of detecting fraudulent digital payment transactions in real time. As NovaPay expands globally, the company faces increasing threats such as identity theft, account takeover, unauthorized payments, and transaction laundering.

Project Summary

The NovaPay Fraud Detection project aims to develop an intelligent machine learning system capable of detecting fraudulent digital payment transactions in real time. As NovaPay expands globally, the company faces increasing threats such as identity theft, account takeover, unauthorized payments, and transaction laundering, while its existing rules-based fraud detection system struggles to adapt to evolving fraud patterns.

The project uses transactional and customer behavioural data to build a supervised machine learning model that classifies transactions as either fraudulent or legitimate using the target variable is_fraud. The dataset includes transaction amounts, device information, geographic data, risk scores, account history, and transaction velocity features that help identify suspicious behaviour.

A full machine learning pipeline is proposed, including data cleaning, preprocessing, feature engineering, imbalance handling, model training, and evaluation. Since fraud data is highly imbalanced, techniques such as SMOTE, class weighting, and threshold tuning are recommended to improve fraud detection performance.

The project also emphasizes explainable AI and regulatory compliance by incorporating interpretable models and explainability tools such as SHAP to justify fraud predictions. Models such as Logistic Regression, Random Forest, and XGBoost are considered suitable due to their strong classification performance and scalability.

The expected outcome is a scalable and adaptable fraud detection system that improves fraud detection accuracy, reduces false positives, supports AML and KYC compliance requirements, and enhances customer trust through faster and more reliable transaction security.

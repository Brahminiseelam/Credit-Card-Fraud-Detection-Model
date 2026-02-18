# Credit-Card-Fraud-Detection-Model
Project Overview
This project aims to detect fraudulent credit card transactions using supervised machine learning techniques. Since fraud datasets are highly imbalanced, special attention was given to handling class imbalance and improving minority class detection performance.
The project includes:
Data preprocessing
Imbalanced data handling
Model training & evaluation
Model saving (model.pkl)
Deployment using Streamli

Dataset Information
Highly imbalanced dataset
Majority class: Legitimate transactions
Minority class: Fraudulent transactions
Features: PCA-transformed numerical features + transaction amount

Technologies Used
Python
Pandas
NumPy
Scikit-learn
Imbalanced-learn (SMOTE)
Streamlit
Pickle

Model Performance
Focused on Recall and F1-score for fraud class
Evaluated using:
Confusion Matrix
Precision
Recall
ROC-AUC score

Deployment
The trained model was saved using pickle and deployed using Streamlit.

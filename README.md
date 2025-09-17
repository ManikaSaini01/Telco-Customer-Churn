Customer Churn Prediction

This project predicts customer churn (i.e., whether a customer will cancel their subscription) using the Telco Customer Churn dataset. The goal is to help businesses (like Telecom or SaaS providers) identify customers at risk of leaving and take proactive retention measures.

The project includes:
Exploratory Data Analysis (EDA) to understand churn drivers
Feature Engineering to create meaningful predictors
Machine Learning models (Logistic Regression, Random Forest, XGBoost, Decision Tree)
Hyperparameter Tuning with GridSearchCV
Model Evaluation using ROC-AUC, Precision, Recall, F1-score
Deployment as a web app (Streamlit / FastAPI) with interactive predictions and churn insights

Results:
Best performing model: DecisionTreeClassifier

Key churn drivers:
Contract type (Month-to-Month customers churn more)
Internet Service (Fiber optic users churn more)
Senior Citizens + Month-to-Month have high churn risk
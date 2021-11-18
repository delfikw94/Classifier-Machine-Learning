# Predictive Model for Customer Retention in Credit Card Service

Predict the Customer's churn potential to develop a certain marketing strategy

**Library and Tools used** : Python, Numpy, Pandas, Seaborn, Scikit-Learn, joblib, Flask, Heroku

**Category** : Machine Learning, Classification

**Year** : September 2021

**Features** : Customer's personal information (age, marital status, gender, number of dependents) and the credit card information (card type, inactive time, utilization ratio, and credit limit)

**Model Algorithms** : PCA (for dimention reduction), Logistic Regression, Random Forest Classifier, SVM

**Result** : For the first model training, Random Forest acheived the highest accuracy among other model. However, after we did the cross-validation and hyperparameter tuning, turned out that the highest accuracy (93.5%) and F1-score (95.96%) is achieved by SVM. Then the model with SVM and its best parameter was saved to be used in deployment. 

**Deployment link** : https://mls2.herokuapp.com

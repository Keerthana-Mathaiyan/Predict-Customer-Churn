# Predict-Customer-Churn

📌 Customer Churn Prediction (Kaggle)


This project focuses on predicting customer churn using a supervised machine learning approach on a Telco-style dataset from a Kaggle competition.


🚀 Overview


The goal is to predict the probability of a customer leaving the service (churn) using behavioral, demographic, and service-related features.


🔍 Key Steps

    Performed Exploratory Data Analysis (EDA) to identify churn patterns
    
    Handled missing values and encoded categorical variables
    
    Applied feature engineering to improve model performance
    
    Built a baseline model using Logistic Regression
    
    Evaluated using ROC-AUC metric
    
    Implemented cross-validation to ensure model stability
    

📊 Results

  Achieved ROC-AUC: 0.91
  
  Consistent cross-validation performance (~0.909)
  
  Minimal overfitting with strong generalization


💡 Key Insights

Customers with short tenure are more likely to churn

Month-to-month contracts have the highest churn rate

Higher monthly charges increase churn probability

Value-added services (Tech Support, Online Security) reduce churn


🛠️ Tech Stack

    Python
    Pandas, NumPy
    Scikit-learn
    Matplotlib / Seaborn

📂 Files

    train.csv – Training dataset
    
    playground-series-s6e3.zip - Input
    
    test.csv – Test dataset
    
    submission.csv – Final predictions
    
    Churn_prediction.ipynb – Full pipeline (EDA → Model → Evaluation)


🔗 Links

Kaggle Notebook: ([Customer Churn Prediction | 0.91 ROC-AUC](https://www.kaggle.com/code/keerthanamathaiyan/customer-churn-prediction-0-91-roc-auc))

Competition: ([Predict Customer Churn](https://www.kaggle.com/competitions/playground-series-s6e3/overview))

📈 Future Improvements

Try ensemble models (XGBoost, LightGBM)

Hyperparameter tuning

SHAP for model interpretability


⭐ If you found this useful


Feel free to star ⭐ the repo or connect!

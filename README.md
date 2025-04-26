# Churn Prediction Model

**📄 Project Overview**
This project builds a machine learning model to predict whether a customer will discontinue a subscription-based service (customer churn) based on historical usage patterns, demographics, and account information.

We use a Random Forest Classifier trained on the Churn_Modelling.csv dataset, applying appropriate data preprocessing, missing value imputation, and feature scaling.

**📂 Dataset**
**File:** Churn_Modelling.csv
**Attributes include:**  
  - Customer demographics (Age, Gender, Geography)
  - Bank account details (Balance, CreditScore, Tenure, etc.)
  - Subscription status (Exited: 1 if churned, 0 otherwise)


**🛠️ Methods Applied**
- Missing value imputation (mean for numeric, mode for categorical features)
- Label Encoding for categorical variables
- Feature scaling using Standard Scaler
- Model training using Random Forest Classifier
- Model evaluation using Accuracy Score, Classification Report, and Confusion Matrix
- Feature Importance visualization


**📊 Results**
**Evaluation Metrics:**
  - Accuracy
  - Precision, Recall, F1-Score (classification report)
  - Confusion Matrix
  
**Feature Importance:**  
  Plotted top 10 features influencing churn prediction.


**🔥 How to Run**
1. Clone this repository.
2. Install dependencies:
   pip install pandas numpy scikit-learn matplotlib seaborn
3. Run the customer_churn_prediction.py script.

**📈 Model Performance**
The Random Forest model achieved a strong accuracy score with meaningful insights into which features most affect customer churn, such as Credit Score, Age, and Balance.

**📌 Future Improvements**
- Hyperparameter tuning using GridSearchCV
- Try advanced models (e.g., XGBoost, LightGBM)
- Model explainability using SHAP or LIME

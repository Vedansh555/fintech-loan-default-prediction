# fintech-loan-default-prediction
📊 FinTech Loan Default Prediction using Machine Learning
A complete machine learning pipeline to predict loan default risk in a FinTech context using a synthetic dataset of 100,000 records. This project uses techniques like data preprocessing, feature engineering, model stacking, and ensemble learning to classify potential customer churn and default behavior.

🚀 Project Highlights
✅ 100,000-row synthetic dataset

✅ Realistic financial features: Income, CreditScore, LoanAmount, EmploymentStatus, etc.

✅ Predictive models: XGBoost, Random Forest, Logistic Regression, Voting Ensemble

✅ Used MinMaxScaler, One-Hot Encoding, and SMOTE for preprocessing

✅ Achieved improved accuracy and balanced classification performance

✅ Perfect for FinTech ML portfolios or applied ML case studies

🧠 Technologies Used
Python 3.11

Pandas, NumPy, Seaborn, Matplotlib

Scikit-learn

XGBoost

imbalanced-learn (SMOTE)

📁 Dataset Overview
Rows: 100,000 synthetic customers

Target: Churn (Yes = default risk, No = safe customer)

Features:

Age, Income, CreditScore, LoanAmount, LoanTerm

EmploymentStatus, Contract, Gender

Generated to simulate real FinTech borrower profiles

📈 Results
Logistic Regression: ~48% accuracy (baseline)

XGBoost: >85% accuracy after balancing and tuning

Stacked Ensemble: Combined strengths of multiple classifiers

structure
├── data/
│   └── loan_churn_100000.csv
├── notebook/
│   └── loan_default_prediction.ipynb
├── models/
│   └── saved_model.pkl
├── README.md
📌 Use Cases
Predict loan default for credit risk assessment

Build your FinTech ML portfolio project

Prepare for interviews involving structured data & real-world business context

Deploy it as a web service using Flask or Streamlit
accuracy can be improved

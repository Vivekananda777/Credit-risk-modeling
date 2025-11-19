# Credit-risk-modeling

#  Credit Risk Modeling using Machine Learning

This project predicts **loan default risk** using machine learning techniques.  
It uses a LendingClub-style dataset and implements:

- Data preprocessing  
- Handling missing values  
- Handling categorical variables  
- SMOTE for class imbalance  
- Logistic Regression & Random Forest  
- ROC-AUC, classification report  
- SHAP / Permutation feature importance  
- Model saving & prediction for new applicants  

---

## 📁 Project Structure

credit-risk-modeling/
│
├── credit_risk_modeling_notebook.ipynb   # Main ML notebook
├── data/                                 # (loans_full_schema.csv)
├── models/                               # (Saved .pkl model)
└── README.md

---

## 🚀 How to Run the Notebook

1. Download the repository  
2. Install dependencies: pip install -r requirements.txt
3. Open the notebook and run: credit_risk_modeling_notebook.ipynb

---

## 📊 Model Training Summary

Models used:
- Logistic Regression  
- Random Forest Classifier
- Oversampling with SMOTE  

Performance metrics:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

---

##  Predicting New Applicants

The notebook includes code to run:

- After loading the saved .pkl model.





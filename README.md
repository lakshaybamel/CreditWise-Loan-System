# 💳 CreditWise Loan Approval System

An end-to-end Machine Learning project that predicts whether a loan application should be approved or rejected based on applicant financial and personal details.

---

## 📌 Problem Statement

Traditional loan approval systems rely heavily on manual verification, which can be:

- ⏳ Time-consuming  
- ⚖️ Biased and inconsistent  
- ❌ Prone to human error  

This project aims to solve these challenges by building an **automated ML-based loan approval system** that ensures faster, more accurate, and unbiased decisions.

---

## 🎯 Objective

- Predict loan approval status (**Approved / Rejected**)  
- Analyze applicant financial and demographic data  
- Compare multiple ML models  
- Select the best-performing model based on evaluation metrics  

---

## 📊 Dataset Overview

Each record represents a loan applicant with features such as:

- Applicant Income  
- Coapplicant Income  
- Employment Status  
- Age  
- Marital Status  
- Dependents  
- Credit Score  
- Existing Loans  
- Debt-to-Income (DTI) Ratio  
- Savings  
- Collateral Value  
- Loan Amount & Term  
- Loan Purpose  
- Property Area  
- Education Level  
- Gender  
- Employer Category  

🎯 **Target Variable:**
- `1` → Loan Approved  
- `0` → Loan Rejected  

---

## 🔍 Project Workflow

1. **Data Cleaning**
   - Handled missing values  
   - Processed categorical variables  

2. **Exploratory Data Analysis (EDA)**
   - Analyzed feature distributions  
   - Identified important patterns  

3. **Feature Engineering**
   - Transformed categorical data  
   - Prepared data for model training  

4. **Model Building**
   - K-Nearest Neighbors (KNN)  
   - Logistic Regression  
   - Naive Bayes  

5. **Model Evaluation**
   - Accuracy  
   - Precision  
   - Recall  
   - F1 Score  

---

## 🤖 Model Performance

- 🏆 **Best Model:** Naive Bayes  
- 📌 Key Influencing Features:
  - Credit Score  
  - Applicant Income  
  - DTI Ratio  

---

## 🛠️ Tech Stack

- Python 🐍  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 📁 Project Structure

```
CreditWise-Loan-System/
│
├── credit_wise.ipynb
├── loan_approval_data.csv
├── README.md
└── requirements.txt
```

---

## 🚀 Future Improvements

- Hyperparameter tuning  
- Use advanced models (Random Forest, XGBoost)  
- Build a Streamlit web app for deployment  
- Add real-time prediction interface  

---

## 💡 Key Learnings

- End-to-end ML workflow  
- Data preprocessing & feature handling  
- Model comparison & evaluation  
- Importance of data quality in ML  

---

## ▶️ How to Run

1. Clone the repository:

```
git clone https://github.com/lakshaybamel/CreditWise-Loan-System
cd CreditWise-Loan-System
```

2. Install required dependencies:

```
pip install -r requirements.txt
```

3. Run the Jupyter Notebook:

```
jupyter notebook credit_wise.ipynb
```

---

## 👨‍💻 Author

**Lakshay Bamel**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
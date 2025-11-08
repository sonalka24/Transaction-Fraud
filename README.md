# Credit Card Fraud Analysis

## 📌 Overview
This project focuses on analyzing credit card transaction data to:
1. Perform **Exploratory Data Analysis (EDA)**.
2. Build a **Fraud Prediction Model**.
3. Conduct **Profit Analysis** based on fraud detection strategies.

The goal is to understand patterns in fraudulent transactions, predict fraud effectively, and evaluate the financial impact of fraud prevention.

---

## 📂 Project Structure
---

## 📊 Dataset Description
The dataset includes the following columns:
- **ID**: Unique transaction identifier
- **cc_num**: Credit card number
- **account_status**: Account status (active/inactive)
- **merchant**: Merchant name
- **category**: Transaction category
- **amt**: Transaction amount
- **first, last, gender**: Customer details
- **street, city, state, zip, lat, long**: Customer location
- **city_pop**: Population of the city
- **job, dob**: Customer job and date of birth
- **trans_num**: Transaction number
- **merch_lat, merch_long**: Merchant location
- **is_fraud**: Fraud indicator (0 = non-fraud, 1 = fraud)
- **trans_time**: Transaction timestamp
- **time_since_last_trans**: Time since last transaction

---

## ✅ Steps in the Project
### 1. **Exploratory Data Analysis (EDA)**
- Understand data distribution and missing values
- Analyze fraud patterns by category, amount, location, and time
- Visualize correlations between numeric features (e.g., `amt`, `lat`, `long`, `merch_lat`, `merch_long`)

### 2. **Fraud Prediction**
- Build machine learning models (Logistic Regression, Random Forest, XGBoost)
- Evaluate performance using metrics like **Precision**, **Recall**, **F1-score**, and **ROC-AUC**
- Handle class imbalance using techniques like **SMOTE** or **class weights**

### 3. **Profit Analysis**
- Calculate cost of fraud vs cost of prevention
- Simulate different fraud detection thresholds
- Estimate potential savings and ROI

---

## 🛠️ Technologies Used
- **Python**
- **Pandas**, **NumPy** for data manipulation
- **Matplotlib**, **Seaborn** for visualization
- **Scikit-learn**, **XGBoost** for modeling
- **Jupyter Notebook** for interactive analysis

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd CreditCard-Fraud-Analysis
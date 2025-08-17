# Churn_prediction

📊 Customer Churn Prediction using Machine Learning

📌 Project Overview

Customer churn is a critical challenge for subscription-based businesses such as telecom and internet service providers.
In this project, I built a **Machine Learning model** to predict whether a customer is likely to churn, based on demographic, usage, and account-related features.

The goal is to **help businesses identify at-risk customers early** and take proactive steps to improve retention.

---

🗂 Dataset

* Source: [Telco Customer Churn Dataset (Kaggle)](https://www.kaggle.com/blastchar/telco-customer-churn)
* Records: \~7,000 customers
* Features: Demographics, account details, internet/phone services, tenure, billing info
* Target Variable: `Churn` (Yes/No)

---
 🔑 Steps Performed

1. **Data Understanding & Cleaning**

   * Loaded dataset and handled missing values
   * Converted categorical variables into numerical format

2. **Exploratory Data Analysis (EDA)**

   * Distribution of churn across demographics and services
   * Correlation heatmaps & visualizations

3. **Data Preprocessing**

   * Feature scaling using `StandardScaler`
   * Addressed class imbalance with `SMOTE`

4. **Model Building**

   * Implemented multiple classification models:

     * Logistic Regression
     * Random Forest
     * Support Vector Machine (SVM)
     * XGBoost

5. **Model Evaluation**

   * Accuracy, Precision, Recall, F1-Score
   * Confusion Matrix
   * ROC-AUC Curve

---

📈 Results

* Best-performing model: Logistiic Regression
* Achieved: 78% Accuracy, 0.62 F1-Score (Churn class)
* Insights:

  * Customers with short tenure and monthly contracts are more likely to churn
  * Auto-payment and long-term contracts reduce churn

---

 🛠 Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* XGBoost




# 📊 Customer Churn Prediction

## 📌 Project Overview
This project focuses on predicting customer churn for a telecom company using machine learning techniques. Customer churn refers to the percentage of customers that stop using a company's service during a given time period.  
By identifying churn-prone customers in advance, businesses can take proactive measures to improve retention and reduce revenue loss.

---

## 🎯 Objectives
- Analyze customer behavior and demographics.
- Identify key factors influencing churn.
- Build and evaluate machine learning models for churn prediction.
- Provide actionable insights for customer retention strategies.

---

## 📂 Dataset
**Source:** [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)  
**Size:** ~7,000 customer records  
**Features:**
- **Demographic:** Gender, Age, SeniorCitizen, etc.
- **Service Details:** Internet service type, contract type, payment method.
- **Account Information:** Tenure, monthly charges, total charges.
- **Target:** Churn (Yes/No)

---

## 🛠️ Tech Stack
- **Programming Language:** Python
- **Libraries:**
  - Data Processing: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`
- **IDE:** Jupyter Notebook

---

## 🔍 Workflow
1. **Data Loading & Understanding**
   - Imported dataset and explored feature details.
2. **Data Preprocessing**
   - Handled missing values.
   - Converted categorical variables to numerical.
   - Normalized continuous features.
3. **Exploratory Data Analysis (EDA)**
   - Visualized churn distribution.
   - Correlation heatmap to find influential features.
4. **Model Building**
   - Trained models: Logistic Regression, Random Forest, Gradient Boosting.
   - Used train-test split for evaluation.
5. **Model Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC.
6. **Insights & Recommendations**
   - Highlighted most impactful features for churn.

---

## 📈 Results
- **Best Model:** Gradient Boosting Classifier
- **Accuracy:** 80%+
- **Key Drivers of Churn:**
  - Contract Type (Month-to-Month more likely to churn)
  - Tenure (Short-term customers more likely to churn)
  - Monthly Charges (Higher charges increase churn risk)

---

## 📌 Key Insights
- Offering discounts or loyalty programs to high-risk customers may reduce churn.
- Encouraging customers to move to longer-term contracts can improve retention.
- Monitoring early-stage customers (low tenure) is critical.

---


# Customer Churn Prediction using Machine Learning

## 📌 Overview
Customer churn is a critical problem for businesses, where customers stop using a company's services. This project aims to predict whether a customer is likely to churn based on their demographic and service usage data.

## 🎯 Objective
To build a machine learning model that can identify customers who are likely to leave the service, helping businesses take proactive actions to improve customer retention.

---

## 🧰 Tools & Technologies Used
- Python
- Pandas (Data Manipulation)
- Scikit-learn (Machine Learning)
- Matplotlib & Seaborn (Visualization)

---

## 📊 Dataset
- Telco Customer Churn Dataset
- Contains customer details such as:
  - Tenure
  - Monthly Charges
  - Total Charges
  - Contract Type
  - Payment Method
  - Churn Status

---

## ⚙️ Project Workflow

### 1. Data Loading
- Imported dataset using Pandas

### 2. Data Cleaning
- Removed unnecessary columns (customerID)
- Converted data types (TotalCharges)
- Handled missing values

### 3. Data Preprocessing
- Converted categorical variables into numerical format using One-Hot Encoding

### 4. Model Building
- Used Logistic Regression for classification

### 5. Model Evaluation
- Evaluated using Accuracy Score and Confusion Matrix

### 6. Data Visualization
- Visualized churn distribution using graphs

---

## 🤖 Machine Learning Model
- **Algorithm Used:** Logistic Regression
- **Problem Type:** Classification

---

## 📈 Results
- The model achieved good accuracy in predicting customer churn
- Successfully classified customers into churn and non-churn categories

---

## 🧠 Key Insights
- Customers with shorter tenure are more likely to churn
- Higher monthly charges increase churn probability
- Long-term contract customers are less likely to leave
- Customer behavior plays a significant role in churn prediction

---

## 💼 Business Impact
- Helps businesses identify high-risk customers
- Enables targeted retention strategies
- Improves customer satisfaction and reduces revenue loss

---

## 🚀 Conclusion
This project demonstrates how machine learning can be applied to solve real-world business problems by predicting customer behavior and enabling data-driven decision-making.

---

## 📁 Project Structure
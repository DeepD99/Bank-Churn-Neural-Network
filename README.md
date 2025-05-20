# Bank Churn Prediction Project

## 💼 Problem Statement

The objective of this project is to develop a neural network-based classifier that can accurately predict whether a customer will **leave the bank (churn)** within the next six months. By identifying potential churners in advance, the bank can take proactive measures to retain valuable customers.

---

## 🧠 Objectives

- Understand factors that influence customer churn in banking.
- Preprocess and analyze customer data for modeling.
- Build and evaluate a deep learning model using Keras.
- Improve predictive performance using SMOTE and hyperparameter tuning.
- Generate actionable insights for customer retention strategies.

---

## 📄 Data Description

Below is a brief description of each column in the dataset:

| Column Name        | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| `CustomerId`       | Unique ID assigned to each customer                                         |
| `Surname`          | Last name of the customer                                                   |
| `CreditScore`      | Credit score of the customer (historical credit rating)                     |
| `Geography`        | Country of the customer (France, Germany, Spain)                            |
| `Gender`           | Gender of the customer                                                      |
| `Age`              | Age of the customer                                                         |
| `Tenure`           | Number of years the customer has been with the bank                         |
| `Balance`          | Account balance                                                             |
| `NumOfProducts`    | Number of financial products purchased by the customer                      |
| `HasCrCard`        | Indicates whether the customer has a credit card (1 = Yes, 0 = No)          |
| `IsActiveMember`   | Indicates if the customer is an active member (1 = Yes, 0 = No)             |
| `EstimatedSalary`  | Estimated salary of the customer                                            |
| `Exited`           | **Target variable** – 1 if the customer left the bank, 0 if they remained   |

---

## 🛠️ Project Workflow

1. **Data Loading & Cleaning**
2. **Exploratory Data Analysis (EDA)**
3. **Feature Engineering & Transformation**
4. **Handling Imbalance with SMOTE**
5. **Model Building** (Neural Network using Keras)
6. **Model Evaluation**
7. **Tuning & Optimization**
8. **Conclusion**

---

## 📊 Model Evaluation Metrics

- Accuracy
- Precision & Recall
- F1 Score
- ROC Curve & AUC Score
- Confusion Matrix

---

## ✅ Conclusion

The final neural network model demonstrated effective performance in predicting customer churn. Key insights revealed that **credit score, geography, age, and number of products** are strong indicators of potential churn behavior. These findings can be used by the bank to refine its customer retention strategy.

---

## 📌 Tech Stack Used

- Python
- Pandas, NumPy
- Scikit-learn
- Keras / TensorFlow
- Matplotlib, Seaborn
- SMOTE (for handling class imbalance)

---

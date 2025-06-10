# 🔄 Customer Churn Prediction using Machine Learning

This end-to-end machine learning project predicts telecom customer churn using real-world data and advanced classification algorithms. It walks through data preprocessing, handling class imbalance, model selection, training, evaluation, and deployment using serialized models.

---

## 📊 Project Overview

The project uses the **Telco Customer Churn** dataset to identify customers likely to cancel their service. It focuses on turning raw customer data into actionable predictions using a structured machine learning pipeline. Key customer features include service type, tenure, monthly charges, and demographic information.

---

## 🧠 Machine Learning Pipeline

### 1. **Data Preprocessing**
- Removed irrelevant identifiers (e.g., customerID)
- Handled missing and inconsistent values in `TotalCharges`
- Converted categorical features using **Label Encoding**
- Balanced class distribution with **SMOTE** to handle churn bias

### 2. **Model Training**
- Trained the following classification models:
  - 🎯 **Decision Tree Classifier**
  - 🌲 **Random Forest Classifier**
  - ⚡ **XGBoost Classifier**

### 3. **Model Evaluation**
- Evaluated using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1)

### 🏆 Best Performance
- **Random Forest**:
  - Accuracy: **~80%**
  - Strong balance between precision and recall
- **XGBoost** also delivered competitive results with high generalization

---

## ✅ Key Achievements

- Built a churn prediction system with **80% accuracy**
- Handled class imbalance using **SMOTE**, improving minority class prediction
- Identified top churn indicators using feature importance from tree-based models
- Created a serialized `.pkl` model for deployment

---

## 🛠 Tools & Technologies

- **Python**, **Pandas**, **NumPy**, **Seaborn**, **Matplotlib**
- **Scikit-learn**, **XGBoost**, **SMOTE (imblearn)**
- **Pickle** (model saving)

---

## 📂 Project Structure

```
├── Customer_Churn_Prediction_using_ML.ipynb   # Main notebook
├── churn_model.pkl                            # Saved model file (optional)
├── README.md
```

---

## 🔗 Dataset

- [Telco Customer Churn Dataset on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## 📌 Conclusion

This project provides a scalable, interpretable framework for predicting customer churn in subscription-based services. It demonstrates how machine learning can empower customer retention efforts and inform marketing strategies.
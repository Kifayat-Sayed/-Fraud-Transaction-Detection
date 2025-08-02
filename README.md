
# 💳 Fraud Transaction Detection

## 🔍 Machine Learning Model for Financial Fraud Prediction

A robust machine learning project designed to detect fraudulent transactions in financial datasets using advanced data balancing techniques and ensemble learning. This project addresses severe class imbalance and builds an efficient fraud detection system using real-world financial transaction data.

---

## 🌟 Key Features

### ✅ End-to-End ML Pipeline

* Large-scale financial dataset with **6M+ transactions**
* Feature engineering & preprocessing
* SMOTE oversampling for class imbalance
* Ensemble model with **Gradient Boosting Classifier**

---

### ✅ SMOTE-Based Balancing

Due to a **high class imbalance** (\~0.13% fraud), we applied:

* **SMOTE (Synthetic Minority Oversampling Technique)**
  to balance classes effectively before model training.

---

### ✅ Gradient Boosting Classifier

After rigorous evaluation, Gradient Boosting emerged as the best-performing classifier for fraud prediction:

* Focuses on minimizing false negatives (missing fraud)
* High accuracy and ROC-AUC scores

---

## 🔍 Project Overview

### 🎯 Objective

Detect fraudulent financial transactions and build a predictive model that helps financial institutions identify risks early.

### 📊 Dataset
📌 Note: The dataset used in this project was provided by Accredian as part of their industry-level internship project to help learners gain hands-on experience in high-stakes, real-world data science applications.

* **Source**: [Proprietary financial transaction dataset](https://drive.usercontent.google.com/download?id=1VNpyNkGxHdskfdTNRSjjyNa5qC9u0JyV&export=download&authuser=0)
* **Shape**: `(6,362,620 rows × 9 columns)`
* **Target column**: `isFraud` (0 = Legitimate, 1 = Fraud)

---

### ⚙️ Key Features Used

* `step` – Time step of the transaction
* `type` – Type of transaction (e.g., CASH\_OUT, TRANSFER)
* `amount` – Amount transferred
* `oldbalanceOrg` / `newbalanceOrig`
* `oldbalanceDest` / `newbalanceDest`

---

## 🧪 Models Used

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Random Forest Classifier
* **Gradient Boosting Classifier** ✅ (Best)

---

## 📈 Evaluation Metrics

* **Accuracy**
* **Precision / Recall**
* **F1-Score**
* **ROC-AUC Score**
* **Confusion Matrix**

---

## 🛠️ Workflow Summary

1. **Data Loading & Exploration**
   → Checked class distribution & data integrity

2. **Preprocessing**
   → Removed irrelevant columns like `nameOrig`, `nameDest`, handled type encoding

3. **Balancing with SMOTE**
   → Oversampled minority fraud class to address imbalance

4. **Model Training**
   → Trained multiple models; selected **Gradient Boosting** for best performance

5. **Evaluation & Interpretation**
   → Analyzed confusion matrix, precision-recall, and ROC-AUC to measure fraud-catching capability

---
---

## 💡 What I Learned and How It Helps Me

* Learned to **handle massive class imbalance** using SMOTE and similar techniques
* Understood the **importance of minimizing false negatives** in fraud detection tasks
* Mastered **Gradient Boosting** and evaluated models using **real-world financial risks**
* Applied **memory optimization strategies** for working with large-scale datasets in Colab
* Strengthened data wrangling, feature selection, and model interpretation skills for financial applications

**How This Helps Me:**
It prepares me for real-world financial data science roles, enhances my fraud detection experience, and sharpens my skills in building enterprise-level ML pipelines for anomaly detection.

---

## 🚀 Future Improvements

* Integrate model into **Streamlit or Flask** for real-time fraud prediction
* Explore **autoencoders** or **isolation forests** for unsupervised anomaly detection
* Perform **feature importance analysis** using SHAP for transparency

---

## ✍️ Author

* **\[Kifayat Sayed]**
  M.Sc. AI & ML | Data Science
  📧 [kifayatsayed301@gmail.com](mailto:kifayatsayed301@gmail.com)
  🌐 [LinkedIn](https://www.linkedin.com/in/kifayat-sayed-9614a9244) | [Portfolio](#)

---


# 🩺 Diabetes Prediction using Machine Learning

## 📌 Overview
This project builds a machine learning system to predict whether a person has **diabetes** based on medical diagnostic measurements such as glucose level, BMI, insulin level, blood pressure, and age.

The model is trained using the **PIMA Indians Diabetes Dataset** and compares multiple machine learning algorithms to determine the best-performing model.

---

## 🎯 Objectives
- Predict diabetes using medical attributes  
- Compare multiple machine learning models  
- Evaluate performance using classification metrics  
- Assist in early detection of diabetes  

---

## 📊 Dataset
- **Name:** PIMA Indians Diabetes Dataset  
- Contains medical data of female patients  

### 🔑 Features:
- Pregnancies  
- Glucose  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI  
- Diabetes Pedigree Function  
- Age  

### 🎯 Target Variable:
- **Outcome**
  - `0` → Non-Diabetic  
  - `1` → Diabetic  

---

## 🛠️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 🤖 Machine Learning Algorithms
The following models were implemented and compared:

- Support Vector Machine (SVM) ✅  
- Logistic Regression  
- Random Forest  

---

## 📈 Model Performance

|          Model         | Accuracy   |
|------------------------|------------|
| Support Vector Machine | **78.66%** |
| Logistic Regression    | 75.97%     |
| Random Forest          | 74.02%     |

👉 **SVM performed the best among all models**

---

## ⚙️ Project Workflow
1. Load the dataset  
2. Data exploration and analysis  
3. Data preprocessing and standardization  
4. Train-test split  
5. Train machine learning models  
6. Evaluate models using:
   - Accuracy score  
   - Confusion matrix  
   - Classification report  
7. Visualize results  
8. Predict diabetes for new input data  

---

## 🔍 Example Prediction

**Input:**

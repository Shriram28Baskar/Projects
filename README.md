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
- Contains medical diagnostic data of female patients  

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

## 🧠 Feature Engineering
- Data preprocessing and standardization  
- Handling missing/zero values  
- Feature scaling for better model performance  

---

## 🛠️ Technologies Used
- Python 🐍  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 🤖 Machine Learning Algorithms
The following models were implemented and compared:

- Support Vector Machine (SVM) ✅ (Best Performing)  
- Logistic Regression  
- Random Forest  

---

## ⚙️ Project Workflow
1. Load the dataset  
2. Data exploration and analysis  
3. Data preprocessing and standardization  
4. Train-test data splitting  
5. Train machine learning models  
6. Model evaluation using:
   - Accuracy score  
   - Confusion matrix  
   - Classification report  
7. Visualization of results  
8. Predict diabetes for new input data  

---

## 📈 Model Performance

| Model | Accuracy |
|------|--------|
| Support Vector Machine | **78.66%** |
| Logistic Regression | 75.97% |
| Random Forest | 74.02% |

👉 **SVM achieved the highest accuracy**

---

## 📊 Evaluation Metrics
- Accuracy Score  
- Confusion Matrix  
- Precision, Recall, F1-score  

---

## 📊 Visualizations
- Diabetes outcome distribution  
- Confusion matrix heatmap  
- Model performance comparison  

---

## 🔍 Example Prediction

**Input:**
(6, 148, 72, 35, 0, 33.6, 0.627, 50)

**Output:**
Diabetic
---
🏆 Conclusion
This project demonstrates how machine learning can assist in early diabetes detection using medical data. Among the models tested, Support Vector Machine achieved the best performance, making it the most effective model for this task.
---
💡 Key Learnings
Importance of data preprocessing and scaling
Model comparison improves decision-making
Visualization helps interpret results
Machine learning can support healthcare diagnostics
---
👨‍💻 Author
Shriram Baskaran

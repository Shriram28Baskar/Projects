Diabetes Prediction using Machine Learning This project uses machine learning algorithms to predict whether a person has diabetes based on medical diagnostic measurements such as glucose level, BMI, insulin level, blood pressure, and age. The model is trained using the PIMA Indians Diabetes Dataset

Diabetes Prediction using Machine Learning

Overview
This project implements a machine learning system that predicts whether a person has diabetes based on several medical attributes such as glucose level, BMI, blood pressure, insulin level, and age.

The model is trained using the "PIMA Indians Diabetes Dataset" and evaluates multiple machine learning algorithms to determine the best performing model.

Dataset
The dataset used in this project is the "PIMA Indians Diabetes Dataset", which contains medical diagnostic data of female patients.

Features in the dataset include:
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

Target Variable:
- Outcome (0 = Non-Diabetic, 1 = Diabetic)

Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

Machine Learning Algorithms Implemented
The following algorithms were used and compared:
- Support Vector Machine (SVM)
- Logistic Regression
- Random Forest

Model Performance
|                Model               | Accuracy   |
|------------------------------------|----------- |
|       Support Vector Machine       |   78.66%   |
|         Logistic Regression        |   75.97%   |
|            Random Forest           |   74.02%   |

SVM performed the best among the tested models.

Project Workflow:
1. Load the dataset
2. Data exploration and analysis
3. Data preprocessing and standardization
4. Train-test data splitting
5. Training machine learning models
6. Model evaluation using:
   - Accuracy score
   - Confusion matrix
   - Classification report
7. Visualization of results
8. Predict diabetes for new input data

Example Prediction:
Input medical data:
(6,148,72,35,0,33.6,0.627,50)
Output:
Diabetic

Visualizations
The project includes visualizations such as:
- Diabetes outcome distribution
- Confusion matrix heatmap
- Model performance evaluation

Conclusion
This project demonstrates how machine learning can assist in early diabetes detection by analyzing patient medical data. Among the models tested, Support Vector Machine achieved the highest accuracy

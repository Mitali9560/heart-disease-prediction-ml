# Heart Disease Prediction using Machine Learning

## 📌 Project Overview
This project predicts whether a person has heart disease based on medical attributes using machine learning.  
It is a **binary classification problem** where the output indicates the presence or absence of heart disease.

---

## 🛠️ Technologies Used
- Python  
- scikit-learn  
- Pandas  
- NumPy  
- VS Code  

---

## 📊 Dataset
The project uses a public heart disease dataset inspired by the **UCI / Kaggle Heart Disease dataset**.

### Features include:
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol level
- Fasting blood sugar
- Maximum heart rate
- Exercise-induced angina

### Target:
- `0` → No heart disease  
- `1` → Heart disease present  

---

## ⚙️ Project Workflow
1. Load and explore the dataset  
2. Separate features and target variable  
3. Split data into training and testing sets  
4. Train a Logistic Regression model  
5. Evaluate the model using performance metrics  

---

## 🧠 Machine Learning Model
- **Algorithm:** Logistic Regression  
- **Reason:** Suitable for binary classification and easy to interpret, especially for medical data  

---

## 📈 Results
- Accuracy: ~80%  
- High recall for heart disease cases  
- Evaluation metrics used:
  - Accuracy
  - Confusion Matrix
  - Precision
  - Recall
  - F1-score  

High recall is important in healthcare to reduce false negatives.

---

## ▶️ How to Run the Project
1. Install required libraries:
```bash
pip install pandas numpy scikit-learn
python heart_disease.py


## Author:
Mitali Kumane
B.Tech – Artificial Intelligence & Machine Learning 



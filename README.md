
# 🩺 Diabetes Prediction using Logistic Regression

This is a simple machine learning project that predicts whether a patient has diabetes or not based on their **Glucose Level**, **Blood Pressure**, and **Age** using a **Logistic Regression** model.

---

## 📌 Project Features

- Built using Python and scikit-learn
- User inputs are taken in real-time through console
- Predicts diabetes with trained model
- Evaluates model using accuracy, confusion matrix, and classification report
- Feature scaling is applied using StandardScaler

---

## 💾 Dataset

A small custom dataset with the following features:
- `Glucose_Level`  
- `BP` (Blood Pressure)  
- `Age`  
- `Diabetes(0/1)` – Target label (1 = has diabetes, 0 = no diabetes)

---

## 🧠 Technologies Used

- Python  
- Pandas, NumPy – Data handling  
- Scikit-learn – Model building, scaling, and evaluation

---

## 📊 Workflow

1. **Data Creation:** A custom dataset of 6 patients is created  
2. **Data Preprocessing:**
   - Features and labels are separated
   - Feature scaling using `StandardScaler`
3. **Model Training:** Logistic Regression  
4. **Prediction:** 
   - User enters values (glucose, BP, age)
   - Model predicts 0 (No diabetes) or 1 (Diabetes)
5. **Evaluation:** 
   - Accuracy Score
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)

---

# 💳 Credit Card Fraud Detection

## 📌 Overview
This project aims to detect fraudulent credit card transactions using machine learning techniques. The dataset is highly imbalanced, making fraud detection a challenging task.

---

## 🎯 Objective
- Identify fraudulent transactions
- Handle imbalanced data
- Build and evaluate classification models

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Imbalanced-learn (SMOTE)

---

## 📂 Dataset
- Contains transaction details
- Features are anonymized (V1, V2, ..., V28)
- Target variable:
  - 0 → Genuine
  - 1 → Fraud

---

## ⚙️ Steps Performed

### 1. Data Loading
- Loaded dataset using Pandas

### 2. Data Exploration
- Checked data structure
- Identified class imbalance

### 3. Data Preprocessing
- Scaled transaction amount
- Checked missing values

### 4. Handling Imbalance
- Used undersampling / SMOTE

### 5. Model Building
- Logistic Regression
- Random Forest Classifier

### 6. Model Evaluation
- Confusion Matrix
- Precision, Recall, F1-score

---

## 📊 Results
- Random Forest performed better in detecting fraud
- High recall achieved for fraud detection

---

## 📈 Key Learnings
- Importance of handling imbalanced datasets
- Evaluation metrics matter more than accuracy
- Practical implementation of ML classification models

---

## 🚀 Future Improvements
- Use advanced models (XGBoost, LightGBM)
- Hyperparameter tuning
- Real-time fraud detection system

---

## 👨‍💻 Author
**Fazal M Shaikh**  
🔗 LinkedIn: http://linkedin.com/in/fazalmshaikh  
🔗 GitHub: https://github.com/fazal-shaikh

# Task-8
# Customer Subscription Prediction using Decision Tree

## 📌 Overview
This project predicts whether a customer will subscribe to a term deposit using the Bank Marketing dataset. A Decision Tree Classifier is used to model customer behavior and generate interpretable decision rules.

---

## 📂 Dataset Information
- Dataset: Bank Marketing Dataset
- Separator: Semicolon (;)
- Target Variable:
  - y (yes = subscribed, no = not subscribed)

### Key Features:
- age
- job
- marital
- education
- default
- housing
- loan
- contact
- month
- day_of_week
- duration
- campaign
- pdays
- previous
- poutcome
- emp.var.rate
- cons.price.idx
- cons.conf.idx
- euribor3m
- nr.employed

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 🔧 Project Workflow

### 1. Data Loading
- Loaded dataset using `sep=';'`
- Cleaned column names

### 2. Data Cleaning
- Handled missing values using:
  - Median (numerical)
  - Mode (categorical)
- Cleaned inconsistent text (lowercase, removed spaces)

### 3. Feature Encoding
- Used OneHotEncoder for categorical variables

### 4. Train-Test Split
- 80% training, 20% testing
- Used `random_state=42` for reproducibility

### 5. Model Training
- Decision Tree Classifier
- Controlled overfitting using `max_depth=4`

### 6. Visualization
- Decision Tree plotted using `plot_tree()`

### 7. Model Evaluation
- Classification Report (Precision, Recall, F1-score)
- Accuracy comparison (Train vs Test)

---

## 📊 Results
- Model successfully predicts customer subscription behavior
- Decision Tree provides interpretable rules
- Controlled overfitting using depth limitation

---

## 📈 Outputs
- Decision Tree Visualization
- Classification Report
- Train vs Test Accuracy

---

## 🎯 Key Learnings
- Handling real-world categorical data
- Decision Tree interpretability
- Overfitting detection and control
- Business rule extraction from ML models

---

## 🚀 Future Improvements
- Use Random Forest or Gradient Boosting
- Hyperparameter tuning
- Feature importance analysis

---

## 👩‍💻 Author
Navya Mahamkali

# Customer Churn Prediction (Random Forest)

## 📌 Overview
This project predicts **customer churn** (whether a customer will leave the service) using a **Random Forest Classifier**.  
The dataset includes customer demographics, subscription details, usage patterns, payment behavior, and support interactions.  
The goal is to build a robust model to identify customers at risk of churning, enabling businesses to take proactive retention actions.

---

## 🎯 Objectives
- Analyze customer demographics and behaviors to detect churn patterns.  
- Handle missing values and data imbalance (using **SMOTE**).  
- Engineer new features (e.g., customer segmentation based on spending).  
- Train and evaluate a **Random Forest model**.  
- Compare model performance using Accuracy, Precision, Recall, F1-Score, and AUC-ROC.  
- Save the best-performing model for deployment.

---

## 🛠️ Tech Stack
- **Python 3.10+**  
- **Libraries**: pandas, numpy, seaborn, matplotlib, scikit-learn, imbalanced-learn  

---

## 📊 Dataset
The project uses two datasets:  
- `customer_churn_dataset-training-master.csv`  
- `customer_churn_dataset-testing-master.csv`  

Both are combined and preprocessed before training.  

---

## 🚀 Steps Implemented
1. Load and clean the data (handle missing values & drop irrelevant columns).  
2. Perform **feature engineering** (e.g., High-Value vs Regular customers).  
3. Encode categorical features and scale numerical ones.  
4. Apply **SMOTE** to balance churn vs non-churn samples.  
5. Train a **Random Forest Classifier** with tuned hyperparameters.  
6. Evaluate model with:
   - Classification report  
   - Confusion matrix  
   - ROC curve  
   - Feature importance chart  
7. Save the final model with accuracy and timestamp in the filename.  

---

## 📈 Results
- **Random Forest** achieved:  
  - Accuracy ≈ **92–93%**  
  - Recall ≈ **98%** (very strong at catching churners)  
  - AUC-ROC ≈ **0.95**

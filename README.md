# 📊 Customer Churn Prediction  

## 📌 Project Overview  
This project predicts **customer churn** using machine learning.  
The dataset is from a telecom company, and the goal is to classify whether a customer will churn based on features like **contract type, monthly charges, and tenure**.  

The workflow covers **EDA → preprocessing → model training → evaluation → explainability** with XGBoost and SHAP.  

---

## 📂 Dataset  
- **Source:** Telco Customer Churn dataset  
- **Target Variable:** `Churn` (Yes/No → Converted to 1/0)  
- **Features:** Demographics, service subscription details, account tenure, and charges  

---

## ⚙️ Technologies Used  
- **Python Libraries:** pandas, numpy, seaborn, matplotlib  
- **Machine Learning:** scikit-learn, imbalanced-learn, XGBoost  
- **Explainability:** SHAP (SHapley Additive exPlanations)  
- **Development:** Jupyter Notebook / Google Colab  
- **Version Control:** Git & GitHub  

---

## 🚀 Project Workflow  
1. **Data Preprocessing**  
   - Handle missing values  
   - Encode categorical variables  
   - Scale numerical features  
   - Balance classes with SMOTE  

2. **Exploratory Data Analysis (EDA)**  
   - Churn rate distribution  
   - Correlation heatmap  
   - Feature distributions  

3. **Model Training**  
   - Algorithm: XGBoost Classifier  
   - Hyperparameter tuning with RandomizedSearchCV  
   - Train-Test Split (80-20)  

4. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1-score  
   - ROC-AUC Curve  
   - Confusion Matrix (heatmap)  
   - Precision-Recall Curve  

5. **Explainability**  
   - Feature importance (XGBoost)  
   - SHAP global summary plot  
   - SHAP local force plots for individual predictions  

---

## 📌 How to Run the Project  

Clone the repository:  
```bash
git clone https://github.com/aditi-tato/customer-churn-prediction.git
cd customer-churn-prediction

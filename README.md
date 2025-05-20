# Customer_Churn_Prediction-

## 📌 Project Overview
This project predicts customer churn using machine learning techniques. The dataset used is from a telecom company, and the goal is to classify whether a customer will churn or not based on various features such as contract type, monthly charges, and tenure.

## 📂 Dataset
- **Source:** Telco Customer Churn dataset
- **Target Variable:** `Churn` (Yes/No -> Converted to 1/0)
- **Features:** Demographics, service subscription details, account tenure, and charges

## ⚙️ Technologies Used
- **Python** (pandas, numpy, seaborn, matplotlib)
- **Machine Learning:** Scikit-learn (Random Forest Classifier)
- **Jupyter Notebook / Google Colab**
- **Git & GitHub**

## 🚀 Project Workflow
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature selection
2. **Exploratory Data Analysis (EDA)**
   - Distribution of churn rates
   - Correlation heatmap
3. **Model Training**
   - Random Forest Classifier
   - Train-Test Split (80-20)
4. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix
   - ROC-AUC Curve
5. **Deployment**
   - Model saved as `churn_model.pkl`
   - Ready for integration into web applications

## 📌 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/aditi-tato/customer-churn-prediction.git
   cd customer-churn-prediction
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Load `customer_churn.ipynb` and execute all cells.

## 📄 Model Deployment (Future Scope)
- **Flask API** for serving predictions
- **Web UI with Streamlit**
- **Deploy on Heroku/AWS**

## 🤝 Contributing
Feel free to fork this repository and contribute improvements! 🚀


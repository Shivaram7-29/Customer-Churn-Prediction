# 🚀 Customer Churn Prediction

This project predicts whether a customer will churn using Machine Learning.

---

## 📌 Problem Statement
Customer churn is a major issue for businesses.  
This project helps identify customers likely to leave, allowing companies to take preventive action.

---

## 📊 Dataset
- Telco Customer Churn Dataset
- Contains customer demographics, services, and account info

---

## ⚙️ Steps Performed

1. Data Cleaning
   - Converted TotalCharges to numeric
   - Removed missing values
   - Dropped irrelevant columns (customerID)

2. Exploratory Data Analysis (EDA)
   - Analyzed churn distribution
   - Studied gender and tenure patterns

3. Feature Engineering
   - Applied one-hot encoding using `get_dummies`
   - Converted target variable into binary

4. Model Training
   - Logistic Regression model used

5. Evaluation
   - Accuracy score calculated on test data

---

## 📈 Results

- Model Accuracy: ~78%
- Key Insights:
  - Customers with low tenure are more likely to churn
  - Monthly charges influence churn behavior

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📁 Project Structure

Customer-Churn-Prediction/
│── churn_prediction.ipynb
│── README.md

---

## 🔥 Future Improvements

- Try advanced models (Random Forest, XGBoost)
- Hyperparameter tuning
- Deploy as a web app

---

## 👨‍💻 Author

- Shiva Ram


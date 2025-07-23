# Credit Risk Prediction using Machine Learning

This project aims to predict whether a person is a **Good** or **Bad** credit risk based on their demographic and financial attributes using supervised machine learning techniques.

---

## 📌 Objective

To develop a predictive model that can help financial institutions assess the credit risk of individuals by analyzing historical loan applicant data.

---

## 📊 Dataset

- **Name**: German Credit Data  
- **Format**: CSV  
- **Source**: [Kaggle – German Credit Data](https://www.kaggle.com/datasets/uciml/german-credit)  
- **Shape**: 1000 rows × 10 columns  
- **Target Variable**: `Risk` (values: Good, Bad)

---

## 🧾 Features

| Feature               | Description                              |
|----------------------|------------------------------------------|
| Age                  | Age of the individual                    |
| Sex                  | Gender (Male/Female)                     |
| Job                  | Job category (0–3)                       |
| Housing              | Type of housing (own, rent, free)       |
| Saving accounts      | Savings account status                   |
| Checking account     | Checking account status                  |
| Credit amount        | Credit amount requested                  |
| Duration             | Loan duration in months                  |
| Purpose              | Purpose of the loan                      |
| Risk                 | Credit risk status (Good/Bad)            |

---

## 🛠️ Technologies Used

- Python 3.12  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  

---

## ⚙️ Workflow

1. Load and inspect the dataset  
2. Handle missing values  
3. Encode categorical variables  
4. Split the dataset into training and testing sets  
5. Train a Logistic Regression model  
6. Evaluate the model using accuracy and classification report  
7. Test the model with custom user input  

---

## 📈 Model Evaluation

**Model Used**: Logistic Regression


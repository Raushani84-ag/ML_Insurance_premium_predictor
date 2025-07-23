# 🏥 Insurance Premium Prediction using Machine Learning

This project is an end-to-end Machine Learning application that predicts the **health insurance premium amount** based on user information like age, income, medical history, lifestyle habits, and region. It demonstrates the power of data-driven decision-making in the health insurance domain.

---

## 🔍 Problem Statement

Insurance companies often face challenges in estimating fair and personalized premiums for clients. Traditional models may not consider multiple influencing factors effectively. This project aims to build a **machine learning model** that predicts premiums based on key user attributes.

---

## 📊 Features Used

- Age
- Gender
- Region
- Number of Dependents
- Annual Income (in Lakhs)
- BMI Category
- Smoking Status
- Genetical Risk
- Marital Status
- Type of Insurance Plan
- Medical History (Disease List)

---

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**: 
  - Pandas, NumPy
  - Scikit-learn
  - Matplotlib & Seaborn (EDA)
- **Model**: Random Forest Regressor (tuned)
- **Deployment-ready structure**

---

---

## 🔄 Data Preprocessing

- Handled missing values in categorical features using imputation.
- One-hot encoding for categorical variables.
- Applied **MinMax Scaling** to normalize numeric inputs.
- Added a custom feature: `normalized_risk_score` (from medical history).

---

## ⚙️ How to Run

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/insurance-premium-predictor.git
   cd insurance-premium-predictor
pip install -r requirements.txt
python app/main.py


Raushani Kymari
Final Year Agricultural Engineering | Aspiring Agri-Data Scientist
---


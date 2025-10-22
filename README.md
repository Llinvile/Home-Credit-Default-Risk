# 🏦 Home Credit Default Risk — Loan Repayment Prediction

---

### 📘 Overview
This project predicts how capable each loan applicant is of repaying a loan, based on historical application and financial data.   It is based on the [Home Credit Default Risk Challenge on Kaggle](https://www.kaggle.com/c/home-credit-default-risk).

----

### 🎯 Objective
To build a **machine learning model** that can accurately predict the **probability of default**, helping financial institutions make informed lending decisions and reduce risk exposure.

----

### ⚙️ Workflow
1. **Data Exploration & Cleaning**
   - Handled missing values and categorical encoding.
   - Explored distributions, correlations, and outliers.

2. **Feature Engineering**
   - One-hot encoding for categorical variables.
   - Scaling and feature importance analysis.

3. **Model Training — LightGBM**
   - LightGBM classifier for efficient and accurate training.
   - Hyperparameters optimized for AUC performance.

4. **Model Evaluation**
   - **Metrics:** ROC-AUC, Precision, Recall, F1-score.
   - **Visuals:** Confusion matrix and top 30 feature importances.

---

### 📈 Results
| Metric | Score |
|---------|-------|
| ROC-AUC | *~0.77–0.79* |
| Precision | *~0.65* |
| Recall | *~0.72* |
| F1 Score | *~0.68* |

*(Scores may vary slightly by run.)*

---

### 🔍 Key Insights
- External risk scores and income-related features are top predictors of loan default.
- LightGBM outperformed traditional models (logistic regression, random forest) in both speed and accuracy.
- The model provides a solid foundation for **credit risk scoring systems**.

---

### 🧠 Tech Stack
- Python (Pandas, NumPy, Scikit-learn, LightGBM)
- Matplotlib & Seaborn for visualisation
- Jupyter Notebook

---

### 🚀 Next Steps
- Implement **hyperparameter tuning** with Optuna or GridSearchCV.
- Create a **dashboard** (Tableau) for stakeholder reporting.
- Explore **model explainability** with SHAP values.

---

### 🧑‍💻 Author
**Llinvile de Jongh**  
Project| 

# 🏦 **Loan Prediction Using Machine Learning and Python**

## 🎯 **Aim**
This project aims to leverage **pandas, matplotlib, and seaborn** for data analysis and visualization, while utilizing **XGBoost and scikit-learn** for machine learning. Our primary objectives include:

- Extracting insights from the dataset using Python libraries.
- Hyperparameter tuning with **Grid Search Cross-Validation** to optimize the **XGBoost** model.
- Predicting whether a loan applicant can **repay the loan** using **Voting Ensemble Techniques**, which combine multiple machine learning algorithms for improved accuracy.

---

## 📊 **Dataset Attributes**
The dataset consists of the following features:
- **Loan_ID** – Unique identifier for the loan.
- **Gender** – Male/Female.
- **Married** – Marital status.
- **Dependents** – Number of dependents.
- **Education** – Graduate/Not Graduate.
- **Self_Employed** – Self-employed status.
- **Applicant_Income** – Income of the applicant.
- **Coapplicant_Income** – Income of the co-applicant.
- **Loan_Amount** – Loan amount requested.
- **Credit_History** – History of previous loan repayments.
- **Property_Area** – Urban/Semi-Urban/Rural.
- **Loan_Status** – Approved (Y) or Rejected (N).

---

## 🔍 **Key Observations from Data**
- **Income Trends:**
  - Male and married applicants tend to have higher incomes.
  - Female and married applicants have the lowest incomes.
  - Graduated applicants earn more than non-graduates.
  - Married and graduated applicants have the highest incomes.
  - Non-self-employed applicants earn more than self-employed applicants.
  - Applicants with **more dependents** tend to earn less.
  - Urban property owners with a **credit history** have higher incomes.
  - Graduates with a **credit history** earn more.

- **Loan & Income Correlation:**
  - Loan Amount is **linearly dependent** on Applicant Income.
  - Heatmaps reveal a **high positive correlation** between Applicant Income and Loan Amount.

- **Demographic Insights:**
  - More **male applicants** than female applicants.
  - More **married applicants** than unmarried applicants.
  - Majority of applicants have **no dependents**.
  - More applicants have **graduation** than non-graduation.
  - **Semi-urban areas** have the highest number of applicants, while rural areas have the least.

---

## ⚙️ **Technologies Used**
- **Python** – Core programming language.
- **pandas & NumPy** – Data manipulation.
- **matplotlib & seaborn** – Data visualization.
- **XGBoost & scikit-learn** – Machine learning models.
- **GridSearchCV** – Hyperparameter tuning.

---

## 📜 **License**
This project is licensed under the **MIT License**. See the LICENSE file for details.

---

## 🙌 **Acknowledgments**
✅ **Kaggle** for providing the dataset.  
✅ Developers and contributors of open-source libraries used in this project.

---

## 📬 **Get in Touch**
Have questions or suggestions? Feel free to reach out via the **Issues** section on GitHub! 🚀

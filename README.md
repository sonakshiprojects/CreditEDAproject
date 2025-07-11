# 🧠 Credit Risk EDA and Default Prediction

This project focuses on **Exploratory Data Analysis (EDA)** and a **Machine Learning (ML)** model using a credit card client dataset. The main goal is to uncover patterns behind credit card default and apply a simple predictive model to demonstrate additional data science capabilities.

---

## 📁 Dataset

- creditdetails.csv

- Number of records: 30,000 clients  
- Key features: Demographics, payment history, bill amounts, previous payments  
- Target variable: `default.payment.next.month` (0 = no default, 1 = default)

---

## 📊 Project Structure

| Step | Description |
|------|-------------|
| 1. | Importing and cleaning data |
| 2. | Univariate analysis |
| 3. | Bivariate and multivariate analysis |
| 4. | Binning and feature engineering |
| 5. | Data preprocessing & handling imbalance |
| 6. | Logistic Regression model (ML step) |

---

## 🔍 Key EDA Insights

- Most clients are aged 20–40, with a sharp decline in higher age brackets.
- A majority of defaulters had delayed payments in recent months (`PAY_0`, `PAY_2`).
- Credit limits are right-skewed, with most under \$10,000 USD.
- Females make up a larger proportion of defaulters despite being fewer in the dataset.

---

## 🤖 Machine Learning (Lightweight Add-on)

A **Logistic Regression** model with `class_weight='balanced'` was trained to predict defaults:
- Achieved ~69% overall accuracy
- Recall for defaulters improved to 64% (vs ~24% baseline)
- Top predictive feature: `PAY_0` (recent payment behavior)

This ML step helped validate the EDA findings and demonstrated basic predictive modeling skills.

---

## 📌 Tools & Libraries

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **scikit-learn** (Logistic Regression, preprocessing, metrics)
- Jupyter Notebook

---

## ✅ Conclusion

The project showcases a complete data science workflow — from **cleaning and exploration** to **interpretation and light prediction**. It demonstrates how EDA can uncover valuable insights and how ML can complement analysis in high-impact areas like credit risk.

---

## 👩‍💻 Author

**Sonakshi Kumar**  
[LinkedIn](https://www.linkedin.com) | [GitHub](https://github.com)


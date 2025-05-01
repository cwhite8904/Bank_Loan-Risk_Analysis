# Bank_Loan-Risk_Analysis
Power BI dashboard + ML model to analyze and predict loan default risk using borrower demographics, income, and debt-to-income ratio.
# 📊 Loan Default Risk Analysis Dashboard

This project analyzes loan applicant data to uncover default risk patterns based on age, employment history, income, and debt ratios. It combines interactive Power BI dashboards with a machine learning model built in Google Colab to enhance financial decision-making.

![Dashboard Preview](dashboard_preview.png)

---

## 🚀 What’s Included

- **Power BI Dashboard (.pbix)** with 4 polished pages:
  - KPI Summary
  - Risk Analysis
  - Drill-Down Table
  - Summary Landing Page
- **Google Colab Notebook (.ipynb)** using Logistic Regression to predict defaults
- **README** with project context and insights

---

## 📁 Project Structure

## 🖥 Dashboard Pages

- **KPI Summary** – High-level metrics: Total Customers, Default Rate %, Avg Income, DTI
- **Risk Analysis** – Visualizes default trends by Age Group, Employment Group, and Debt Risk
- **Drill-Down Table** – Filterable customer-level detail with conditional formatting
- **Summary Page** – Project intro, key insights, and navigation buttons

---

## 🔍 Key Insights

- The overall loan default rate is **15.9%**
- Customers flagged as **High Risk** based on debt-to-income ratio account for the majority of defaults (30%+)
- Borrowers under age 35 have the **highest default rates**
- Applicants with **<5 years of employment** show increased default risk

---

## 🤖 Machine Learning (Colab Notebook)

We use **Logistic Regression** to predict whether a customer is likely to default based on key features:
- `age`, `income`, `debtinc`, `creddebt`, `othdebt`, `employ`, and `ed`

Model steps:
- Data preprocessing
- Train/test split
- Model training (Logistic Regression)
- Evaluation with confusion matrix, accuracy, precision/recall

📄 [View Notebook](bank_loan_analysis.ipynb)

---

## 🧠 Skills Demonstrated

- Power BI Data Modeling & DAX
- KPI Cards, Pie Charts, Bar Charts, Drilldown Tables
- Conditional Formatting by Rules
- Predictive Analytics with Logistic Regression (scikit-learn)
- GitHub Project Documentation

---

## 📎 How to Use This Project

1. Download the `.pbix` file to explore or customize the dashboard
2. Open the `.ipynb` notebook in Google Colab to review the model
3. Fork this repo to use it in your own portfolio

---

## 📬 Contact

**Chris White**  
📍 Kansas City | 💻 MBA in AI & Business Analytics  
📫 [LinkedIn](https://linkedin.com/in/chris-white-80462425a)  
🐱 [GitHub](https://github.com/yourusername)

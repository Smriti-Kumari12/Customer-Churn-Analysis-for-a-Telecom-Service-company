# Customer-Churn-Analysis-for-a-Telecom-Service-company
# 📊 Customer Churn Analysis & Prediction | SQL • Power BI • Machine Learning

## 🔍 Project Overview
In today’s competitive business environment, customer retention is critical for long-term growth.  
This project focuses on **end-to-end customer churn analysis and prediction** for a **Telecom company**, combining:

- **ETL pipeline using SQL Server**
- **Interactive Power BI dashboards**
- **Machine Learning–based churn prediction (Random Forest)**

The goal is to transform raw customer data into **actionable business insights** and proactively identify customers at risk of churning.

---

## 🎯 Business Objectives
- Analyze customer churn across multiple dimensions
- Identify high-risk churn segments
- Support data-driven marketing and retention strategies
- Predict future churners using Machine Learning

---

## 👥 Target Audience
Although the dataset is telecom-based, the approach is **industry-agnostic** and applicable to:
- Telecom
- Retail
- BFSI
- SaaS
- Healthcare
- Subscription-based businesses

Any organization focused on **customer retention** can leverage this framework.

---

## 🛠 Tech Stack
- **Database:** Microsoft SQL Server (SSMS)
- **BI Tool:** Power BI
- **Programming:** Python
- **ML Library:** Scikit-Learn
- **Data Handling:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn

---

## 📂 Dataset & Resources
- Source: Customer churn CSV file
- ETL handled via SQL Server
- Color palette used in Power BI dashboard:

---

## ⚙️ Project Architecture
CSV File
↓
SQL Server (Staging → Production)
↓
Power BI (Historical Analysis Dashboard)
↓
Python ML Model (Random Forest)
↓
Predicted Churn Data
↓
Power BI (Churn Prediction Dashboard)
---

## 🧩 Step 1: ETL Process (SQL Server)
- Created database: `db_Churn`
- Imported raw data into **staging table**
- Performed:
  - Data type corrections
  - Null handling
  - Data cleansing
- Created **production table**
- Built SQL **views** for Power BI and ML consumption:
  - `vw_ChurnData`
  - `vw_JoinData`

---

## 🔎 Step 2: Data Transformation (Power BI)
- Created derived columns:
  - Churn Status (Binary)
  - Monthly Charge Range
- Created mapping tables:
  - Age Groups
  - Tenure Groups
- Unpivoted service usage data for flexible analysis

---

## 📐 Step 3: Key Metrics
- Total Customers
- New Joiners
- Total Churn
- Churn Rate (%)

---

## 📊 Step 4: Power BI Dashboard
### 🔹 Summary Page
- KPI Cards (Customers, Churn, Churn Rate)
- Demographic analysis (Age, Gender)
- Account insights (Contract, Payment Method, Tenure)
- Geographic churn distribution
- Service-wise churn impact

### 🔹 Churn Reason Tooltip Page
- Churn Category
- Churn Reason breakdown

---

## 🤖 Step 5: Churn Prediction (Machine Learning)
- Algorithm Used: **Random Forest Classifier**
- Reason:
  - Handles non-linear relationships
  - Reduces overfitting
  - High accuracy for classification problems

### ML Workflow:
- Data extracted from SQL views
- Categorical encoding using LabelEncoder
- Train-test split (80/20)
- Model evaluation:
  - Confusion Matrix
  - Classification Report
- Feature importance analysis
- Prediction on **newly joined customers**

---

## 📈 Step 6: Predicted Churn Visualization (Power BI)
- Imported predicted churn data
- Created a **Churn Prediction Page**:
  - Customer-level churn table
  - Demographic churn distribution
  - Contract & payment risk analysis
  - State-wise churn prediction

---

## 🚀 Key Insights
- Short-tenure customers show higher churn probability
- Month-to-month contracts are more churn-prone
- Certain payment methods correlate with higher churn
- Service usage significantly impacts churn behavior

---

## 📌 Business Impact
- Enables **proactive retention campaigns**
- Helps prioritize **high-risk customers**
- Improves **customer lifetime value (CLV)**
- Supports executive-level decision making

---

## 📷 Dashboard Preview
> *(Add Power BI screenshots here)*

---

## 📁 Repository Structure
├── SQL Scripts
├── Power BI Dashboard (.pbix)
├── ML Notebook (.ipynb)
├── Prediction Output (CSV)
└── README.md
---

## 🙌 Conclusion
This project demonstrates a **complete analytics lifecycle** — from raw data ingestion to predictive insights — using industry-standard tools.  
It showcases strong skills in **SQL, Power BI, and Machine Learning**, making it suitable for **Data Analyst / Business Analyst / Analytics roles**.

---

⭐ If you found this project insightful, feel free to star the repository!

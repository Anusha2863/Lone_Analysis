# 🏦 Loan Approval Analysis – End-to-End Data Analytics Project

## 📌 Project Overview

This project demonstrates a complete **End-to-End Data Analytics workflow** using a Loan Approval dataset.

The project transforms raw loan application data into actionable insights through structured data processing, SQL analysis, and an interactive Power BI dashboard.

It reflects the full lifecycle of a Data Analyst role:

- Data Loading  
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- SQL-Based Business Analysis  
- Data Modeling & DAX  
- Interactive Power BI Dashboard  
- Business Insight Reporting  

## 🎯 Business Problem / Objective

Financial institutions process large volumes of loan applications but need better visibility into:

- Loan approval trends  
- Applicant demographics  
- Income impact on loan approval  
- Property area performance  
- Risk-based approval patterns  

The objective of this project is to:

✔ Clean and prepare raw loan data  
✔ Analyze approval trends  
✔ Identify key approval factors  
✔ Build interactive dashboards  
✔ Support data-driven lending decisions  

## 🗂 Dataset

- Format: CSV  
- Type: Structured Loan Application Dataset  
- Used across Python, SQL databases, and Power BI  

### Key Features:

- Loan_ID  
- Gender  
- Married  
- Dependents  
- Education  
- Self_Employed  
- ApplicantIncome  
- CoapplicantIncome  
- LoanAmount  
- Loan_Amount_Term  
- Credit_History  
- Property_Area  
- Loan_Status  

The dataset contains both categorical and numerical variables suitable for statistical and business analysis.

## 🛠 Tools & Technologies Used

### 🐍 Python (Jupyter Notebook)
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

### 🗄 Databases
- PostgreSQL  
- MySQL  
- SQL Server  

### 📊 Power BI
- Data Modeling  
- DAX Measures  
- KPI Cards  
- Interactive Visuals  
- Slicers  
- Cross-filtering  


# 🔄 Project Workflow

## 1️⃣ Data Loading

- Imported CSV dataset using Pandas  
- Inspected structure and column types  
- Checked dataset dimensions  
- Identified missing values  

📌 Outcome: Initial understanding of loan application dataset.


## 2️⃣ Exploratory Data Analysis (EDA)

- Analyzed loan approval distribution  
- Compared income vs loan amount  
- Studied approval trends by gender  
- Examined dependents impact  
- Evaluated property area distribution  
- Visualized approval rates using bar and donut charts  

📌 Outcome: Identified patterns affecting loan approval decisions.

## 3️⃣ Data Cleaning & Preprocessing

- Handled missing values in Gender, Dependents, LoanAmount  
- Standardized categorical values  
- Converted Loan_Status to Approved / Not Approved  
- Verified data consistency  
- Prepared cleaned dataset for SQL & BI tools  

📌 Outcome: Clean, reliable, analysis-ready dataset.

## 4️⃣ SQL Analysis

Cleaned dataset imported into:

- PostgreSQL  
- MySQL  
- SQL Server  

### SQL Techniques Applied:

- GROUP BY & HAVING  
- COUNT(), SUM(), AVG()  
- CASE WHEN conditions  
- Approval rate calculations  
- Property area comparisons  
- Gender-based approval analysis  

📌 Outcome: Extracted structured business insights using relational queries.


## 5️⃣ Data Modeling & DAX (Power BI)

- Created relationships between fields  
- Developed calculated measures  

### Example DAX Measures:

- Total Applicants  
- Approved Loans  
- Total Loan Amount  
- Approval Rate %  
- Income-based metrics  

📌 Outcome: Enabled dynamic KPI tracking and interactive reporting.


# 📊 Dashboard Preview

## 🖥 Main Dashboard – Executive View

Includes:

- KPI Cards (Total Applicants, Approved Loans, Total Loan Amount)  
- Loan Approval Distribution (Donut Chart)  
- Loan Amount by Property Area  
- Approved Loans by Gender  
- Dependents vs Approval Analysis  
- Interactive Slicers (Loan Status, Gender, Education, Property Area)

<img width="1440" height="787" alt="Lone_report" src="https://github.com/user-attachments/assets/ec36820f-6619-4c6c-8625-8d35297e9ee7" />


# 🔁 End-to-End Architecture Flow

Loan CSV → Python (EDA & Cleaning) → SQL Database → Power BI Modeling → Interactive Dashboard → Business Insights


# 📈 Key Insights / Findings

- ~68% of total applications are approved  
- Semiurban areas show higher loan distribution  
- Applicants with 0 dependents have higher approval rates  
- Male applicants show higher approval counts  
- Income and credit history significantly influence approval  


# ✅ Conclusion

This project successfully demonstrates:

✔ Complete End-to-End Data Analytics Lifecycle  
✔ Advanced Data Cleaning & Preprocessing  
✔ SQL-Based Business Analysis  
✔ Interactive Power BI Dashboard Development  
✔ Data-Driven Decision Support  

The Loan Approval Analysis Dashboard provides structured insights to improve financial lending strategies.


# ▶️ How to Run the Project

## 🔹 Python (EDA & Cleaning)

1. Open Jupyter Notebook  
2. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Run the notebook file inside `<a href ="https://github.com/Anusha2863/Lone_Analysis/blob/main/loan_eda.ipynb1.ipynb"> Notebook</a>'

## 🔹 SQL

- Import cleaned CSV file into your database  
- Execute queries from <a href = "https://github.com/Anusha2863/Lone_Analysis/blob/main/Lone_sql_queries"> Lone_sql</a>
## 🔹 Power BI

- Open '<a href = "https://github.com/Anusha2863/Lone_Analysis/blob/main/Lone_report.png">Report</a>`  
- Refresh dataset if required  

⭐ If you found this project helpful, feel free to star the repository!



<img width="1134" height="860" alt="Screenshot 2026-02-20 085224" src="https://github.com/user-attachments/assets/fce91e14-e317-4a62-9396-df2013db825e" />

inter

<img width="1187" height="900" alt="Screenshot 2026-02-20 085713" src="https://github.com/user-attachments/assets/74bc3dff-4c19-426f-b4be-e1bc6739957f" />

basic
<img width="1151" height="874" alt="Screenshot 2026-02-20 085104" src="https://github.com/user-attachments/assets/cd148a1f-9cb7-4292-b42b-1b1dbb19e86b" />

sql
<img width="1117" height="856" alt="Screenshot 2026-02-20 085520" src="https://github.com/user-attachments/assets/d874b8c8-2530-461d-9376-d5eef34d4300" />



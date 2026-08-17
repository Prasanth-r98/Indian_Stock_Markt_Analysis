📊 Indian Stock Market Performance Analysis

📌 Project Overview

This project analyzes and compares the stock market performance of Tata Consultancy Services (TCS) and Infosys from 2021 to 2025.

The project uses Python, SQL, Excel, and Power BI to perform data cleaning, exploratory data analysis (EDA), statistical analysis, data querying, and interactive visualization.

The main objective is to identify stock price trends, returns, trading volume, volatility, and overall performance of TCS and Infosys during the selected period.

---

🎯 Project Objectives

- Analyze historical stock market data of TCS and Infosys.
- Understand stock price movements and trends.
- Compare the performance of TCS and Infosys.
- Calculate daily returns.
- Analyze trading volume.
- Identify yearly performance patterns.
- Measure stock volatility.
- Perform statistical hypothesis testing.
- Use SQL to extract meaningful business insights.
- Build an interactive Power BI dashboard.
- Present the final findings in a structured report.

---

📂 Dataset

Companies

- TCS
- Infosys

Period

2021 – 2025

Main Columns

Column| Description
Date| Trading date
Company| Company name
Price| Closing stock price
Open| Opening stock price
High| Highest price of the day
Low| Lowest price of the day
Vol| Trading volume
Change%| Daily percentage change
Daily_Return| Calculated daily return

---

🛠️ Tools & Technologies

Python

- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook / Google Colab

SQL

- SQLite / SQL
- Data aggregation
- Filtering
- GROUP BY
- ORDER BY
- Aggregate functions
- Comparative analysis

Microsoft Excel

- Data preparation
- Data cleaning
- Sorting and filtering
- Basic calculations
- Data validation

Power BI

- Interactive dashboard
- KPI cards
- Line charts
- Bar charts
- Slicers
- Data visualization
- Comparative analysis

---

🔄 Project Workflow

Raw Stock Market Data
        ↓
Data Cleaning
        ↓
Data Preparation
        ↓
Exploratory Data Analysis
        ↓
Statistical Analysis
        ↓
SQL Analysis
        ↓
Excel Analysis
        ↓
Power BI Dashboard
        ↓
Final Report

---

🐍 Python & EDA

Python was used for data preprocessing, exploratory data analysis, return calculation, statistical analysis, and visualization.

Major EDA Activities

- Dataset structure inspection
- Missing value checking
- Duplicate value checking
- Data type validation
- Date conversion
- Sorting data chronologically
- Company-wise analysis
- Daily return calculation
- Price trend analysis
- Trading volume analysis
- Volatility analysis
- Outlier identification
- Year-wise performance analysis

Daily Return

Daily return was calculated using the percentage change in the stock price:

Daily Return = ((Today's Price - Previous Price) / Previous Price) × 100

---

📈 Statistical Analysis

Hypothesis testing was performed to compare the performance of TCS and Infosys.

A t-test was used to determine whether there was a statistically significant difference between the returns of the two companies.

Hypothesis

Null Hypothesis (H₀):

There is no significant difference between the returns of TCS and Infosys.

Alternative Hypothesis (H₁):

There is a significant difference between the returns of TCS and Infosys.

The statistical test results were interpreted using the calculated p-value and significance level.

---

🗄️ SQL Analysis

SQL was used to perform structured analysis on the stock market dataset.

SQL Analysis Included

- Company-wise average price
- Maximum stock price
- Minimum stock price
- Total trading volume
- Average daily return
- Year-wise performance
- Company comparison
- Sorting and filtering
- Aggregation using SQL functions

Example:

SELECT
    Company,
    AVG(Price) AS Average_Price,
    MAX(Price) AS Maximum_Price,
    MIN(Price) AS Minimum_Price
FROM stock_data
GROUP BY Company;

---

📊 Excel Analysis

Excel was used for data preparation and supporting analysis.

Excel Activities

- Data cleaning
- Sorting
- Filtering
- Calculations
- Company-wise comparison
- Return analysis
- Volume analysis
- Supporting data validation

---

📊 Power BI Dashboard

An interactive Power BI dashboard was created to visualize the stock market performance of TCS and Infosys.

Dashboard Components

KPI Cards

- Average Price
- Maximum Price
- Trading Volume
- Average Return

Charts

- TCS vs Infosys Price Trend
- Year-wise Performance
- Return Comparison
- Volatility Analysis
- Trading Volume Analysis

Filters / Slicers

- Company
- Year
- Date

The dashboard allows users to interactively compare the performance of both companies across different time periods.

---

🔍 Key Analysis Areas

The project focuses on answering the following questions:

1. How did TCS stock price perform from 2021 to 2025?
2. How did Infosys stock price perform during the same period?
3. Which company showed stronger price performance?
4. Which company had higher average returns?
5. Which company had higher trading volume?
6. How did stock performance change year by year?
7. Which stock showed higher volatility?
8. Is there a statistically significant difference between the returns of TCS and Infosys?
9. What major trends and patterns can be identified from the dataset?

---

💡 Key Insights

The analysis provides insights into:

- Long-term stock price trends.
- Differences in TCS and Infosys performance.
- Daily return behavior.
- Trading volume patterns.
- Year-wise stock performance.
- Stock volatility.
- Statistical differences in returns.
- Comparative investment performance.

«Note: Specific numerical findings are available in the project analysis, SQL outputs, Power BI dashboard, and final report.»

---

📁 Project Structure

Indian_Stock_Market_Analysis/
│
├── Data/
│   └── TCS_Infosys_2021_2025_Combined.xlsx
│
├── Python/
│   └── TCS_Infosys_EDA_2021_2025.ipynb
│
├── SQL/
│   └── TCS_Infosys_Stock_Analysis.sql
│
├── Excel/
│   └── TCS_Infosys_2021_2025_Combined.xlsx
│
├── PowerBI/
│   └── Indian_Stock_Market_Analysis.pbix
│
├── Screenshots/
│   ├── Python_EDA/
│   ├── SQL/
│   ├── PowerBI/
│   └── Statistical_Analysis/
│
├── Report/
│   ├── Indian_Stock_Market_Analysis_Report.docx
│   └── Indian_Stock_Market_Analysis_Report.pdf
│
└── README.md

---

🖼️ Project Screenshots

Screenshots of the following analysis stages are included in the project:

- Python EDA output
- Statistical / t-test output
- SQL analysis output
- Power BI dashboard

---

📑 Final Report

The complete project report contains:

- Introduction
- Objectives
- Dataset description
- Data cleaning
- Exploratory Data Analysis
- Statistical analysis
- SQL analysis
- Power BI dashboard
- Key findings
- Conclusion

---

🚀 Skills Demonstrated

This project demonstrates practical knowledge of:

- Data Cleaning
- Data Analysis
- Exploratory Data Analysis
- Statistical Analysis
- Python
- Pandas
- SQL
- Microsoft Excel
- Power BI
- Data Visualization
- Dashboard Development
- Business Insights
- Report Preparation

---

🎓 Project Type

Data Analytics / Exploratory Data Analysis Project

Project Title

Indian Stock Market Performance Analysis and Exploratory Data Analysis using Python, SQL, Excel & Power BI

---

⚠️ Disclaimer

This project is created for educational and data analytics purposes only.

The analysis and findings presented in this project should not be considered financial or investment advice.

---

👨‍💻 Author

Prasanth R

M.Com (Computer Applications)

Skills

Python | SQL | Excel | Power BI | Data Analytics | EDA

---

⭐ "If you find this project useful, feel free to explore..."

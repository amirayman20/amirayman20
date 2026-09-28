# 👋 Hi, I'm Amir Ayman

### Data Analyst · Inventory, Procurement & Sales Analytics

*Turning raw data into clear, actionable decisions.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amir-ayman-664513103)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/amirayman20)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:amirayman20@gmail.com)

📍 Saudi Arabia · 🎓 Google Data Analytics Certificate

---

## 🎯 About Me

I work in warehouse and procurement analytics for a retail pharmacy chain with **100+ branches**, where I turn sales, stock, and purchasing data into decisions that management can act on.

- Inventory analytics and purchase planning across a large branch network
- Management reporting and KPI design
- SQL data modeling, Power BI dashboards, and Python automation
- Passionate about clean, structured data models and clear business storytelling

---

## 🧰 Tech Stack & Tools

![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![ETL](https://img.shields.io/badge/ETL-4B8BBE?style=for-the-badge)
![Data Modeling](https://img.shields.io/badge/Data%20Modeling-000000?style=for-the-badge)

- **Querying & Modeling:** T-SQL, Data Warehousing (Medallion Architecture), ETL, stored procedures, views
- **BI & Reporting:** Power BI, DAX, Power Query, Excel (automated, color-coded reports)
- **Analysis & Automation:** Python (Pandas, NumPy, Matplotlib, Seaborn, GeoPandas), Jupyter Notebooks

---

## 🏭 Work-Inspired Projects

*Built from real inventory and purchasing problems in a large branch network, and published with synthetic data.*

### 🟠 1. Inventory Purchase Optimizer

**Repo:** [inventory-purchase-optimizer](https://github.com/amirayman20/inventory-purchase-optimizer)

Stock that looks healthy on paper is often trapped in weak branches. This tool separates *useful* stock from *total* stock before any purchase decision is made.

- Branch ABC classification based on sales contribution
- Useful-stock weighting by branch class (A, B, C)
- Distinguishes **slow items** (a purchasing problem) from **branch leakage** (a distribution problem)
- Purchase quantity from period need minus useful stock, with a fast-moving item adjustment
- Color-coded priorities (Fast / Medium / Slow / Dead) and a multi-sheet Excel report
- Configurable coverage days, safety days, and thresholds
- Includes a synthetic data generator, sample output, and analysis notebook

### 🟠 2. Inter-Branch Excess Rebalancer

**Repo:** [inter-branch-excess-rebalancer](https://github.com/amirayman20/inter-branch-excess-rebalancer)

Before buying more, find out whether the stock already exists somewhere else in the network.

- Calculates daily consumption, **excess**, and **need** per item per branch
- **Warehouse gate:** branch-to-branch transfers are suggested only when the central warehouse cannot cover demand
- Best-match logic: each item goes to the branch with the highest need, with no duplication across reports
- Expiry filter that excludes items too close to expiry from transfers
- One Excel transfer report per source → target branch pair, with a reason for each transfer
- Includes a synthetic data generator and a logic-flow diagram

---

## 🐍 Python Projects

### 🟡 3. Olist Brazilian E-Commerce: End-to-End Analytics

**Repo:** [Olist-E-Commerce-Analytics-End-to-End-Python-Project](https://github.com/amirayman20/Olist-E-Commerce-Analytics-End-to-End-Python-Project)

- Unified relational data model connecting 9 source tables
- Feature engineering: actual vs. estimated delivery time and delay periods
- Analysis of delivery delays and their effect on customer reviews
- Geospatial analysis of sales and logistics by state (GeoPandas)
- Modular, reusable scripts plus an exploratory notebook
- 20+ charts documenting the analysis

### 🟡 4. Sales Analysis 2019 (EDA)

**Repo:** [sales-analysis-2019-eda](https://github.com/amirayman20/sales-analysis-2019-eda)

- 12-month sales analysis with Pandas, Matplotlib, and Seaborn
- Data cleaning, exploratory analysis, and visualization
- Business insights drawn from the results

### 🟡 5. Netflix Movies & TV Shows Analytics

**Repo:** [netflix-data-analysis](https://github.com/amirayman20/netflix-data-analysis)

- Exploratory analysis of genre distribution, release trends, and content patterns
- WordCloud and bigram text analysis
- Fully documented notebook with a clear workflow

---

## 🗄️ SQL Projects

### 🟡 6. SQL Data Warehouse (Medallion Architecture)

**Repo:** [data-warehouse-sql-project](https://github.com/amirayman20/data-warehouse-sql-project)

- Bronze → Silver → Gold layers
- Real-world cleaning, transformation, and modeling
- Stored procedures, views, and optimized queries

### 🟡 7. SQL Data Analytics

**Repo:** [sql-data-analytics-project](https://github.com/amirayman20/sql-data-analytics-project)

- Exploratory analysis and performance metrics
- Segmentation and reporting
- Clean, optimized T-SQL

---

## 📊 Power BI Projects

### 🟡 8. Sales–Customer–Product Dashboard

**Repo:** [powerbi-sales-customer-product-dashboard](https://github.com/amirayman20/powerbi-sales-customer-product-dashboard)

- Built on top of the SQL Gold layer
- KPIs, trends, and segmentation
- Interactive visuals with a clean layout

### 🟡 9. Sales Performance Analysis

**Repo:** [Sales-Performance-Analysis](https://github.com/amirayman20/Sales-Performance-Analysis)

- Revenue, cost, profit, and sales count by country, customer, and year
- Power Query cleaning and DAX measures for the KPIs
- Interactive filters by gender, occupation, and education
- Built on the AdventureWorks dataset

### 🟡 10. Car Insurance Data Analysis

**Repo:** [Car-Insurance-Data-Analysis](https://github.com/amirayman20/Car-Insurance-Data-Analysis)

- Claims analysis by vehicle use, age group, region, and education level
- Built from a business requirements document and a data dictionary
- Helps identify high-risk segments and support pricing and retention decisions

### 🟡 11. HR Analytics Dashboard

**Repo:** [HR-Analytics-PowerBI-Dashboard](https://github.com/amirayman20/HR-Analytics-PowerBI-Dashboard)

- Attrition analysis by job category, salary band, and satisfaction level
- Power Query for cleaning and DAX for turnover, age, and experience metrics
- Quick filtering by department (Operations, Finance, HR, IT, Marketing, Sales)

### 🟡 12. UK Railway Ticket Analytics

**Repo:** [uk-railway-ticket-analytics](https://github.com/amirayman20/uk-railway-ticket-analytics)

- Revenue trends and ticket segmentation
- Delay analysis and customer behavior insights
- Interactive dashboards on a structured data model

---

## 📬 Let's Connect

I'm open to data analyst opportunities. Feel free to reach out.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amir-ayman-664513103)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/amirayman20)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:amirayman20@gmail.com)

---

⭐ If you find my work useful, feel free to star the repositories.

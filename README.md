# Gen Z Career & Mission Aspirations | Business Intelligence Dashboard

## 📌 Project Overview
Organizations face unprecedented challenges in attracting, onboarding, and retaining Gen Z talent due to shifting workplace expectations. This project delivers an end-to-end data analytics and business intelligence solution to decode the career drivers, salary structures, and mission alignment expectations of over **7,000+ respondents** across **1,800+ regions**.

By migrating raw survey data into a structured relational database and building multi-page interactive dashboards, this project provides HR leadership and executive stakeholders with actionable blueprints to optimize recruitment strategies, lower employee attrition, and reduce real estate overhead costs.

---

## 📈 Business Impact & Strategic Value
* **Talent Acquisition Optimization:** Identified that **50% of entry-level candidates** expect a starting salary within the 21k–25k bracket, allowing HR teams to calibrate compensation benchmarking to maximize offer-acceptance rates.
* **Corporate Overhead Reduction:** Visualized a dominant **46% preference for Hybrid work** layouts and **33% for Remote work**. This data allows corporate real estate stakeholders to transition to hot-desking models, potentially reducing office operational expenses by **25%–30%**.
* **Risk-Mitigation in Turnover:** Proved that **72.2% of respondents** reject companies lacking a defined corporate mission. Implementing the dashboard's cultural recommendation framework directly targets a reduction in early-stage (90-day) employee attrition.

---

## 🛠️ Tech Stack & Architecture
* **Database Management & Warehousing:** SQL, PostgreSQL (pgAdmin)
* **Data Transformation & Cleaning:** Advanced Microsoft Excel (Power Query, Text-to-Columns, Data Validation)
* **Business Intelligence & Visualizations:** Power BI (DAX, Data Modeling), Interactive Excel Dashboards (Pivot Tables, Slicers)

---

## 📊 Dashboard Architecture & Insights

### 1. Career Aspirations & Operational Setup (Power BI / Excel)
* **Core Metrics Tracked:** Average Salary Expectations, Workforce Demographics, Influencer Vectors.
* **Key Finding:** Traditional corporate structures fail to resonate; non-traditional drivers (World Leaders at 1.8k, Influencers at 1.2k) hold more recruitment marketing leverage than standard corporate outreach channels.

### 2. Mission & Workplace Culture Alignment (Power BI / Excel)
* **Core Metrics Tracked:** Corporate Mission Weight, Multi-Generational Retention Drivers, Team Size Preferences.
* **Key Finding:** Work-Life Balance is the absolute highest priority driver for workplace happiness (scoring 4.1k engagement), completely outpacing standalone financial incentives.

  Dashboard Preview

<img width="1600" height="667" alt="image" src="https://github.com/user-attachments/assets/fd33fb2c-4dff-475f-a7de-f73d7fd16170" />

<img width="1222" height="678" alt="image" src="https://github.com/user-attachments/assets/4292779f-78aa-47c7-a1c4-e5d53fadbc72" />
<img width="1214" height="671" alt="image" src="https://github.com/user-attachments/assets/ec30f97a-1794-4162-9299-b6012c2b2743" />

---

## 💻 Technical Implementation Details

### 1. Relational Database Setup & Querying
* Loaded raw flat files into a relational database system using PostgreSQL.
* Formulated analytical queries to aggregate survey responses, segment demographics, and extract regional metrics.
* Sample query used for extracting operational work setup preferences:
```sql
SELECT work_setup_preference, COUNT(*) as response_count
FROM genz_aspirations_data
GROUP BY work_setup_preference
ORDER BY response_count DESC;
```

### 2. Data Cleaning & Transformation (ETL)
* Utilized Excel and Power Query to handle missing fields, remove duplicate responses, and format regional data (pin codes).
* Standardized categorical text values to ensure seamless data modeling inside the BI tools.

---

## 🚀 Key Recommendations for Employers
1. **Calibrate Recruitment Channels:** Shift employer branding expenditures toward values-based marketing on social and community-oriented channels.
2. **Transition to Agile Workspaces:** Redesign corporate footprint strategies around a 46% hybrid-baseline to maximize workstation utilization efficiency.
3. **Embed Corporate Social Responsibility (CSR):** Embed mission statements directly into recruitment scripts to secure high-priority candidates early in the hiring cycle.

---

## 📂 Repository Structure
```text
├── Data/                     # Cleaned survey datasets (CSV/XLSX)
├── SQL_Queries/              # PostgreSQL scripts for aggregation and demographic segmentation
├── Dashboards/               # Power BI (.pbix) files and Excel dashboard deliverables
└── README.md                 # Project documentation and executive summary
```

---
## 👤 Contact & Collaboration
**Surbhi Sharma**  
📧 [surbhisharma06@gmail.com](mailto:surbhisharma06@gmail.com) | 💼 [LinkedIn](https://linkedin.com) | 💻 [GitHub](https://github.com)






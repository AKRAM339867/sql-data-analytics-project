# 📊 SQL Data Analytics Project

![SQL Server](https://img.shields.io/badge/Database-SQL%20Server-red?style=flat&logo=microsoftsqlserver)
![Language](https://img.shields.io/badge/Language-T--SQL-blue)
![License](https://img.shields.io/badge/License-MIT-green)

A comprehensive collection of SQL scripts designed for database exploration, analytical reporting, and business intelligence. This repository covers foundational database setup, exploratory data analysis (EDA), advanced metrics, time-series analysis, segmentation, and automated report views using T-SQL.

---

## 📁 Repository Structure


```text
sql-data-analytics-project/
├── scripts/                              # Core SQL analytical scripts
│   ├── 00_init_database.sql              # Database initialization and schema setup
│   ├── 01_database_exploration.sql       # Inspecting tables, schemas, and metadata
│   ├── 02_dimensions_exploration.sql     # Categorical and dimensional data profiling
│   ├── 03_date_range_exploration.sql     # Time scope and date boundary checks
│   ├── 04_measures_exploration.sql       # Aggregations, totals, and baseline metrics
│   ├── 05_magnitude_analysis.sql        # Data sorting and comparative sizing
│   ├── 06_ranking_analysis.sql          # Row ranking using ROW_NUMBER(), RANK(), DENSE_RANK()
│   ├── 07_change_over_time_analysis.sql # MoM, YoY, and period-over-period trends
│   ├── 08_cumulative_analysis.sql       # Running totals and moving averages
│   ├── 09_performance_analysis.sql      # Target vs. actual performance metrics
│   ├── 10_data_segmentation.sql         # Customer RFM and product categorization
│   ├── 11_part_to_whole_analysis.sql    # Percentage shares and ratio calculations
│   ├── 12_report_customers.sql          # Customer gold-layer view/report generation
│   └── 13_report_products.sql           # Product gold-layer view/report generation
├── FUNDING.yml                           # GitHub sponsor configuration
├── LICENSE                               # MIT License
└── README.md                             # Project documentation
```


---

## 📑 Script Breakdown & Analytical Scope

1. **Database Setup & Exploration (`00` – `03`)**: Initializes the environment and audits tables, dimensions, unique values, and time coverage.
2. **Core Analytics & Ranking (`04` – `06`)**: Calculates essential business KPIs, evaluates comparative magnitudes, and ranks entities across various metrics.
3. **Time-Series & Trend Analysis (`07` – `09`)**: Analyzes temporal growth patterns, cumulative revenue streams, running sums, and target achievements.
4. **Advanced Segmentation & Ratios (`10` – `11`)**: Segments customers/products into behavioral tiers and measures individual contributions to overall totals.
5. **Reporting Views (`12` – `13`)**: Constructs consolidated analytical views (`gold.report_customer` and `gold.report_products`) for BI dashboards and exports.

---

## 🚀 Getting Started

1. **Clone the Repository**:
   ```bash
   git clone [https://github.com/AKRAM339867/sql-data-analytics-project.git](https://github.com/AKRAM339867/sql-data-analytics-project.git)
Execute Scripts: Open SQL Server Management Studio (SSMS), connect to your instance, and run scripts/00_init_database.sql followed by any analysis script sequentially.

🛠️ Tech Stack
Database Engine: Microsoft SQL Server (T-SQL)

Tooling: SQL Server Management Studio (SSMS)

Version Control: Git & GitHub

## 👤 About the Author
Hi, I'm Akram Bechat! 👋

I specialize in Finance and Data Analytics, combining business domain knowledge with hands-on data engineering skills (SQL, Python, Excel, Power BI). I enjoy building scalable data pipelines, data warehouses, and reporting systems that transform raw business data into strategic insights.

💼 LinkedIn: [linkedin.com/in/akram-bechat-169651317]

🐙 GitHub: github.com/AKRAM339867

📧 Email: bechat.akram.encg@uhp.ac.ma

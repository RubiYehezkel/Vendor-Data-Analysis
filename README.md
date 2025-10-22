# Vendor Data Analysis

🏪 Vendor Performance & Sales Analysis
📖 Project Overview

This repository contains a complete workflow for analyzing real vendor sales and performance data, from ingestion to exploratory analysis and statistical testing.
The project demonstrates how data-driven insights can solve real-world business problems — such as identifying underperforming vendors, optimizing profit margins, and understanding sales distribution patterns.

🧠 Key Objectives

Ingest and store raw vendor data efficiently using Python and SQLAlchemy.

Explore data trends, correlations, and outliers through visual and statistical methods.

Compare top-performing vs. low-performing vendors using t-tests and other hypothesis tests.

Demonstrate how logs and structured pipelines improve traceability and reliability in data workflows.

⚙️ Technologies Used

Python
Pandas, NumPy
Database	SQLAlchemy, SQLite
Matplotlib, Seaborn
SciPy

📊 Business Problem

Many organizations manage multiple vendors, yet struggle to measure performance consistency and detect inefficiencies.
This project uses real vendor transaction data to answer key business questions:

Which vendors generate the highest profit margins?

Are high-revenue vendors also more profitable?

Do underperforming vendors share common characteristics?

🔍 Highlights
1. Data Ingestion with Logging

A robust pipeline (ingestion_db.ipynb) loads raw .csv files into a SQL database.

Each ingestion event is logged, enabling auditability and error tracing.

Example log entries include file names, ingestion times, and record counts.

2. Exploratory Data Analysis

Conducts descriptive statistics and visualizations of vendor and sales data.

Identifies trends, seasonal patterns, and outliers.

3. Vendor Performance Testing

Applies independent t-tests to compare profit margins between top and bottom revenue quartiles.

Evaluates whether differences are statistically significant, enabling data-backed vendor management decisions.

🧾 Logging

Logs are crucial for:

Tracking pipeline health

Debugging ingestion errors

Ensuring data integrity and reproducibility

🚀 How to Run

Clone this repository

git clone https://github.com/yourusername/vendor-performance-analysis.git
cd vendor-performance-analysis


Open and run the notebooks in the following order:

ingestion_db.ipynb

Exploratory Data Analysis.ipynb

Vendor Performance Analysis.ipynb

💡 Key Takeaways

Logs turn data pipelines into maintainable, production-ready systems.

Statistical testing converts raw numbers into actionable business intelligence.

Using real vendor data allows bridging the gap between technical insights and practical business outcomes.

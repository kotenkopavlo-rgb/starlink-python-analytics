# Starlink Python Analytics

Data analysis project based on Starlink customer and subscription data using Python and Pandas.

## Project Overview

This project analyzes customer and subscription data to identify patterns in customer behavior, subscription plans, revenue, and traffic usage.

The project is being developed progressively while learning Python, Pandas, statistics, and data analytics.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Git & GitHub

## Dataset

The project uses two datasets:

- `starlink_customers.csv` — customer information and traffic usage data
- `subscriptions.csv` — subscription plans and billing information

The datasets are connected through the customer ID.

## Analysis

The project currently includes the following analyses:

- **ST001** — High-Traffic Customers in Ukraine
- **ST002** — Top 10 Customers by Total Traffic
- **ST003** — Traffic by Country
- **ST004** — Country Traffic & Customer Analysis
- **ST005** — Country Revenue Analysis
- **ST006** — Plan Revenue by Country
- **ST007** — Subscription Plan Distribution
- **ST008** — Revenue per Customer by Plan
- **ST009** — Customer Distribution by Subscription Plan
- **ST010** — Revenue by Subscription Plan
- **ST011** — Revenue by Country
- **ST012** — Customer Activity by Country
- **ST013** — Upload Traffic by Country
- **ST014** — Customer Traffic by Subscription Plan
- **ST015** — Customer Count by Country
- **ST016** — Average Traffic by Subscription Plan
- **ST017** — Revenue per Customer by Country
- **ST018** — Subscription Plan Categorization
- **ST019** — Subscription Status Standardization
- **ST020** — Customer Plan Category
- **ST020** — Customer Download Usage Segmentation


Each analysis follows a consistent structure:

- Business Question
- Analysis
- Code
- Result
- Business Insight

## Project Structure

```text
starlink-python-analytics/
│
├── data/
│   ├── starlink_customers.csv
│   └── subscriptions.csv
│
├── notebooks/
│   ├── ST001_High-Traffic Customers in Ukraine.ipynb
│   ├── ST002_Top 10 Customers by total traffic.ipynb
│   ├── ...
│   └── ST017_Revenue per Customer by Country.ipynb
│
└── README.md

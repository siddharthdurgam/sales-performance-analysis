# Sales Performance Analysis

## Project Overview

An end-to-end e-commerce sales analytics project using Python and Power BI to analyze sales performance, customer and order patterns, product categories, geographical performance, and monthly sales trends.

The project combines data preparation and exploratory analysis in Python with an interactive Power BI dashboard to turn raw e-commerce data into practical business insights.

## Business Objectives

- Analyze monthly sales trends and identify significant changes in performance
- Identify top-performing product categories
- Understand geographical sales and order concentration
- Analyze customer and order patterns
- Build an interactive management dashboard in Power BI
- Translate analytical findings into actionable business recommendations

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI
- Excel

## Project Workflow

```text
Raw E-commerce Data
        ↓
Data Loading
        ↓
Data Cleaning & Transformation
        ↓
Feature Engineering
        ↓
Exploratory Data Analysis
        ↓
Business Insights
        ↓
Power BI Dashboard
        ↓
Actionable Recommendations
```

## Dashboard

### Executive Summary

The Executive Summary provides a management-level view of:

- Total Sales
- Total Customers
- Total Orders
- Average Order Value
- Monthly Sales Trend
- Sales by Product Category
- Year-level filtering

![Executive Summary](dashboard/executive_summary.png)

### Deep Dive Analysis

The Deep Dive Analysis focuses on:

- Geographical order distribution
- Top-performing product categories
- Regional concentration
- Category-level sales comparison

![Deep Dive Analysis](dashboard/deep_dive_analysis.png)

## Key Project Metrics

| KPI | Value |
|---|---:|
| Total Sales | **$20.31M** |
| Total Customers | **95.42K** |
| Total Orders | **98.67K** |
| Average Order Value | **$205.83** |

## Key Insights

### 1. Sales Performance

Monthly sales show strong performance through much of the period, followed by a significant decline in the later months and a temporary recovery in November. This pattern highlights the need to investigate demand changes, inventory availability, logistics, promotions, and other operational factors.

### 2. Product Category Performance

The strongest categories include:

- `bed_bath_table`
- `health_beauty`
- `computers_accessories`
- `furniture_decor`
- `watches_gifts`
- `sports_leisure`

### 3. Geographical Performance

Customer and order activity is strongly concentrated in Brazil's Southeast region. São Paulo (SP) is the leading state by order volume, followed by Rio de Janeiro (RJ) and Minas Gerais (MG).

This indicates strong existing demand in the core market while also highlighting opportunities to evaluate expansion into less-served regions.

## Business Recommendations

### Inventory Planning
Maintain adequate inventory for high-performing categories, particularly before expected peak sales periods.

### Marketing Strategy
Investigate significant sales declines and consider targeted promotional campaigns during weaker periods.

### Geographical Expansion
Continue strengthening the strongest markets while testing demand and logistics feasibility in under-served regions.

### Merchandising
Consider bundle offers that combine high-performing products with slower-moving products to improve inventory movement.

### Customer Value
Explore threshold-based promotions or shipping incentives to encourage larger baskets and improve average order value.

## Python Analysis

The Jupyter Notebook covers:

1. Loading the source datasets
2. Merging orders, items, products, customers, payments, and category translations
3. Initial data inspection
4. Date conversion
5. Missing-value handling
6. Time-based feature engineering
7. Exporting the cleaned dataset
8. Exploratory analysis of monthly sales
9. Product-category analysis
10. State-level order analysis

## Project Structure

```text
sales-performance-analysis/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   └── sales_data_analysis.ipynb
│
├── dashboard/
│   ├── executive_summary.png
│   └── deep_dive_analysis.png
│
├── reports/
│   ├── sales_data_analysis_report.pdf
│   └── project_report.pdf
│
└── data/
    └── README.md
```

## Dataset

The notebook is designed around the public Olist e-commerce dataset and references the following source files:

- `olist_orders_dataset.csv`
- `olist_order_items_dataset.csv`
- `olist_products_dataset.csv`
- `olist_customers_dataset.csv`
- `olist_order_payments_dataset.csv`
- `product_category_name_translation.csv`

The raw dataset is intentionally not included in this repository package. See `data/README.md` for the expected file names and setup notes.

## How to Run

1. Install Python 3.x.
2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Place the required source CSV files in the notebook's working directory.
4. Open:

```text
notebooks/sales_data_analysis.ipynb
```

5. Run the notebook cells in order.

## Author

**Siddharth Durgam**

Business Analyst | Data Analytics Enthusiast

LinkedIn: [Siddharth Durgam](https://www.linkedin.com/in/siddharth-durgam-878632263)

---

⭐ If you find this project useful, feel free to explore the analysis and dashboard.

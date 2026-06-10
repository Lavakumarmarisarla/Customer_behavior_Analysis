# Customer Shopping Behavior Analysis
## Overview

This project presents an end-to-end Data Analytics workflow using customer shopping behavior data. The objective was to analyze customer purchasing patterns, uncover business insights, and visualize key performance indicators through an interactive Power BI dashboard.

The project covers the complete analytics lifecycle, including data preprocessing, exploratory data analysis (EDA), SQL-based business analysis, dashboard development, reporting, and presentation.

## Dataset

#### Dataset: Customer Shopping Behavior Dataset

The dataset contains information related to:

- Customer demographics
- Age and gender
  Product categories
- Purchase amounts
- Review ratings
- Subscription status
- Discount usage
- Shipping preferences
- Payment methods
- Purchase frequency

## Tools & Technologies
#### Data Analysis
- Python
- Pandas
- NumPy
#### Data Visualization
- Power BI
#### Database
- MySQL

#### Documentation & Presentation
- Microsoft Word
- Gamma

## Project Workflow
#### 1. Data Loading
- Imported the customer shopping dataset into Python.
- Performed initial data inspection using Pandas.
#### 2. Data Cleaning
- Checked for missing values.
- Filled missing review ratings using category-wise median values.
- Standardized column names.
- Removed redundant columns.
- Created additional features such as:
- Age Group
- Purchase Frequency (Days)
#### 3. Exploratory Data Analysis (EDA)
- Analyzed customer demographics.
- Examined purchasing behavior across categories.
- Studied customer ratings and spending patterns.
- Identified trends and relationships within the data.
#### 4. SQL Analysis

The cleaned dataset was loaded into MySQL for business analysis.

SQL queries were written to answer key business questions such as:

- Top-selling product categories
- Customer spending patterns
- Discount utilization rates
- Purchase frequency analysis
- Revenue contribution by customer segments
- Product performance metrics
#### 5. Dashboard Development

An interactive Power BI dashboard was created to visualize:

- Total Sales
- Average Purchase Value
- Customer Segmentation
- Product Category Performance
- Discount Analysis
- Customer Purchase Trends
- Review Rating Insights
#### 6. Reporting & Presentation
Created a detailed project report documenting findings and methodology.
Developed a presentation summarizing business insights and recommendations.
Dashboard Highlights

The Power BI dashboard provides:

- Interactive filters and slicers
- Customer demographic analysis
- Category-wise sales performance
- Purchase behavior trends
- Discount impact analysis
- KPI cards for business monitoring
## Key Insights
- Identified the most frequently purchased product categories.
- Analyzed the impact of discounts on customer purchases.
- Evaluated customer spending behavior across different age groups.
- Explored relationships between review ratings and purchasing patterns.
- Generated actionable insights to support business decision-making.

## Project Files
Customer-Shopping-Behavior-Analysis/
│
├── customer_shopping_behavior.csv
├── Customer Shopping Analysis.ipynb
├── customer_behavior_SQL_queries.pdf
├── Customer Shopping Behaviour Dashboard.pbix
├── Customer Shopping Behavior Analysis Documentation.pdf
├── Customer-Shopping-Behavior-Analysis.pptx
└── README.md
## How to Run :
#### Clone the Repository
### Clone the Repository

```bash
git clone https://github.com/Lavakumarmarisarla/Customer_behavior_Analysis.git
cd Customer_behavior_Analysis
```

#### Install Dependencies
pip install pandas numpy matplotlib seaborn sqlalchemy pymysql
Run the Notebook
jupyter notebook

Open Customer Shopping Analysis.ipynb and execute all cells.

#### Execute SQL Queries
Create a MySQL database.
Import the cleaned dataset.
Run the SQL queries provided in the project files.
#### Open Dashboard
Open the Power BI dashboard file.
Refresh the data source if required.
Explore the interactive visualizations.



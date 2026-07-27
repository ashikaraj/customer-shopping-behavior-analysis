# customer-shopping-behavior-analysis
End-to-end data analytics project analyzing customer shopping behavior using Python, PostgreSQL, SQL, and Power BI. Includes data cleaning, feature engineering, business analysis, interactive dashboards, and actionable insights.

# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior using retail transaction data to uncover purchasing patterns, customer segments, product preferences, and revenue trends. The project follows an end-to-end data analytics workflow, from data preprocessing and exploratory analysis to SQL-based business insights and interactive dashboard creation.

The objective is to demonstrate how raw data can be transformed into meaningful business insights that support data-driven decision-making.

---

## Dataset

- **Dataset:** Customer Shopping Behavior Dataset
- **Records:** 3,900 customer purchases
- **Features:** 18 columns
- **Domain:** Retail / E-commerce

The dataset contains customer demographics, purchase details, shopping preferences, subscription information, discounts, shipping methods, product categories, and customer review ratings.

---

## Tools & Technologies

- **Python**
  - Pandas
  - NumPy
  - Jupyter Notebook
- **PostgreSQL**
- **SQL**
- **Power BI**
- **Gamma** (Presentation)
- **Git & GitHub**

---

## Project Workflow

### 1. Data Loading
- Imported the dataset into Python using Pandas.
- Performed an initial exploration to understand the dataset structure.

### 2. Exploratory Data Analysis (EDA)
- Examined dataset information and summary statistics.
- Identified missing values.
- Explored customer demographics and purchase patterns.

### 3. Data Cleaning & Feature Engineering
- Handled missing values.
- Standardized column names.
- Created new features such as:
  - `age_group`
  - `purchase_frequency_days`
- Verified data consistency.
- Prepared the cleaned dataset for SQL analysis.

### 4. PostgreSQL & SQL Analysis
- Loaded the cleaned dataset into PostgreSQL.
- Wrote SQL queries to answer key business questions, including:
  - Revenue by gender
  - High-spending discount users
  - Top-rated products
  - Shipping type comparison
  - Subscriber vs non-subscriber analysis
  - Discount dependency
  - Customer segmentation
  - Top-selling products by category
  - Repeat buyer analysis
  - Revenue by age group

### 5. Power BI Dashboard
Developed an interactive dashboard to visualize:

- Customer overview
- Revenue by category
- Revenue by age group
- Customer subscription distribution
- Sales by category
- Key business KPIs

### 6. Reporting & Presentation
- Documented the complete analysis in a project report.
- Created a presentation using **Gamma** to communicate insights and business recommendations.

---

## Dashboard
<img width="765" height="412" alt="image" src="https://github.com/user-attachments/assets/4565667b-4f73-45ad-86b9-eb497810bb36" />

The Power BI dashboard provides an interactive view of customer purchasing behavior and business performance through charts, KPIs, and filters.

**Key Metrics**
- Total Customers
- Average Purchase Amount
- Average Review Rating

**Visualizations**
- Revenue by Category
- Revenue by Age Group
- Subscription Distribution
- Sales by Category
- Interactive Filters

---

## Key Results

The analysis identified several valuable business insights:

- Male customers generated higher overall revenue.
- Young Adults contributed the highest revenue.
- Express shipping customers spent slightly more on average.
- Several repeat buyers were not subscribed.
- High-rated products can be prioritized for promotions.
- Customer segmentation highlighted opportunities for loyalty programs.

---

## Repository Structure

```
customer-shopping-behavior-analysis/
│
├── data/
├── notebooks/
├── sql/
├── dashboard/
├── report/
├── images/
├── README.md
└── LICENSE
```

---

## How to Run

1. Clone this repository.

```bash
git clone https://github.com/yourusername/customer-shopping-behavior-analysis.git
```

2. Install the required Python libraries.

```bash
pip install pandas numpy jupyter
```

3. Open the Jupyter Notebook.

4. Run the notebook to:
   - Load the dataset
   - Perform EDA
   - Clean the data
   - Create new features

5. Import the cleaned dataset into PostgreSQL.

6. Execute the SQL queries located in the `sql/` folder.

7. Open the Power BI dashboard (`.pbix`) to explore the visualizations.

---

## Business Value

This project demonstrates an end-to-end data analytics workflow by combining Python, PostgreSQL, SQL, and Power BI to transform raw retail data into actionable business insights. It highlights practical skills in data cleaning, exploratory analysis, SQL querying, dashboard development, and business reporting.

---

## Author

**Ashika Raj**

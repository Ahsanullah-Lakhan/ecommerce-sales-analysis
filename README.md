
# E-Commerce Sales and Profit Analysis

## Project Overview

This project analyzes retail sales data to understand business performance, profitability, customer behavior, and sales trends.

The project uses Python and data analysis libraries to transform raw retail data into meaningful business insights and actionable recommendations.

The main objective is to help a business make better decisions using data.

## Business Objectives

- Analyze overall sales and profit performance
- Identify the most profitable product categories
- Compare sales and profitability across regions
- Understand customer segment performance
- Identify top-selling products and customers
- Analyze monthly sales trends
- Investigate the relationship between discounts and profit
- Identify products generating negative profit
- Provide data-driven business recommendations

## Dataset

**Dataset:** Superstore Sales Dataset

**Source:** [Kaggle - Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

The dataset contains retail transaction information, including:

- Order details
- Customer information
- Product categories and sub-categories
- Sales and profit
- Quantity
- Discount
- Region
- Order and shipping dates

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

## Project Workflow

### 1. Data Loading

Imported the retail sales dataset into a Pandas DataFrame using `pd.read_csv()`.

### 2. Data Inspection

Examined the dataset using:

- `shape`
- `columns`
- `info()`
- `describe()`
- `isnull().sum()`
- `duplicated().sum()`

### 3. Data Cleaning

Performed the following data preparation tasks:

- Removed duplicate records
- Standardized column names
- Converted date columns into datetime format
- Converted numerical columns into appropriate data types
- Handled missing values in essential analysis columns

### 4. Feature Engineering

Created additional analytical features:

- Profit Margin
- Order Month
- Order Year

Profit margin was calculated using:

Profit Margin = (Profit / Sales) × 100

### 5. Exploratory Data Analysis

Conducted analysis to understand:

- Sales and profit by category
- Sales and profit by sub-category
- Regional sales performance
- Customer segment performance
- Top 10 products by sales
- Top 10 customers by sales
- Monthly sales trends
- Discount and profit relationship
- Products with negative profit

### 6. Data Visualization

Created visualizations using Matplotlib and Seaborn, including:

- Category sales bar charts
- Top product sales charts
- Monthly sales trend charts
- Correlation heatmap

### 7. Business Insights

Generated key business performance indicators:

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Total Quantity Sold
- Overall Profit Margin

## Key Findings

The analysis identifies:

- The highest-selling product category
- The most profitable product category
- The strongest-performing region
- The customer segment contributing the most sales
- Products generating negative profit
- Monthly sales patterns
- Potential relationships between discounts and profitability

Actual findings and numerical results should be added here after reviewing the notebook outputs.

## Business Recommendations

Based on the analysis, businesses can:

- Focus marketing efforts on high-performing product categories
- Identify opportunities in strong-performing regions
- Develop customer retention strategies
- Review pricing and discount policies
- Investigate products generating negative profit
- Use monthly sales trends for inventory and business planning

## Project Files

```text
ecommerce-sales-analysis/
│
├── ecommerce_sales_analysis.ipynb
├── cleaned_superstore_data.csv
├── category_analysis.csv
├── region_analysis.csv
├── top_customers.csv
├── subcategory_analysis.csv
└── README.md
```

## Conclusion

This project demonstrates the use of Python for business-oriented data analysis.

It covers the complete analytical workflow, from loading and cleaning data to exploratory analysis, visualization, and business recommendations.

The project combines business understanding with technical data analysis skills to support data-driven decision-making.

## Author

Ahsanullah Lakhan

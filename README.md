# Diwali-Sales-Analysis
A Python-based Diwali Sales Analysis project that performs data cleaning, exploratory data analysis, and visualization to identify customer behavior and business insights using Pandas, Matplotlib, and Seaborn

# Diwali Sales Analysis

## Overview

This project performs Exploratory Data Analysis (EDA) on a Diwali Sales dataset using Python. The objective is to analyze customer purchasing behavior during the Diwali festival and identify key sales trends based on demographic and product-related attributes.

The analysis includes data cleaning, preprocessing, visualization, and business insights that can help organizations understand customer preferences and improve marketing strategies.

---

## Objectives

- Clean and preprocess the dataset.
- Analyze customer purchasing behavior.
- Identify high-value customer segments.
- Discover top-performing product categories.
- Analyze sales across different states and occupations.
- Generate business insights using data visualization.

---

## Dataset Information

The dataset contains customer purchase records collected during the Diwali shopping season.

### Dataset Size

- Rows: 11,251
- Columns: 15

### Features

- User_ID
- Cust_name
- Product_ID
- Gender
- Age Group
- Age
- Marital_Status
- State
- Zone
- Occupation
- Product_Category
- Orders
- Amount
- Status
- unnamed1

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Collection

- Imported the Diwali Sales dataset into a Pandas DataFrame.

### 2. Data Cleaning

The following preprocessing steps were performed:

- Removed unnecessary columns:
  - Status
  - unnamed1
- Checked for missing values.
- Removed null records.
- Converted the Amount column into integer data type.
- Renamed columns where required.

### 3. Exploratory Data Analysis

The notebook explores customer purchasing behavior using various visualizations and statistical summaries.

Analysis includes:

- Gender-wise customer distribution
- Gender-wise total sales
- Age Group analysis
- Sales by Age Group
- Top 10 States based on Orders
- Top 10 States based on Sales Amount
- Marital Status distribution
- Marital Status vs Sales
- Occupation-wise customer distribution
- Occupation-wise sales analysis
- Product Category distribution
- Product Category-wise sales
- Top 10 Most Sold Products

---

## Data Visualization

The project includes the following visualizations:

- Count Plot
- Bar Plot
- Sales Comparison Charts
- Category-wise Analysis
- State-wise Sales Analysis
- Customer Demographic Analysis

All visualizations are created using Matplotlib and Seaborn.

---

## Key Insights

The analysis reveals several customer purchasing trends, including:

- Female customers contributed more to total sales than male customers.
- Customers in the 26–35 age group made the highest number of purchases.
- Married customers showed higher purchasing activity.
- Certain states generated significantly higher sales than others.
- Customers working in IT, Healthcare, and Aviation were among the highest contributors to revenue.
- Food, Clothing, and Electronics-related categories were among the top-selling product categories.
- A small number of products accounted for a large share of total orders.

---

## Skills Demonstrated

This project demonstrates practical knowledge of:

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Analysis
- Customer Segmentation
- Business Insight Generation
- Python Programming
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Project Structure

```
Diwali-Sales-Analysis/
│
├── Diwali_sales_analysis.ipynb
├── Diwali Sales Data.csv
└── README.md
```

---

## How to Run

1. Clone this repository.
2. Install the required Python libraries.
3. Open the notebook in Jupyter Notebook or Google Colab.
4. Run all cells to reproduce the analysis.

### Required Libraries

```
pandas
numpy
matplotlib
seaborn
```

---

## Future Improvements

- Build an interactive dashboard using Power BI or Tableau.
- Develop a sales prediction model using Machine Learning.
- Create customer segmentation using clustering algorithms.
- Deploy the analysis as a web application using Streamlit.

---

## Author

**Nandani Rajput**

B.Tech Computer Science Engineering

GLS University

# Global Superstore – Data Analytics Project

## 📌 Project Overview

This project focuses on analyzing the Global Superstore dataset to identify business trends, evaluate sales and profitability, and generate meaningful business insights using Python and data analytics techniques.

The project covers data inspection, data cleaning, exploratory data analysis, pivot table creation, data visualization, and business recommendations.

## 🎯 Project Objectives

- Understand and inspect the Global Superstore dataset.
- Identify and handle data quality issues.
- Perform data cleaning and preprocessing.
- Create pivot tables for business analysis.
- Visualize sales, profit, and customer segment performance.
- Generate actionable business insights.

## 📂 Dataset Information

**Dataset:** Global Superstore Dataset

**Source:** [Kaggle – Global Superstore Dataset](https://www.kaggle.com/datasets/apoorvaappz/global-super-store-dataset)

- Total Records: 51,290
- Total Columns: 24
- File Format: CSV

### Key Features

- Order ID
- Order Date
- Ship Date
- Ship Mode
- Customer Name
- Segment
- City
- State
- Country
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit
- Shipping Cost

## 🛠️ Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Microsoft Excel
- GitHub

## ⚙️ Project Workflow

### 1. Data Inspection
- Loaded the dataset using Pandas.
- Checked dataset dimensions and column names.
- Examined the first five records.
- Analyzed data types and missing values.

### 2. Data Cleaning
- Checked missing values.
- Identified and removed duplicate records.
- Cleaned text columns.
- Converted date columns into datetime format.
- Checked numeric data types.
- Preserved missing postal codes where appropriate.

### 3. Pivot Table Analysis

Created four pivot tables:

- Category-wise Sales and Profit
- Region-wise Sales Analysis
- Customer Segment Analysis
- Sub-Category Performance

### 4. Data Visualization

Created four charts:

1. Sales by Product Category
2. Profit by Region
3. Monthly Sales Trend
4. Sales Distribution by Customer Segment

### 5. Business Insights

Analyzed overall sales, profit, orders, product categories, regional performance, and customer segments.

## 📊 Key Business Findings

| Metric | Result |
|---|---:|
| Total Sales | $12,642,501.91 |
| Total Profit | $1,467,457.29 |
| Total Orders | 25,035 |
| Total Quantity | 178,312 |
| Top Sales Category | Technology |
| Top Profit Region | Central |
| Top Customer Segment | Consumer |
| Lowest Profit Sub-Category | Tables |

## 💡 Business Recommendations

- Focus on Technology products to improve sales.
- Study the successful strategies of the Central region.
- Review pricing and discount strategies for loss-making products.
- Focus on the Consumer segment.
- Improve customer location data quality.

## 📁 Project Structure

```text
Mission1-Global-Superstore-Data-Analysis/
│
├── Charts/
│   ├── 1_Sales_by_Category.png
│   ├── 2_Profit_by_Region.png
│   ├── 3_Monthly_Sales_Trend.png
│   └── 4_Segment_Sales.png
│
├── Business_Insights.txt
├── Global_Superstore_Pivot_Tables.xlsx
├── mission1.ipynb
└── README.md
```

## 🚀 How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/ReyanReza3126/Mission1-Global-Superstore-Data-Analysis.git
```

2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

3. Download the dataset from Kaggle and place it in the appropriate project directory.

4. Open `mission1.ipynb` in Jupyter Notebook or VS Code.

5. Run the notebook cells sequentially.

## 👨‍💻 Author

**Reyan Reza**

B.Tech – Computer Science and Engineering (Machine Learning)

Gautam Buddha University

GitHub: [ReyanReza3126](https://github.com/ReyanReza3126)

## 📌 Project Status

Completed – Data Analytics Mission 1

---

*This project was completed as part of a Data Analytics internship learning program.*

# Task 5: Sales Data Analysis

## Problem Statement

Analyze business sales data to identify trends, top-performing products, category-wise performance, regional sales distribution, and state-wise contributions. The objective is to derive meaningful business insights that can support data-driven decision-making and improve overall business performance.

---

## Dataset Details

### Dataset Name
Superstore Sales Dataset (`train.csv`)

### Description
The dataset contains sales transaction records, including order details, product information, categories, regions, states, and sales values. It is used to analyze business performance and identify key sales trends.

### Features
- Order Date
- Product Name
- Category
- Region
- State
- Sales
- Other order-related attributes

---

## Approach

### 1. Data Loading
- Imported the dataset using Pandas.
- Loaded the sales data into a DataFrame.

### 2. Data Understanding
- Examined dataset structure using `df.info()`.
- Reviewed data types and available features.

### 3. Summary Statistics
- Generated descriptive statistics for the Sales column.
- Analyzed measures such as mean, minimum, maximum, and standard deviation.

### 4. Monthly Sales Trend Analysis
- Converted Order Date to datetime format.
- Grouped sales by month.
- Visualized monthly sales trends using a line chart.

### 5. Top 10 Selling Products
- Aggregated sales by Product Name.
- Identified the top 10 products with the highest sales.
- Visualized results using a bar chart.

### 6. Sales by Category
- Grouped sales data by product category.
- Compared category-wise sales performance using a bar chart.

### 7. Sales by Region
- Analyzed total sales across different regions.
- Visualized regional performance using a bar chart.

### 8. Top 10 States by Sales
- Calculated total sales for each state.
- Identified the top 10 states contributing the highest sales.
- Displayed results using a bar chart.

### 9. Correlation Analysis
- Selected numerical features from the dataset.
- Computed the correlation matrix.
- Visualized relationships using a heatmap.

---

## Results

### Monthly Sales Trend
- Identified sales growth patterns over time.
- Highlighted peak and low-performing sales periods.

### Top Selling Products
- Determined the products generating the highest revenue.
- Identified key contributors to overall sales.

### Category Analysis
- Compared sales performance across product categories.
- Revealed the most profitable categories.

### Regional Analysis
- Evaluated sales performance across regions.
- Identified the strongest business markets.

### State-wise Analysis
- Determined the states contributing the highest sales.
- Highlighted major revenue-generating locations.

### Correlation Analysis
- Examined relationships among numerical variables.
- Provided insights into factors influencing sales performance.

---

## Tools & Libraries Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

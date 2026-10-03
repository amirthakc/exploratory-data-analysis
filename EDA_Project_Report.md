# EXPLORATORY DATA ANALYSIS (EDA) PROJECT

## 1. Project Title
**E-Commerce Sales Exploratory Data Analysis**

## 2. Objective
The main objective is to analyze a sales dataset, understand its structure, identify patterns and trends, study correlations, and present the findings using visualizations.

## 3. Dataset
No dataset was supplied with the Thiranex task. Therefore, a synthetic e-commerce dataset was generated containing **500 original orders**. The raw dataset also contains deliberate missing values, duplicate rows and extreme values so the EDA workflow includes realistic data-cleaning steps.

### Main columns
- Order ID
- Order Date
- Category
- Product
- Quantity
- Unit Price
- Discount
- City
- Sales Channel
- Payment Method
- Revenue
- Customer Rating

## 4. Data Cleaning
The following operations were performed:
1. Removed duplicate records.
2. Converted Order Date into datetime format.
3. Filled missing City values using the mode.
4. Filled missing Customer Rating values using the median.
5. Detected extreme Quantity and Unit Price values using the IQR method.
6. Limited extreme values to reasonable IQR boundaries.
7. Recalculated Revenue after cleaning.

## 5. Statistical Analysis
- Total Revenue: **₹2,620,376.67**
- Average Revenue per Order: **₹5,240.75**
- Highest Revenue Category: **Electronics**
- Highest Revenue City: **Salem**
- Highest Revenue Sales Channel: **Website**
- Correlation between Quantity and Revenue: **0.550**

## 6. Visualizations
The project includes:
1. Revenue by Product Category
2. Revenue by City
3. Monthly Revenue Trend
4. Revenue Distribution
5. Quantity vs Revenue Scatter Plot
6. Payment Method Distribution
7. Correlation Matrix

## 7. Key Findings
### Category
The category-level analysis identifies **Electronics** as the highest-revenue category in this generated dataset.

### Location
**Salem** has the highest total revenue among the cities in the dataset.

### Sales Channel
The **Website** channel has the highest total revenue in the generated data.

### Time Trend
Monthly revenue analysis helps identify periods of relatively higher and lower sales and can support future sales planning.

### Correlation
Quantity and Revenue have a correlation of approximately **0.550**. Correlation indicates association, not causation.

### Payment Method
The payment-method chart shows the distribution of UPI, Card, Cash and Net Banking usage.

## 8. Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## 9. Conclusion
This project demonstrates how Exploratory Data Analysis can turn raw sales data into useful information. Statistical summaries provide numerical understanding, while charts reveal patterns and trends that may be difficult to see in a table.

The workflow can be extended with dashboards, hypothesis testing and machine-learning models.

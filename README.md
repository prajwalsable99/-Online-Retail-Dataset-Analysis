# Online Retail Dataset Analysis

## Project Overview
This project analyzes the Online Retail Dataset, which contains transactional data for a UK-based online retailer. The analysis involves various stages, including data cleaning, exploratory data analysis (EDA), forecasting, segmentation, and visualization. Each step provides insights into customer behavior, product performance, and sales trends.

---

## Dataset Overview

**Source:**  
The dataset used in this project is the Online Retail Dataset, available from the UCI Machine Learning Repository. It contains detailed transactional data for an online retailer, including:

- Product details  
- Purchase quantities  
- Prices  
- Customer demographics

**Dataset Link:** [UCI Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail)

### Columns:
- **InvoiceNo**: Unique identifier for each transaction.
- **StockCode**: Unique identifier for each product.
- **Description**: Name or description of the product.
- **Quantity**: Number of items purchased.
- **InvoiceDate**: Date and time of purchase.
- **UnitPrice**: Price per unit of the product.
- **CustomerID**: Unique identifier for each customer.
- **Country**: Country where the customer is located.

---

## Key Steps

### 1. Importing Necessary Libraries
All essential Python libraries for data manipulation, visualization, and modeling are imported. This includes pandas, numpy, matplotlib, seaborn, plotly, and others.

### 2. Loading and Cleaning the Dataset
The dataset is loaded and cleaned to handle:
- Missing values in critical columns (e.g., CustomerID, Description).
- Invalid entries (e.g., Quantity or UnitPrice values of 0 or less).
- Removal of duplicates.

### 3. Exploratory Data Analysis (EDA)
Performed to uncover insights such as:
- Total sales trends over time.
- Best-selling products.
- Customer purchase patterns.

### 4. Forecasting Revenue
Revenue forecasting is conducted using statistical models such as ARIMA and SARIMA. Forecasts are generated for the next six months based on historical sales data.

### 5. Demand Segmentation
Products are categorized into demand profiles using criteria such as:
- Smooth demand (consistent over time).
- Intermittent demand (low quantity but regular intervals).
- Erratic demand (high quantity variation).
- Lumpy demand (irregular and unpredictable).

### 6. Inventory Optimization
Economic Order Quantity (EOQ) is calculated to optimize inventory levels by minimizing holding and ordering costs.

### 7. Geographical Mapping
Sales data is visualized geographically using latitude and longitude for each country. Tools such as Plotly are used to create scatter plots on a world map, showcasing:
- Total sales per country.
- Key geographic trends.

### 8. RFM Analysis
Customers are segmented based on Recency, Frequency, and Monetary (RFM) metrics:
- **Recency**: How recently a customer made a purchase.
- **Frequency**: How often they purchase.
- **Monetary**: Total spending.

### 9. Price Elasticity Analysis
Examines the relationship between price changes and demand, helping identify how price adjustments impact sales.

---

## Technologies Used

**Python**: For data manipulation, analysis, and visualization.  
**Libraries:**  
- `pandas`, `numpy`: Data manipulation.  
- `matplotlib`, `seaborn`, `plotly`: Visualization.  
- `statsmodels`: Forecasting.  
- `plotly` (optional): Geographic data handling.

---

## Results
The analysis provided actionable insights, including:
- Key regions driving sales.
- Products requiring better inventory planning.
- Customer segmentation for targeted marketing strategies.
- Revenue projections to aid business decisions.
![image](https://github.com/user-attachments/assets/c3728e35-a434-47fd-accb-96f9798d73c2)

---

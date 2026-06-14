# Amazon Seller Performance & Customer Analytics Dashboard

## Project Overview

This project analyzes Amazon sales data using SQL and Power BI to generate actionable business insights related to sales performance, customer behavior, product performance, seller contribution, and operational efficiency.

The objective is to transform raw transactional data into an interactive business intelligence dashboard that supports data-driven decision-making.

---

## Tools & Technologies

* Power BI
* MySQL
* DAX
* SQL
* CSV Dataset

---

## Dataset Information

The dataset contains:

* Order Information
* Customer Details
* Product Details
* Seller Information
* Revenue Metrics
* Payment Methods
* Shipping Costs
* Geographic Data

### Key Columns

* OrderID
* OrderDate
* CustomerID
* CustomerName
* ProductID
* ProductName
* Category
* Brand
* Quantity
* UnitPrice
* Discount
* Tax
* ShippingCost
* TotalAmount
* PaymentMethod
* OrderStatus
* City
* State
* Country
* SellerID

---

# Dashboard Pages

---

# Page 1: Executive Dashboard

### Objective

Provide a high-level overview of business performance.

### KPIs

* Total Revenue
* Total Orders
* Total Customers
* Quantity Sold

### Visualizations

* Monthly Revenue Trend (Line Chart)
* Revenue by Category
* Revenue by Country
* Interactive Filters

### Business Insights

* Overall business growth trend
* Best-performing categories
* Top revenue-generating regions
* Sales performance overview

---

# Page 2: Product Analytics

### Objective

Analyze product and brand performance.

### KPIs

* Product Revenue
* Products Sold
* Average Product Price
* Total Brands

### Visualizations

* Top 10 Products by Revenue
* Revenue by Brand
* Revenue by Category
* Product Performance Matrix

### Business Insights

* Highest-performing products
* Brand contribution to sales
* Category-wise revenue distribution
* Product-level performance analysis

---

# Page 3: Customer Analytics

### Objective

Understand customer behavior and customer value.

### KPIs

* Total Customers
* Customer Revenue
* Average Customer Value
* Top Customer Revenue

### Visualizations

* Top Customers Analysis
* Revenue by State
* Customer Segment Distribution
* Customer Ranking Table
* Customer Revenue vs Quantity Analysis

### Business Insights

* Identification of high-value customers
* Geographic concentration of customers
* Customer purchasing behavior
* Customer segmentation analysis

---

# Page 4: Seller Performance Dashboard

### Objective

Evaluate seller performance and revenue contribution.

### KPIs

* Total Sellers
* Seller Revenue
* Average Revenue per Seller
* Top Seller Revenue

### Visualizations

* Top Sellers by Revenue
* Seller Revenue Contribution (Pie Chart)
* Seller Revenue Trend
* Seller Performance Matrix

### Business Insights

* Top-performing sellers
* Revenue contribution by seller
* Seller growth trends
* Revenue concentration among sellers

---

# Page 5: Operations Dashboard

### Objective

Monitor operational efficiency and transaction performance.

### KPIs

* Total Orders
* Total Shipping Cost
* Average Shipping Cost
* Completed Orders

### Visualizations

* Payment Method Analysis (Pie Chart)
* Order Status Analysis (Pie Chart)
* Shipping Cost Analysis
* Monthly Operational Trend
* Payment Method Funnel Analysis

### Business Insights

* Most preferred payment methods
* Order completion and cancellation rates
* Shipping cost distribution
* Operational performance trends

---

# SQL Analysis Performed

### Data Cleaning

* Date Conversion
* Null Value Checks
* Data Validation

### Business Queries

* Total Revenue Analysis
* Monthly Revenue Trend
* Category Performance
* Product Performance
* Customer Ranking
* Seller Ranking
* Payment Method Analysis
* Geographic Analysis

---

# Key DAX Measures

### Revenue

Total Revenue = SUM(TotalAmount)

### Orders

Total Orders = DISTINCTCOUNT(OrderID)

### Customers

Total Customers = DISTINCTCOUNT(CustomerID)

### Quantity Sold

Quantity Sold = SUM(Quantity)

### Average Order Value

Average Order Value = DIVIDE([Total Revenue],[Total Orders])

---

# Project Outcomes

* Built an end-to-end Business Intelligence solution.
* Performed SQL-based data preparation and analysis.
* Developed interactive Power BI dashboards.
* Generated actionable business insights from Amazon sales data.
* Applied data modeling, DAX calculations, and visualization best practices.

---

# Future Enhancements

* Customer Lifetime Value Analysis
* Profitability Analysis
* Sales Forecasting
* Inventory Analytics
* Advanced Customer Segmentation

---



# Screenshots
https://github.com/Tejinder2207/Amazon-Seller-Performance-and-Customer-Analytics-Dashboard/blob/main/Executive%20Dashboard.png
https://github.com/Tejinder2207/Amazon-Seller-Performance-and-Customer-Analytics-Dashboard/blob/main/Product%20Analytics.png
https://github.com/Tejinder2207/Amazon-Seller-Performance-and-Customer-Analytics-Dashboard/blob/main/Customer%20Analytics.png



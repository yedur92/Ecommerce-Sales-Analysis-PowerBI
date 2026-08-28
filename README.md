# E-Commerce Sales Analysis – Power BI

An interactive Power BI dashboard developed to analyse e-commerce sales performance, profitability, customer behaviour, product ratings, geographical performance and shipping trends.

## Project Overview

This project uses Microsoft Power BI to transform e-commerce sales data into an interactive analytical dashboard.

The report provides both high-level business insights and detailed transaction-level analysis through multiple dashboard pages, interactive filters and bookmarks.

## Dashboard Pages

### 1. Home

The Home page provides an overall summary of e-commerce performance.

**KPIs**
- Total Orders
- Overall Profit Margin
- Products Sold
- Total Sales
- Total Profit

**Visualisations**
- **Sales by Category** – Compares sales across product categories.
- **Sales & Profit Margin** – Shows sales and profit margin trends over time.
- **Sales by Region** – Shows the contribution of each region to total sales.
- **Top 5 Products by Sales** – Identifies the five highest-selling products.

**Filters**
- Product Category
- Location
- Date

### Bookmarks

Three interactive bookmarks provide quick access to different sales views.

| Highest Sales | Lowest Sales | All Sales |
|:---:|:---:|:---:|
| ![Highest Sales](assets/highest-sales.png) | ![Lowest Sales](assets/lowest-sales.png) | ![All Sales](assets/all-sales.png) |
| Displays the high-performing sales view. | Displays the low-performing sales view. | Returns to the overall sales view. |

### 2. Sales & Profit Analysis

This page focuses on revenue and profitability.

**KPIs**
- Total Orders
- Overall Profit Margin
- Products Sold
- Total Sales
- Total Profit

**Visualisations**
- **Profit Distribution by Category**
- **Profit vs Target**
- **Sales vs Profit Margin**
- **Top 10 Products by Profit**

**Filters**
- Product Category
- Location
- Date

### 3. Customer Analysis

This page analyses customer demographics and purchasing behaviour.

**KPIs**
- Total Customers
- Average Sales per Customer
- Average Products per Customer
- Average Profit per Customer

**Visualisations**
- **Customers Age Distribution**
- **Sales & Profit Trend by Age**
- **Quantity by Age & Gender**
- **Sales by Payment Method**

**Filters**
- Gender
- Age
- Date

### 4. Ratings & Sales Analysis

This page examines the relationship between ratings and sales performance.

**KPIs**
- Total Orders
- Total Customers
- Average Rating
- Category Count
- Products Count

**Visualisations**
- **Rating Distribution**
- **Avg Rating by Category**
- **Profit Distribution by Rating**
- **Avg Order Value by Rating**

**Filters**
- Date
- Product Category
- Rating

### 5. Shipping & Sales Analysis

This page focuses on geographical sales performance and order fulfilment.

**KPIs**
- Total Shipping Cost
- Total Sales
- Total Cities
- Average Sales per City
- Average Orders per City

**Visualisations**
- **Regional Sales and Profit**
- **Sales by City**
- **Orders by Status**
- **Top 10 Cities by Sales**

**Filters**
- Order Status
- Date
- Location

### 6. Sales Details

The Sales Details page provides a detailed, filterable view of individual sales records.

**Fields include**
- Customer Name
- Gender
- Age
- Order ID
- Customer ID
- Product Category
- Product
- Quantity
- Sales Amount
- Profit
- Discount %
- Profit Margin
- Payment Method
- Rating Category
- Order Status
- Days to Ship
- Total Shipping Cost

**Filters**
- Product Category
- Location
- Date
- Gender
- Age
- Rating
- Order Status

## Interactivity

The dashboard includes:

- Interactive slicers
- Bookmark-based sales views
- Page navigation
- Interactive visual cross-filtering
- Detailed sales-level analysis

## Tools Used

- Microsoft Power BI
- Power Query
- DAX
- Data Visualisation

## Project Files

| File | Description |
|---|---|
| `Ecommerce Sales Analysis.pbix` | Power BI dashboard |
| `README.md` | Project documentation |

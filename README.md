# Target Brazil E-commerce — SQL Analysis

## 📌 Project Overview

This project was completed as part of a Scaler Data Analytics case study.

The analysis uses Brazilian e-commerce data from 2016 to 2018 to understand customer behavior, order trends, payment patterns, revenue, freight costs, and delivery performance.

The dataset contains more than 100,000 orders across multiple tables, including customers, orders, payments, and order items.

## 🎯 Business Objective

The objective of this analysis is to use SQL to identify:

- Order growth and seasonal trends
- Customer distribution across Brazilian states
- Revenue and payment patterns
- Freight cost differences across regions
- Delivery performance
- Payment behavior and installment patterns
- Potential operational bottlenecks and business opportunities

## 🗂️ Dataset

The analysis covers e-commerce activity from 2016 to 2018.

Key tables used:

- `orders`
- `customers`
- `payments`
- `order_items`

## 🛠️ Tools & Technologies

- SQL
- Google BigQuery
- CTEs
- JOINs
- Subqueries
- Window Functions
- Aggregate Functions
- Date & Time Functions
- CASE Statements

## 🔍 Analysis Performed

### 1. Basic Exploration

- Examined table structure and column data types
- Identified the order date range
- Analyzed customer locations

### 2. Order Trends

- Year-over-year order growth
- Monthly order patterns
- Order activity by time of day

### 3. E-commerce Evolution

- Month-on-month order trends by state
- Customer distribution across states

### 4. Economic Impact

- Payment value trends
- Total and average payment value by state
- Freight cost analysis by state

### 5. Delivery Performance

- Delivery time analysis
- Estimated versus actual delivery dates
- State-level delivery performance

### 6. Payment Analysis

- Month-on-month orders by payment type
- Orders by number of payment installments

## 📊 Key Insights

- Order volume showed year-over-year growth from 2016 to 2018.
- Peak order activity occurred around June to September.
- Most orders were placed during the afternoon.
- São Paulo contributed significantly to overall revenue.
- Remote states showed higher freight costs and longer delivery times.
- Customers frequently used installment-based payments.

## 💡 Business Recommendations

Based on the analysis:

- Improve logistics operations in regions with higher delivery times.
- Explore opportunities to improve performance in underperforming states.
- Optimize freight and delivery routes to reduce logistics costs.
- Continue supporting flexible payment options such as installments.

## 📁 Project Structure

```text
target-brazil-ecommerce-sql-analysis/
│
├── README.md
│
├── sql/
│   ├── basic_exploration.sql
│   ├── order_trends.sql
│   ├── ecommerce_evolution.sql
│   ├── economic_impact.sql
│   ├── delivery_performance.sql
│   └── payment_analysis.sql
│
└── screenshots/
    └── analysis_results/

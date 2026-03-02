E-Commerce Supply Chain Optimization & Demand Forecasting

Tech Stack: Python | Google Colab | Power BI | Time Series Forecasting | Pandas | NumPy | Matplotlib | Statsmodels

**Project Overview:**
This project focuses on building an end-to-end supply chain analytics and demand forecasting system using multi-table e-commerce data (100K+ orders).

**The objective was to:**

1. Analyze demand patterns and supply chain risks
2. Forecast product demand using time-series models
3. Optimize inventory levels using classical inventory management techniques
4. Create an interactive Power BI dashboard for business insights

**Business Problem**

1. E-commerce companies face challenges such as:
2. Stockouts due to inaccurate demand forecasting
3.Excess inventory increasing holding costs
4. Regional delivery delays affecting customer satisfaction
5. Poor visibility into category-level demand trends
6. This project addresses these challenges through data-driven forecasting and inventory optimization.

**Dataset**
100,000+ e-commerce orders
Multiple relational tables (Orders, Customers, Products, Categories, Regions, Shipments)
Cleaned, merged, and transformed into a unified analytical dataset

**Exploratory Data Analysis (EDA)**

**Performed in Python (Google Colab):**

Monthly & weekly demand trend analysis
Seasonal pattern identification
Category concentration analysis (Top revenue contributors)
Regional delivery performance & delay risk analysis
High-volume product identification

**Key Insights:**
Clear seasonal spikes during festive periods
20% of products contributing to majority of sales (Pareto effect)
Certain regions showed consistent delivery delays

**Demand Forecasting Models**

Implemented Time Series Forecasting models:
Moving Average
Simple Exponential Smoothing

**Model Evaluation Metrics:**

MAE (Mean Absolute Error)
RMSE (Root Mean Square Error)
MAPE (Mean Absolute Percentage Error)
The best-performing model was selected based on minimum forecasting error.

**Inventory Optimization**
**Applied classical inventory control models to 20 high-volume products:**

EOQ (Economic Order Quantity)
Safety Stock Calculation
Reorder Point (ROP)
Formula Logic Used:
EOQ = √(2DS / H)
Safety Stock = Z × σ × √L
Reorder Point = (Average Demand × Lead Time) + Safety Stock

Where:
D = Demand
S = Ordering Cost
H = Holding Cost
L = Lead Time

Result:

Reduced stockout risk
Improved inventory turnover
Optimized reorder decisions

**Power BI Dashboard**
Built an interactive dashboard including:
Sales Trend Analysis
Category-wise Revenue
Region-wise Performance
Inventory Risk Indicators
Forecast vs Actual Comparison

The dashboard enables business users to make informed supply chain decisions.

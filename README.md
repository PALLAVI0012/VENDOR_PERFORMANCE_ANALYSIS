Vendor Performance Analysis Project
Overview
----------------------------check whole project here ---------------------------

https://drive.google.com/file/d/1UHhxFAmav5mxCWWCL6rukhEjw6HNgxL0/view?usp=sharing
-----------------------------------------------------------------------------------
Effective inventory and sales management is key to maximizing profitability in the retail and wholesale sectors. This project analyzes vendor performance, identifies profitability trends, and provides actionable insights to optimize sales, reduce inventory costs, and improve operational efficiency.

The analysis demonstrates how data-driven decision-making can support strategic vendor management, pricing adjustments, and stock optimization.

Key Features

Segmentation of vendors into 
top-performing and low-performing based on sales data.

Profit margin analysis including mean values and 95% confidence intervals.

Identification of slow-moving inventory and vendors with high capital tied up in unsold stock.

Exploratory data analysis for key metrics such as:

Total sales vs. purchase quantity

Profit margin trends

Inventory turnover ratios

Gross profit patterns

Visualization of profit margin distributions and inventory performance using histograms and confidence interval plots.

Hypothesis testing to determine if profit margins differ significantly between top and low-performing vendors.

Methodology

Data Cleaning & Aggregation

Filter inconsistent or negative data points (e.g., negative profit, zero sales).

Aggregate sales, purchase, and inventory data by vendor for analysis.

Vendor Performance Segmentation

Top Vendors: Sales ≥ 75th percentile

Low Vendors: Sales ≤ 25th percentile

Profitability Analysis

Calculated mean profit margins and 95% confidence intervals for top and low-performing vendors.

Conducted two-sample t-tests to compare margins.

Inventory & Stock Turnover Analysis

Computed unsold inventory value per vendor.

Identified slow-moving products and vendors with high inventory holding costs.

Insights & Recommendations

Highlighted areas for promotional campaigns, pricing adjustments, and inventory optimization.

Sample Findings

Low-performing vendors maintain higher profit margins but lower sales volumes, suggesting opportunities for targeted marketing or improved distribution.

Total unsold inventory across vendors is significant (~$2.7M), highlighting areas for operational improvements.

Profit margins vary between vendor segments, confirming the need for strategic pricing and vendor management.

Future Enhancements

Revenue & Profit Forecasting: Develop predictive models to estimate revenue and margin based on sales trends and seasonality.

Dynamic Pricing Simulation: Simulate pricing strategies to optimize profit margins without affecting sales volume.

Inventory Optimization Models: Implement algorithms to minimize stock holding costs while maintaining adequate supply.

Interactive Dashboards: Create Power BI dashboards for real-time vendor performance tracking.

Anomaly Detection: Identify unusual sales patterns or outliers to prevent financial loss.

Vendor Benchmarking: Compare vendors across multiple KPIs to support procurement decisions.

Tools & Technologies

Python (Pandas, NumPy, SciPy)

Matplotlib & Seaborn for visualization

Jupyter Notebook for interactive analysis

Power BI for dashboard creation

GitHub for version control and portfolio showcase

How to Run

Clone the repository:

git clone https://github.com/PALLAVI0012/vendor-performance-analysis.git


Install required packages:

pip install pandas numpy scipy matplotlib seaborn


Load your dataset and run the analysis scripts:

import pandas as pd
df = pd.read_csv("vendor_data.csv")


Explore visualizations and reports generated from the scripts.

Author


Pallavi– Aspiring Data Analyst | Portfolio Project

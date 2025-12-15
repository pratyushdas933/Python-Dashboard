Streamlit Superstore Sales Dashboard – Interpretation

<img width="1919" height="955" alt="Screenshot 2025-12-15 094039" src="https://github.com/user-attachments/assets/463d4967-1238-4826-9509-6ec2235fec20" />


This Streamlit application is an interactive Exploratory Data Analysis (EDA) dashboard built using the Superstore sales dataset. The dashboard allows users to dynamically analyze sales performance across time, geography, product categories, and customer segments.

The application begins by enabling users to upload their own dataset or fall back on a default Superstore CSV file. A date range filter is applied to focus the analysis between selected start and end dates. Additional sidebar filters for Region, State, and City allow granular geographic analysis, with the dataset updating automatically based on user selections

Key visualizations include:

Category-wise sales bar chart to identify top-performing product categories.

Region-wise sales pie chart to show contribution of different regions to total sales.

Time-series line chart illustrating monthly sales trends, useful for identifying seasonality and growth patterns.

Treemap visualization providing a hierarchical view of sales by Region → Category → Sub-category.

Segment-wise and Category-wise pie charts highlighting customer and product distribution.

Scatter plot of Sales vs Profit, with quantity represented by marker size, helping identify profitable and loss-making transactions.

The dashboard also includes expandable data tables, allowing users to view summarized and raw data with color gradients for better readability, and provides download options for processed datasets such as category, region, and time-series summaries 
Overall, this dashboard serves as a comprehensive business intelligence tool for sales analysis, enabling decision-makers to quickly explore trends, compare performance across dimensions, and extract actionable insights through an intuitive and interactive interface.

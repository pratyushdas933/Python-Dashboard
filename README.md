Streamlit Superstore Sales Dashboard – Interpretation

<img width="1543" height="901" alt="Screenshot 2025-12-15 094708" src="https://github.com/user-attachments/assets/c9fa8f73-d50a-4a20-8daf-014683888b10" />
<img width="1553" height="932" alt="Screenshot 2025-12-15 094722" src="https://github.com/user-attachments/assets/986c80be-5f4d-4b49-9521-eecc6dd41783" />
<img width="1576" height="955" alt="Screenshot 2025-12-15 094735" src="https://github.com/user-attachments/assets/c3fd7cd2-4b36-4633-9a35-3d2049449532" />
<img width="1475" height="709" alt="Screenshot 2025-12-15 094747" src="https://github.com/user-attachments/assets/9ac3fe54-f36e-4138-83e9-48bdb651db70" />
<img width="1527" height="913" alt="Screenshot 2025-12-15 094800" src="https://github.com/user-attachments/assets/dac3a5b6-bc21-46ec-8202-a222c90eac22" />


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

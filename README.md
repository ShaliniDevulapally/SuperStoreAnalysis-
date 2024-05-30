# <span style="color:blue">Sales Performance Analysis Dashboard (2014-2017)</span>

Welcome to the **Sales Performance Data Insights Dashboard**, an interactive tool designed to analyze Super Store data from 2014 to 2017. This dashboard provides comprehensive insights into the company's growth in revenue, profits, and product sales across different categories.

## <span style="color:green">Problem Statement</span>

The Super Store aims to enhance its business performance by gaining a deeper understanding of sales trends, profitability, and customer purchasing behaviors from 2014 to 2017. Key challenges include identifying high-performing product categories, managing inventory to avoid overstock or stockouts, understanding the dynamics of new versus repeated orders, and improving profit margins. The objective of this project is to create an interactive dashboard that provides actionable insights, enabling data-driven decision-making to optimize pricing strategies, inventory management, and customer retention efforts.

## <span style="color:green">Key Features</span>

- **Revenue and Profit Analysis**: Track the growth in revenue and profits over the years, identifying key trends and patterns that can help in strategic decision-making.
- **Product Sales Performance**: Analyze the most and least sold product categories, enabling the company to make informed decisions about pricing and inventory management to minimize losses.
- **Interactive Visualizations**: Engage with the data through interactive visualizations that allow users to drill up or down, offering a detailed view of yearly cumulative sales growth.
- **Profit Margin Analysis**: Highlight the average profit margin of each subcategory to identify the most profitable sub-categories, helping to prioritize high-margin products.
- **Trends of Revenue Over Time**: Monitor trends in revenue over time by year and month to understand seasonality and growth patterns.
- **New and Repeated Orders Analysis**: View bar charts that differentiate between new and repeated orders to help in customer retention strategies.

This dashboard is designed for stakeholders to gain actionable insights into the business performance and to strategize effectively based on data-driven evidence.

## <span style="color:green">Data Sources</span>

- **orders.csv**: Complete order details, including order ID, product, sales, quantity, discount, and profit.
- **people.csv**: Information on the head of a particular region, helping to segment and analyze data by region.
- **returns.csv**: Contains `Order_ID` and `Returned` columns to track returned orders.

## <span style="color:green">Themes</span>

The current theme used for the dashboard is **Metricalist-Simply Modern Dark**, providing a sleek and modern look to the visualizations.

## <span style="color:green">Steps to Reproduce the Analysis</span>

1. **Data Preparation**:
    - Import the datasets (`orders.csv`, `people.csv`, `returns.csv`).
    - Clean and preprocess the data to handle missing values and ensure consistency.

2. **Data Integration**:
    - Merge the datasets to create a comprehensive dataset for analysis.
    - Join `orders.csv` with `returns.csv` on `Order_ID` to incorporate return information.
    - Join the resulting dataset with `people.csv` based on the regional head information.

3. **Calculations and Metrics**:
    - Calculate **Cumulative Total Sales**: Sum of sales over time.
    - Identify **Repeated Order IDs**: Orders from returning customers.
    - Compute **Profit, Revenue, and Cost**: Key financial metrics.
    - Derive **Average Profit Margin**: Profitability of each subcategory.

4. **Visualization**:
    - Create interactive visualizations using a dashboard tool (e.g., Tableau, Power BI).
    - Ensure the ability to drill up and down in the data for detailed analysis.

5. **Interactive Elements**:
    - Incorporate filters and interactive elements to allow users to customize their view.
    - Highlight key metrics and trends with visual cues.

## <span style="color:green">Screenshots</span>

Include snapshots of the following measures calculated in the dashboard:

- [Cumulative Total Sales](#)

  ![CumulativeTotalSales](https://github.com/ShaliniDevulapally/SuperStoreAnalysis-/assets/105088900/aee6502e-187e-4998-9f2a-67abb2e5f374)    
- [Repeated Order IDs](#)
  
  ![RepeatedOrderIDs](https://github.com/ShaliniDevulapally/SuperStoreAnalysis-/assets/105088900/d068717b-8bb5-4bdb-8727-c6d9f2343b08)
- [Profit](#)
- [Revenue](#)
- [Cost](#)
- [New and Repeated Orders](#)

  ![NewOrderIds](https://github.com/ShaliniDevulapally/SuperStoreAnalysis-/assets/105088900/1531b66c-e2c0-4c17-b8e6-4e38ba542c85)

  
- [Average Profit Margin](#)


## <span style="color:green">Snapshot of Dashboard</span>

![SuperStoreDashboard](https://github.com/ShaliniDevulapally/SuperStoreAnalysis-/assets/105088900/2094ebde-1698-446f-af3d-f401d9ebefc7)


## <span style="color:green">How to Use</span>

1. Clone the repository.
2. Import the datasets into your preferred data analysis tool.
3. Follow the steps outlined in the "Steps to Reproduce the Analysis" section to recreate the analysis.
4. Explore the interactive dashboard to gain insights and make data-driven decisions.

## <span style="color:green">Conclusion</span>

This dashboard provides a powerful tool for analyzing Super Store data, offering deep insights into sales performance, customer behavior, and profitability. By leveraging this analysis, stakeholders can make informed decisions to drive business growth and efficiency.

---


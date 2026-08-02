## Amazon Sales Data Analysis 📊🛒

## 🎯 Project Objective
- The main goal of this project is to perform Exploratory Data Analysis (EDA) on an Amazon Sales dataset. By identifying sales trends, regional performance, and key operational metrics, this project aims to uncover hidden patterns that can help improve business decisions, optimize inventory management, and maximize overall profitability.
## Key Metrics Tracked (KPIs):
- Total Revenue: Total sales generated across all orders.
- Total Profit: Overall net margin earned by the company.
- Total Units Sold: Total volume of products shipped.
- Average Delivery Time: Average days taken between order date and ship date.
## Business Questions Addressed:
- What are the yearly and monthly revenue trends over time?
- Which geographic regions and countries generate the maximum sales and profit?
- What product categories (Item Types) are the top performers in volume vs. value?
- How do sales channels (Online vs. Offline) compare in terms of order volume and profit?
- Is there a correlation between product costs, selling prices, and net profits?

  ##  Process & Methodology
-  Data Inspection & Profiling: Loaded the dataset containing thousands of transactions and checked data types, shapes, and structural completeness.
- Data Cleaning:* Handled missing values in critical identifiers (like Order IDs) and categorical tags. Dropped corrupt or duplicate entries.
- Feature Engineering: Parsed raw date strings into structured pandas datetime formats. Extracted Order_Year, Order_Month, and Year_Month periods for         chronological analysis
-  Data Aggregation: Grouped transactions by regions, sales channels, time periods, and item categories to calculate totals and statistical frequencies.
- Data Visualization: Built visual frameworks using Matplotlib and Seaborn, including line charts, bar plots, distribution histograms, violin plots, and   correlation heatmaps.


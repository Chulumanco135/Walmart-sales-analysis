# Walmart-sales-analysis
# Retail sales comparison and analysis using R
# Project Topic
•	Sales Comparison and Performance Analysis Across Walmart Stores Using Weekly Sales Data.

# Background 
•	Many retail businesses operate in a challenging environment where the sale performances are influenced by various external and internal factors. Walmart as one of the biggest retail stores globally, collects data from different stores to understand trend, customer behavior and improve the decision-making. Sales can fluctuate based on seasonality, promotional events, regional differences, and economic indicators such as fuel prices, consumer price index (CPI), and unemployment rates. Analyzing this data helps uncover patterns and supports strategic planning.

# Problem statement 
•	Although Walmart store collects data every week but it does not clarify on which stores are underperforming or which factors (external or internal factors) influences their sales most. Without deeper analysis of the store sales the business opportunities and areas where there are issues may go unnoticed.

# Project Objectives
The objective of this project is to:
•	Compare weekly sales across different Walmart stores.
•	Analyze how sales are influenced by holidays and economic conditions.
•	Identify top-performing and underperforming stores.
•	Visualize patterns in sales over time and during special periods.
# Research Questions
•	Which Walmart stores perform best in terms of weekly sales?
•	Do holidays significantly impact weekly sales?
•	How do economic factors like fuel prices, CPI, and unemployment relate to sales performance?
•	Are there seasonal trends or anomalies in sales data?
# Aim 
•	This study focuses on sales data collected from multiple Walmart stores across different weeks. It covers sales trends, store comparisons, holiday effects, and economic influences using variables available in the dataset.
Significance of the Study
Understanding how various factors influence sales can help Walmart and other retailers:
•	Improve sales strategies across different regions.
•	Prepare better for holiday periods and economic fluctuations.
•	Optimize performance across branches based on data-driven insights.

                                         # Methodology

# Data Source
The dataset used in this project is a publicly available Walmart sales dataset containing 6,435 rows of weekly sales data from multiple Walmart stores. The data includes variables such as: 
•	Store number
•	Weekly sales figures
•	Holiday indicators
•	Economic indicators (fuel price, CPI, unemployment)
•	Temperature
•	Date of each record

# Variables used
•	Store
•	Date
•	Weekly Sales
•	Temperature
•	Fuel Price
•	Holiday Flag
Tools and software used
•	Microsoft Excel: For basic analysis, and visualization.
•	RStudio: For data cleaning, deeper statistical analysis and correlation testing .
Data Cleaning and Preparation
•	Converted date to proper format
•	Removed duplicates and missing values (if any). Created derived variables such as:
•	Monthly sales average
•	Sales during holidays vs non-holidays
•	Store-wise average weekly sales

# Data Analysis Techniques
•	Descriptive analysis
•	Comparative Analysis
•	Data Visualization
•	Correlation analysis

# Key Graphs and Visualizations
•	Line charts: Weekly sales trend over time
•	Bar charts: Store-wise average sales
•	Boxplots: Sales distribution during holiday vs non-holiday weeks
•	Scatter plots: Relationship between sales and economic indicators

#Conclusion

This chapter provides a final interpretation and conclusion based on the analysis conducted in the project. The study aimed to compare Walmart store sales, assess the impact of holidays, and explore the influence of economic factors using real weekly sales data.

As seen in the bar chart of average weekly sales by store, some stores (e.g., Store 20, Store 4) consistently outperform others, suggesting operational, geographic, or demographic advantages. This offers Walmart an opportunity to benchmark best practices and support underperforming stores. The boxplot comparing holiday vs non-holiday weeks showed that holiday weeks tend to have higher sales, but also more variability. This confirms that holidays are a key sales driver, but Walmart should improve consistency in how stores capitalize on peak periods. Correlation and regression results showed that economic variables like Fuel Price, CPI, and Unemployment have only weak negative correlations with Weekly Sales. The linear regression model had an R-squared value of only 0.024, meaning only 2.4% of the variation in sales was explained by these variables. This suggests that internal factors (e.g., promotions, store layout, customer service) and external ones (e.g., regional events, demographics) may have a greater influence on weekly sales. The line graph of weekly sales over time revealed clear seasonal trends, especially around year-end holidays. Sales peaks occur regularly, which provides strong justification for using time-based models (e.g., time series forecasting) in future analysis.
Walmart can target underperforming stores for improvement by analyzing practices of top stores. Strong holiday sales support seasonal marketing and staffing strategies. Because economic variables were weak predictors, future studies should include store-specific, promotion, and customer behavior data. A better predictive model would use machine learning or time series forecasting with additional features.

This project concluded that weekly sales at Walmart stores are influenced more by internal and seasonal factors than by external economic indicators

✅ Walmart dataset
https://drive.google.com/file/d/1asjyh5D5ubLYkJFgiB7Ai_b-JdNICeE6/view?usp=sharing

✅ Codes and graphs 
https://docs.google.com/document/d/1Z9GcPDWhTIVwQd_0FQmHPZ6bptvLpzQM/edit?usp=sharing&ouid=103479920004238899821&rtpof=true&sd=true

✅ File the whole project on
https://ahead-thing-2a1.notion.site/Walmart-online-project-1fa889a606d2805daed6dc2c12181476

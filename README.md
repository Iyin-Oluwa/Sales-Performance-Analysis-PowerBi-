# Sales-Performance-Analysis-PowerBi

## Table of Content

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tool](#tool)
- [Data Cleaning/Preparation](#data-cleaningpreparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Analysis Insight](#analysis-insight)
- [Result/Findings](#resultfindings)
- [Recommendations](#recommendations)

### Project Overview

This project aims to delve into the sales performance of a Store across a four-year period (2013-2017), concentrating on 10 states categorized into four regions (Central, East, South, West) within the USA. Through comprehensive analysis of the sales data, our objective is to uncover significant trends and patterns that offer valuable insights. By employing a data-driven approach, we aim to make informed recommendations to enhance performance and gain a detailed understanding of the company's overall business trajectory.




![Sales Analysis Dashboard_](https://github.com/Iyin-Oluwa/Store-Sales-Analysis--Excel/assets/171290094/5c1fc3bf-b90e-4c18-ae74-af168d8a252d)

### Data Source

Sales Data: The primary dataset used for this project is the 'Superstore.xlsx', containing detailed information about each sale made by the company.


### Tool
- Excel - Data Cleaning, Data Analysis and Creating a reports.
   - [Download here](https://microsoft.com)
     
- Power BI- Creating interactive reports and visualizations.
  -  [Download here](https://microsoft.com)


  ### Data Cleaning/Preparation
 - Data Loading and Inspection: The dataset was initially loaded into the analysis environment to thoroughly examine its contents. This step enabled understanding of the data's structure, including its columns and rows, providing an initial assessment of its overall quality and completeness.

- Handling Missing Values: Addressing any missing data points within the dataset involved identifying where data was absent and implementing appropriate strategies for handling these gaps, whether through imputation or removal, to ensure that the analysis was based on as complete a dataset as possible.

- Data Cleaning and Formatting: The data was cleaned to ensure accuracy and consistency for analysis. This process involved tasks such as correcting errors, removing duplicates, and standardizing formats (e.g., dates, text) across the dataset. Formatting also included ensuring correct assignment of data types (e.g., numerical values treated as numbers, categorical variables appropriately labeled).

  ### Exploratory Data Analysis
  EDA involved exploring the sales data to answer the key questions with the years and region as a benchmark.

  - What is the Overall sales?
  - What is the Total Profit?
  - What is the Yearly and Quarterly sales trend?
  - What is the Percentage of profit to sales?
  - What is the Sum of profit by Top 5 state?
 


### Metrics
The metrics included in the analysis are total sales, profit, total quantity, total discounts.These metrics provide a comprehensive view of sales performance and profitability.



### Data Analysis
Incude some intresting code worked with : 

``` dax
Profit Margin % = DIVIDE(SUM('Transaction'[Profit]), SUM('Transaction'[Sales]), 0)
```



### Analysis Insight

1 Overall Sales: The total sales revenue generated over the specified period reflecting the business's financial performance in terms of sales volume.

2 Total Profit: The cumulative profit earned during the analyzed timeframe.

3 Yearly and Quarterly Sales Trend: Analyzing the trends in sales on a yearly and quarterly basis provides valuable insights into revenue patterns, highlighting periods of growth, seasonality, or fluctuations that impact overall business perform

4 Percentage of Profit to Sales: The ratio of total profit to total sales, indicating the efficiency of converting sales revenue into profit.

5 Sum of Profit by Top 5 States: Summarizes the total profit generated across the top five states in terms of sales revenue, highlighting geographical areas contributing significantly to overall profitability.

### Result/Findings

- The total sales has the sum value of sales from the 3 segments (Consumer, Corporate, Home Office), having Consumer segment with the highest value.
- Total Profit has the sum value of sales from the 3 categories ( Furniture, Office supplies, Technology), which shows that Technology category is profitable to the company.
- The annual and quarterly sales trends indicate fluctuations in profitability over time. However, starting from the fourth quarter of 2017, there has been a noticeable upward movement in the trend.
- The Percentage of Profit to Sales is approximately 12%.
- Profit by Top 5 State: This shows the sum value from the highest to the lowest, California emerges as a high-profit state.
    

### Recommendations
Based on our analysis, here are straightforward recommendations:

- Focus on Consumer Segment: Since consumers drive the highest sales, prioritize targeted marketing campaigns and enhance customer experience to boost engagement and loyalty.

- Leverage Technology Category: Expand offerings in technology to capitalize on its profitability. Consider introducing new products, improving distribution, and enhancing after-sales support.

- Profitability Management: Monitor and analyze quarterly and annual profitability trends closely. Identify factors contributing to the recent upward trend in profitability and assess how they can be sustained or amplified. This may involve optimizing operations, controlling costs, or enhancing product/service differentiation.

- Margin Maintenance: To keep profits strong despite market changes and competition, review pricing, efficiency, and cost management regularly.
  
- Geographical Expansion: Focus on High-Profit States (e.g., California): Develop tailored approaches for states with high profitability like California, including localized marketing initiatives, strategic partnerships, and customer service enhancements.
  
These actions aim to enhance performance, manage risks, and seize opportunities identified through our analysis of sales and profitability data.

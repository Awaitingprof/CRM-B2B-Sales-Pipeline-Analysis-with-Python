# CRM-B2B-Sales-Pipeline-Analysis-with-Python
This project presents a comprehensive Exploratory Data Analysis (EDA) of a B2B CRM sales pipeline, using Python to derive insights into sales performance, customer characteristics, product effectiveness, revenue generation, and quarterly sales trends.
The analysis uses a relational CRM dataset containing 8,800 sales opportunities, 85 customer accounts, 7 products, and 35 sales agents. The objective is to transform raw CRM data into meaningful business intelligence that can support sales strategy, performance management, and revenue optimization.

The project follows a structured, business-oriented EDA framework, progressing from data understanding and quality assessment to statistical analysis, visualization, relationship analysis, and business recommendations.
## Business Objectives
The analysis was designed to answer four core business questions:

1. How is each sales team performing compared with the others?
2. Are any sales agents significantly lagging behind their peers?
3. What quarter-over-quarter trends exist in sales performance and revenue?
4. Do certain products demonstrate stronger win rates or revenue potential?
In addition, Is understanding opportunity volume, sales outcomes, deal values, customer characteristics, product performance, regional differences, and relationships between key variables.
## Datasets
The project uses five interconnected CSV files:
### Dataset	             ### Description
- Accounts.csv	        Customer account information, including industry, revenue, employees,                            location, and parent company
- Products.csv	        Product catalogue containing product series and sales prices
- Sales_teams.csv	      Sales-agent information, including managers and regional offices
- Sales_pipeline.csv	  Sales opportunities, stages, dates, agents, products, accounts, and deal                         values
- Data_dictionary.csv	    Definitions and descriptions of the dataset fields

## Tools & Technologies
- Python
- Pandas for Data manipulation and analysis
- NumPy for Numerical computation
- Matplotlib for Data visualization
- Seaborn  for Statistical visualization

## Analytical Workflow
The project follows a structured 17-step EDA process:
- Define the analytical objective
- Import required libraries
- Load the datasets
- Understand the datasets
- Inspect data structures and data types
- Identify and assess missing values
- Check for duplicate records
- Identify and correct data-quality issues
- Generate descriptive statistics
- Perform univariate analysis
- Perform bivariate analysis
- Perform multivariate analysis
- Detect and investigate outliers
- Analyze correlations and relationships
- Visualize distributions, trends, and patterns
- Create relevant analytical features
- Summarize findings and develop business recommendations

## Sales Pipeline Performance
The dataset contains 8,800 opportunities:
- 4,238 Won
-  2,473 Lost
-  1,589 Engaging
-  500 Prospecting
-  This represents a 63.15% win rate among closed opportunities.
## Sales Team Performance
Different teams lead on different performance dimensions.
-  Cara Losch recorded the highest team win rate at 64.43%.
-  Melvin Marxen generated the highest Won revenue at approximately $2.25M.
-  Rocco Neubert recorded the highest average Won deal value at approximately $2,837.
-  Summer Sewald demonstrated a strong balance between opportunity volume, conversion rate, and revenue.
-  Dustin Brinkmann's team generated comparatively low average and median deal values despite closing a substantial number of opportunities.

This demonstrates that sales-team performance should not be evaluated using win rate alone. Volume, conversion, revenue, and deal value provide complementary measures of performance.

## Sales Agent Performance
Agent-level performance also varied considerably.
- Hayden Neloms recorded the highest observed win rate at approximately 70.39%.
- Lajuana Vencill recorded the lowest at approximately 54.98%.
- Darcel Schlecht managed the largest opportunity volume with 747 opportunities.
The analysis also examined agent-product combinations, revealing that some agents achieved particularly strong conversion rates with specific products. However, combinations with very small sample sizes were treated cautiously to avoid overstating their significance.

## Product Performance
Product analysis revealed a major distinction between conversion efficiency and revenue contribution.
-  MG Special achieved the highest win rate at approximately 64.84%, but its average Won deal value was only about $55, resulting in just $43,768 in Won revenue.
In contrast:
   - GTX Pro generated the highest Won revenue at approximately $3.51M.
   - GTX Plus Pro had an average Won deal value of approximately $5,490.
   - GTK 500 had an exceptionally high average Won deal value of approximately $26,707, although     this was based on only 15 Won deals.
This means that :
#### A product with a high win rate is not necessarily the product with the highest revenue potential.

## Regional Performance
The three regional offices also demonstrated different performance profiles.
  - West achieved the highest win rate at 63.94% and generated approximately $3.57M in Won revenue.
  - Central managed the largest opportunity volume.
  - East recorded the highest average and median Won deal values.
#### This Shows an important analytical principle: volume, conversion efficiency, and deal value can produce different rankings of business performance.

## Quarterly Sales Trends
Quarterly analysis revealed a noticeable change in sales performance during 2017.

After the partial Q1:
 - Win rate declined from 61.71% in Q2 to 60.25% in Q4.
 - Won revenue peaked at approximately $3.09M in Q2 before declining through Q3 and Q4.
 - Average Won deal value also peaked in Q2 and subsequently declined.
#### This shows that the decline in revenue after Q2 was influenced by both weaker conversion and declining average deal value, rather than simply a reduction in sales activity.

## Account-Level Insights
A correlation analysis revealed a very strong positive relationship (0.95) between account revenue and employee count. This shows that larger organizations, measured by employee count have substantially higher annual revenue within the dataset.
A moderate negative relationship was also observed between company establishment year and both revenue and employee count, suggesting that older companies in this dataset tend to be larger.

## Business Recommendations
- 1. Investigate the post-Q2 performance decline
Management should investigate why win rates, Won revenue, and average deal values declined during the second half of 2017.
-  2. Examine low-value sales patterns
Dustin Brinkmann's team warrants further investigation because of its comparatively low deal values despite substantial Won-deal volume.
- 3. Prioritize high-value product opportunities
Products such as GTX Pro and GTX Plus Pro demonstrate strong revenue potential through relatively high deal values combined with competitive win rates.
- 4. Use multiple KPIs for sales evaluation
Sales performance dashboards should incorporate:
Opportunity Volume + Win Rate + Won Revenue + Average Deal Value + Open Pipeline rather than relying on a single performance metric.
- 5. Investigate product-agent interactions
High-performing agent-product combinations could provide useful insights for sales enablement, product positioning, and targeted training.
- 6. Treat small samples carefully
Exceptional results from products or agent-product combinations with very few observations should be validated with additional data before informing major business decisions.
## Skills Demonstrated
- Data Analysis
- Exploratory Data Analysis
- Data Cleaning
- Data Quality Assessment
- Statistical Analysis
- Business Intelligence
- Sales Analytics
- Revenue Analysis
- KPI Analysis
- Data Visualization
- Correlation Analysis
- Outlier Detection
- Feature Engineering
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn 

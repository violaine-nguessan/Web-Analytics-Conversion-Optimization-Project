# 📊 Web Analytics & Conversion Optimization Project



## Executive Summary

This project analyzes web analytics data from the Google Analytics demo dataset using SQL and Python to uncover actionable insights about conversion rates, customer behavior, and marketing performance. The goal is to help businesses optimize marketing investments, improve conversion performance, and identify high-value customer segments.

The analysis combines statistical testing, customer segmentation, regression modeling, and SQL analytics techniques to evaluate how factors such as traffic sources, time of day, and customer behavior impact conversions and revenue. Key insights provide strategic guidance on when and where to invest marketing resources and which customer segments to prioritize. I recommend the following actions to improve marketing efficiency and conversion performance:

1. Prioritize high-performing traffic sources that generate the highest conversion rates and order values.
2. Invest in customer segments with the highest revenue potential identified through clustering analysis.
3. Align marketing campaigns with time periods showing slightly higher conversion performance.
4. Use data-driven models to monitor and predict conversion trends over time.

### Business Problem

An e-commerce business wants to better understand what drives conversions and revenue on its website. With multiple traffic sources, customer behaviors, and time-based patterns, the company needs to identify:

Which traffic sources generate the highest conversions and revenue 
Whether conversion rates vary significantly by time of day 
Which customer segments are most valuable
Which variables influence daily conversion rates
How to optimize marketing investments using data

The challenge is to analyze web analytics data to provide clear, actionable recommendations that improve conversion performance and maximize return on marketing spend.

### Methodology

1. Data Extraction & Preparation : The dataset was queried using SQL on the Google Analytics demo database to extract session, transaction, and revenue information. The data was then cleaned, aggregated, and structured in Python in order to prepare it for statistical analysis and modeling.
2. Exploratory Analysis : An exploratory analysis was conducted to understand user behavior and performance trends. Conversion rates were analyzed across different hours of the day and time periods, while traffic sources and average order values were compared to identify performance differences. Revenue trends were also examined over time to detect patterns and seasonality.
3. Statistical Analysis : Statistical methods were applied to validate observed trends. An ANOVA test was used to determine whether conversion rates varied significantly depending on the time of day. Regression analysis was then performed to identify which variables had the strongest influence on daily conversion rates.
4. Customer Segmentation : Customer segmentation was carried out using a K-means clustering model. Users were grouped based on behavioral and revenue-related variables in order to identify high-value segments and better understand differences in purchasing behavior.
5. SQL Analytics : Advanced SQL techniques were used to deepen the analysis. Window functions allowed ranking of traffic sources by performance, while moving averages and cumulative metrics helped track revenue and purchase trends over time.
6. Visualization & Interpretation : Visualizations were created in Python to present key findings clearly and support interpretation. These visual outputs were used to translate analytical results into business insights and actionable recommendations.

### Skills

1. Data Analysis & Transformation : SQL was used to query, join, and aggregate web analytics data from the dataset, while Python was used to clean, transform, and structure the data for analysis.
2. Statistical Analysis : Statistical techniques such as ANOVA and linear regression were applied to evaluate conversion rate differences and identify variables influencing performance trends.
3. Data mining : A K-means clustering model was implemented in Python to segment users into meaningful groups based on revenue and behavioral patterns.
4. Data Visualization : Python libraries such as Matplotlib and Pandas were used to create visualizations that highlight trends, comparisons, and key performance indicators.
5. Analytics Engineering : Advanced SQL features, including window functions, aggregations, and KPI calculations, were used to analyze traffic sources, revenue growth, and conversion performance.

### Results & Business Recommendation

The analysis shows that conversion rates remain relatively stable across different times of day, with only minor variations and no strong statistical evidence of significant differences. This suggests that time-based targeting alone may not dramatically improve conversion performance. However, traffic source analysis reveals clear differences in performance. Certain sources generate significantly higher conversion rates and higher-value purchases, indicating that marketing budgets should prioritize these channels.
Customer segmentation using K-means identified a high-value cluster with the highest average purchase revenue. This segment represents the most profitable audience and should be the primary target for marketing and retention strategies.
Regression analysis indicates that multiple variables (traffic source, device category, geography, and time factors) influence daily conversion rates, though the relationship is moderate. This highlights the importance of using data-driven monitoring rather than relying on a single factor.

Key Recommendations : 

1. Invest more in high-converting traffic sources to maximize ROI.
2. Target the highest-revenue customer cluster for marketing campaigns.
3. Monitor conversion trends with predictive models to anticipate changes.
4. Continue analyzing customer behavior to refine segmentation strategies.
5. Use SQL dashboards and automated reporting to track performance over time.

### Next Steps

1. Build an interactive dashboard (Power BI / Tableau / Looker Studio).
2. Implement predictive models to forecast conversions and revenue.
3. Track campaign performance in real time.
4. Conduct A/B testing on high-value customer segments.
5. Expand analysis to additional time periods and markets.

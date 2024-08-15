# Promotional_Analysis
Analyzing Promotional Campaign Performance at AtliQ Mart During Diwali 2023 and Sankranti 2024
## Project Introduction:
In the dynamic landscape of the retail industry, promotional campaigns serve as pivotal drivers of sales and customer engagement, particularly during festive seasons. This project delves into the realm of data analytics to scrutinize the performance of promotional endeavors carried out by AtliQ Mart, a prominent retail chain operating over 50 supermarkets in the southern region of India, recently conducted a large-scale promotion during the festive periods of Diwali 2023 and Sankranti 2024. Through rigorous analysis, our objective is to unearth valuable insights into the efficacy of these campaigns, enabling us to furnish actionable recommendations for enhancing future marketing strategies.

## Project Overview:
The analysis relies on data sourced from AtliQ Mart's internal databases, utilizing key datasets such as fact_events, dim_products, dim_stores, and sales_summary. These datasets encompass crucial details regarding product sales, store locations, promotional events, and campaign revenues, forming the foundation for insightful analysis and decision-making.

## Methodology
### Data Collection:
* Gathered data from AtliQ Mart's internal databases, including Facts table(facts_table) and dimension table(dim_table).

### SQL Queries:
* Utilized SQL queries to extract relevant information from the datasets.
* Implemented common table expressions (CTEs) to simplify complex queries and improve readability.
* Applied filtering conditions and joins to merge multiple tables and extract desired insights.

###  Analytical Thinking:
*  Employed analytical thinking to identify key metrics and KPIs relevant to the analysis.
*  Formulated hypotheses and questions to guide the analysis process.
*  Applied critical thinking skills to interpret query results and derive meaningful insights.

### Adhoc Request Analysis:
* Using SQL queries, we performed ad hoc analysis to address various business requests related to promotional campaign performance.
* This included identifying high-value products featured in promotions, evaluating store distribution across cities, assessing revenue generated before and after each campaign, calculating incremental sold quantity for different product categories, and identifying top-performing products based on incremental revenue percentage.
* Reports Provided as the Requests:-
  1. . Provide a list of products with a base price greater than 500 and that are featured in promo type of 'BOGOF' (Buy One Get One Free). This information will help us identify high-value products that are currently being heavily discounted, which can be useful for evaluating our pricing and promotion strategies.
  2.  Generate a report that provides an overview of the number of stores in each city. The results will be sorted in descending order of store counts, allowing us to identify the cities with the highest store presence. The report includes two essential fields: city and store count, which will assist in optimizing our retail operations.
  3.  Generate a report that displays each campaign along with the total revenue generated before and after the campaign? The report includes three key fields: campaign _name, total revenue(before_promotion), total revenue(after_promotion). This report should help in evaluating the financial impact of our promotional campaigns. (Display the values in millions)
  4. 	Produce a report that calculates the Incremental Sold Quantity (ISU%) for each category during the Diwali campaign. Additionally, provide rankings for the categories based on their ISU%. The report will include three key fields: category, isu%, and rank order. This information will assist in assessing the category-wise success and impact of the Diwali campaign on incremental sales.
  5.  Create a report featuring the Top 5 products, ranked by Incremental Revenue Percentage (IR%), across all campaigns. The report will provide essential information including product name, category, and ir%. This analysis helps identify the most successful products in terms of incremental revenue across our campaigns, assisting in product optimization.
  
### Reporting:
*  Documented SQL queries, including explanations and rationale behind each query.
*  Generated comprehensive reports summarizing the findings of the analysis, including key insights, trends, and recommendations.
*  Presented the reports to the Sales Director and other stakeholders to facilitate data-driven decision-making.

## Results & Insights:
The analysis revealed valuable insights into the performance of promotional campaigns during Diwali 2023 and Sankranti 2024. These insights include:

*  Identification of promotional strategies and high-performing products.
*  Assessment of geographical trends and store distribution.
*  Evaluation of revenue impact and effectiveness of promotional discounts.
*  Incremental sold quantity and revenue percentage during the Diwali campaign
*  Recommendations for optimizing future marketing strategies based on data-driven insights.

## Conclusion:
In conclusion, our analysis of AtliQ Mart's promotional campaigns during Diwali 2023 and Sankranti 2024 has provided valuable insights into various aspects of their sales and marketing strategies. We identified high-value products featured in 'BOGOF' promotions, analyzed the distribution of stores across different cities, and examined the total revenue generated before and after each promotional campaign. Additionally, our analysis delved into the incremental sold quantity and revenue percentage during the Diwali campaign, shedding light on the effectiveness of the promotions. Furthermore, we identified the top 5 products ranked by incremental revenue percentage, offering actionable insights for future promotional efforts. These findings will assist AtliQ Mart in optimizing their promotional strategies, enhancing sales performance, and driving customer engagement in future campaigns.

## Power Bi Dashboard
In addition to the primary analysis, I developed an additional Power BI dashboard to offer further information and insights. This dashboard includes three distinct views:

Live dashboard link : [Link](https://app.powerbi.com/view?r=eyJrIjoiZjA1YThlZTktYjZjNy00MDVmLTk2ZmUtNTk4MmFlNTY3ZDdmIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

### 1.Promotional Analysis
*  This view offers insights into the effectiveness of different promotion types by highlighting the top promotion types based on Incremental Revenue and the bottom promotion types based on Incremental Sold Units.
*  Users can compare the performance of various promotion types and identify the optimal promotion type for maximizing revenue.
*  ![Screenshot 2024-02-22 113736](https://github.com/Reyyadav/Promotional_Analysis/assets/153619494/06bb5ebf-5255-45f6-ab48-620af206de82)

### 2.Store Performance Analysis
*  This view provides a comprehensive overview of store performance metrics, allowing stakeholders to identify top-performing stores based on Incremental Revenue (IR) and bottom-performing stores based on Incremental Sold Units (ISU).
*  Users can drill down into specific cities to analyze store performance trends across different geographical locations.
*  ![Screenshot 2024-02-21 155821](https://github.com/Reyyadav/Promotional_Analysis/assets/153619494/9f8c181f-7787-45c9-9ecb-c514afba0200)

### 3.Product-wise Analysis
*  This view focuses on analyzing product performance and category trends, helping stakeholders identify high-lifting product categories and assess product responsiveness to promotions.
*  Users can explore the correlation between product categories and promotion type effectiveness, enabling data-driven decision-making for future promotional strategies.
*  ![Screenshot 2024-02-21 155844](https://github.com/Reyyadav/Promotional_Analysis/assets/153619494/f407ccfb-53b0-4820-94c4-b05867a7b7f0)
*  ![Screenshot 2024-02-21 155904](https://github.com/Reyyadav/Promotional_Analysis/assets/153619494/8ee76a23-aba6-4c32-8541-5cace53b96b0)

## Future Work
### Competitive Analysis:
Conduct competitive analysis to benchmark AtliQ Mart's promotional performance against industry peers and competitors. By comparing key metrics such as sales growth, market share, and customer acquisition, AtliQ Mart can identify areas of competitive advantage and opportunities for improvement to stay ahead in the market.
### Integration with Customer Feedback:
Integrate customer feedback data into the analysis to gain insights into customer satisfaction levels, preferences, and sentiments regarding promotional campaigns. By incorporating qualitative feedback from customers, AtliQ Mart can refine its promotional strategies and tailor offerings to better meet customer needs and preferences.
### Long-Term Impact Assessment:
Evaluate the long-term impact of promotional campaigns on brand loyalty, customer retention, and overall business performance. By conducting longitudinal studies and tracking key performance indicators (KPIs) over time, AtliQ Mart can measure the sustained effectiveness of its promotions and identify areas for continuous improvement and innovation.

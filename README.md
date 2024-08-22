# CUSTOMER-PERSONALITY-ANALYSIS

## TABLE OF CONTENT
- [CUSTOMER PERSONALITY ANALYSIS OVERVIEW](#customer-personality-analysis-overview)
- [LANDING PAGE](#landing-page)
- [DATA SOURCE](#data-source)
- [TOOLS](#tools)
- [TYPES OF ANALYSIS USED FOR THIS PROJECT](#types-of-analysis-used-for-this-project)
- [KEY PERFORMANCE INDICATORS](#key-performance-indicators)
- [DATA CLEANING](#data-cleaning)
- [DATA PROCESSING](#data-processing)
- [DATA ANALYSIS](#data-analysis)
- [INSIGHTS](#insights)
- [RECOMMENDATIONS](#recommendations)

## CUSTOMER PERSONALITY OVERVIEW
The market campaign dataset provides a comprehensive view of customer behavior and responses to various marketing initiatives. It includes data on customer demographics, purchasing habits, and campaign interactions, allowing for an in-depth analysis of marketing effectiveness and customer segmentation.

## LANDING PAGE
The dataset is organized into three primary sections:
1. PEOPLE: This section contains demographic and behavioral data about the customers.

* ID: A unique identifier for each customer.
* Year_Birth: The customer's year of birth, useful for calculating age and analyzing age-related trends.
* Education: The customer's highest level of education, categorized into levels such as 'Graduation', 'PhD', 'Master', and '2nCycle'.
* Marital_Status: The customer's marital status, which can influence purchasing behavior.
* Income: The customer's annual household income, which is crucial for understanding purchasing power.
* Kidhome: The number of children living at home, influencing household-related purchases.
* Teenhome: The number of teenagers living at home, also impacting household purchasing decisions.
* Dt_Customer: The date when the customer enrolled with the company, which can be used to calculate customer tenure.
* Recency: The number of days since the customer last made a purchase, indicating engagement levels.
* Complain: A binary indicator showing whether the customer has complained in the last two years.

2. PRODUCTS: This section focuses on the products that customers have purchased.
* MntWines: The amount spent on wine in the last two years.
* MntFruits: The amount spent on fruits in the last two years.
* MntMeatProducts: The amount spent on meat products in the last two years.
* MntFishProducts: The amount spent on fish in the last two years.
* MntSweetProducts: The amount spent on sweets in the last two years.
* MntGoldProds: The amount spent on gold products in the last two years.
PromotionNumDealsPurchases: The number of purchases made with a discount, indicating price sensitivity.
* AcceptedCmp1 - AcceptedCmp5: Indicators for whether the customer accepted offers in five different campaigns.
* Response: Whether the customer responded positively to the last campaign.

3. PLACE: This section captures the purchasing channels used by customers.
* NumWebPurchases: The number of purchases made through the company's website.
* NumCatalogPurchases: The number of purchases made using a catalog.
* NumStorePurchases: The number of purchases made directly in stores.
* NumWebVisitsMonth: The number of visits to the company’s website in the last month, indicating online engagement.

## DATA SOURCE
This data set was gotten from cognorise as a task for my internship.
-[download here](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)

## TOOLS
- Analysis - jupyter notebook
- Visualization - jupyter notebook

## TYPES OF ANALYSIS USED FOR THIS PROJECT
* Customer Segmentation: To identify distinct groups of customer based on demographics, purchasing behaviors and engagement with marketing campaigns.
* Customer Lifetime Value (CLV) Analysis: To estimate the total value a customer is expected to bring to the company over time.
* Product Preference Analysis: To understand which product preference are most popular among different customer segments.
* Campaign effectiveness Analysis: To evaluate the success of marketing campaigns.
* Customer Churn Analysis: To identify customers who are likely to stop purchasing and why.
* Channel Analysis: To assess the performance of different purchasing channels.
* Customer Satisfaction Analysis: To measure and improve customer satisfaction.
* Demographics Analysis: To understand the demographics of your customer base.

## KEY PERFORMANCE INDICATORDS
* Age group (derived from 'Year_Birth).
* Education level distribution.
* Marital status distribution.
* Average income per segment.
* Average Recency (days since last purchase).
* Number of complains per segment.
* Total amount spent on products.
* Average revenue per customer.
* Frequency of purchase
* Recency
* Tenure
* Average spending per product category
* pProduct preference by segment
* Correlation between product categories
* Total revenue per product category.
* Campaign response rate.
* Conversion rate(percentage of customers who made a purchase after a campaign).
* Average spending by campaign responder.
* Response raete by customer segment.
* Number of complaints.
* Cu8stomer tenure and churn rate.
* Number of purchase by channel.
* Average order value by channel.
* Return on investmen(ROI) for promotional campaigns by channel.
* Relationship between complains and campaign response.

## DATA CLEANING
The dataset was clean as no null values or incorrect spellings were found.

## DATA PROCESSING
* Tenure column was created from dt_customers.

## DATA ANALYSIS
* Total Number of Customers is 2,240.

* Age Group Distribution
0-18: 0 customers
19-25: 0 customers
26-35: 61 customers
36-45: 363 customers
46-55: 740 customers
56-65: 506 customers
66-75: 460 customers
76-85: 107 customers
86-100: 0 customers
This shows that the majority of the customers are between the ages of 36 and 75, with the highest concentration in the 46-55 age group. There are no customers in the 0-18 and 19-25 age ranges, indicating that younger people are not part of this customer base. This could influence marketing strategies to target middle-aged and older individuals.

* Education Level Distribution
Graduation: 1,127 customers
PhD: 486 customers
Master: 370 customers
2n Cycle: 203 customers
Basic: 54 customers
This breakdown shows that most customers have a higher education level, with over half of them being graduates. A significant number also hold PhDs and Master’s degrees. This suggests that the customer base is generally well-educated, which might influence the type of products or services marketed to them.

* Marital Status Distribution
Married: 864 customers
Together: 580 customers
Single: 480 customers
Divorced: 232 customers
Widow: 77 customers
Alone: 3 customers
Absurd: 2 customers
YOLO: 2 customers
The majority of customers are married or in a relationship (together). There is also a significant number of single and divorced customers. The presence of unusual categories like “Alone,” “Absurd,” and “YOLO” suggests some data anomalies or creative entries, which might need further cleaning or consideration when analyzing the marital status segment.

* Average Recency is 49.11 days. The average recency of 49.11 days indicates that, on average, customers last made a purchase approximately 49 days ago. This metric is critical for understanding customer engagement and can help identify potential churn. A lower recency implies more recent customer engagement, while a higher value could indicate a risk of churn.

* Total Amount Spent on Products: $1,356,988.

* Average Revenue per Customer is $605.80. On average, each customer has spent $605.80. This metric, also known as average revenue per user (ARPU), is essential for understanding customer value. Higher ARPU indicates that customers are more valuable, spending more on the company’s products or services.

* Average Number of Web Purchases: 4.08
  
* Average Number of Catalog Purchases: 2.66

* Average Number of Store Purchases: 5.79
  
* Average Number of Web Visits per Month: 5.32

* Average Amount Spent on Products
- Wines: $303.94
- Fruits: $26.30
- Meat: $166.95
- Fish: $37.53
- Sweets: $27.06
- Gold: $44.02
This shows the average amount each customer spends on different product categories over the given period. The highest average spending is on wines ($303.94), followed by meat products ($166.95). This suggests that these two categories are the most popular or have higher price points. In contrast, spending on fruits, sweets, and gold is relatively low, indicating either lower interest or lower price points in these categories.

* Total Revenue per Product
- MntWines: $680,816
- MntFruits: $58,917
- MntMeatProducts: $373,968
- MntFishProducts: $84,057
- MntSweetProducts: $60,621
- MntGoldProds: $98,609
This metric reflects the total revenue generated from each product category across all customers. Wines contribute the most to total revenue, followed by meat products. Fruits, sweets, and fish generate lower revenue, which aligns with the lower average spending seen earlier. This information can help in prioritizing products for promotions or stocking decisions.

* Correlation Matrix Between Product Categories
The correlation matrix shows how spending in one product category relates to spending in another. For example, MntMeatProducts and MntFishProducts have a strong positive correlation (0.568402), indicating that customers who spend more on meat also tend to spend more on fish.
MntFruits and MntSweetProducts also show a positive correlation (0.567164), suggesting that customers who buy fruits may also buy sweets.

* Campaign Acceptance Rate
- AcceptedCmp1: 6.43%
- AcceptedCmp2: 1.34%
- AcceptedCmp3: 7.28%
- AcceptedCmp4: 7.46%
- AcceptedCmp5: 7.28%
- Response (latest campaign): 14.91%
These percentages represent the proportion of customers who accepted offers from various campaigns. The latest campaign has the highest acceptance rate (14.91%), indicating it was the most successful. 

* Percentage of Customers Who Made Purchases After Campaigns: 27.19%
This shows that 27.19% of the customers who received campaign offers made a purchase afterward.

*  Average Spending by Campaign Responder: $1,001.33
On average, customers who responded to a campaign spent $1,001.33. This figure is significantly higher than the overall average spending, indicating that campaign responders tend to be more valuable customers. 

* Long-Term Retention Rate of Campaign Responders: 100.00%
This indicates that all customers who responded to campaigns have been retained over the long term. A 100% retention rate suggests that the campaigns were highly effective in engaging customers and keeping them loyal to the brand.

*  Response Rate by Age Group
- 26-35: 34.43%
- 36-45: 28.93%
- 46-55: 24.05%
- 56-65: 26.48%
- 66-75: 27.17%
- 76-85: 42.06%
The response rate by age group indicates how different age groups react to campaigns. The highest response rate is among the 76-85 age group (42.06%), suggesting that older customers are more likely to respond to campaigns.

* Response Rate by Income Group
- 0-29k: 14.05%
- 30k-59k: 20.52%
- 60k-89k: 38.83%
- 90k-119k: 89.13%
- 120k-149k: NaN
- 150k+: 0.00%
Higher-income groups (90k-119k) show a significantly higher response rate (89.13%), indicating that campaigns are more effective among wealthier customers. The response rate drops to zero for the 150k+ group, which could be due to a small sample size or less interest in promotions. The response rate increases progressively with income, which suggests that campaigns are well-targeted to middle-income customers.

* Response Rate by Marital Status Group
- Absurd: 50.00%
- YOLO: 50.00%
- Widow: 35.06%
- Single: 30.83%
- Divorced: 29.74%
- Married: 25.12%
- Together: 25.00%
- Alone: 33.33%
Marital status influences how customers respond to campaigns. Unusual marital statuses like "Absurd" and "YOLO" have the highest response rates (50.00%), though these are likely due to very small sample sizes. Widowed customers also show a relatively high response rate (35.06%). Married and customers living together have the lowest response rates, suggesting they may be less engaged with the campaigns.

* Response Rate by Education Group
- 2n Cycle: 22.66%
- Basic: 12.96%
- Graduation: 26.44%
- Master: 27.03%
- PhD: 32.51%
Educational background affects campaign responses, with PhD holders having the highest response rate (32.51%). Customers with basic education respond the least (12.96%). The results suggest that more educated customers may be more likely to engage with the campaigns, perhaps due to better alignment of the offers with their preferences or more disposable income.

* Recency (Days Since Last Purchase)
Maximum Recency: 99 days
Churn Rate by Recency Group:
- 0-30 days: 0.00%
- 31-60 days: 51.51%
- 61-90 days: 100.00%
- 91-180 days: 100.00%
Customers who haven’t made a purchase in the last 61-90 days or more have a 100% churn rate, meaning they are very likely to leave. In contrast, customers who purchased within the last 0-30 days have a 0% churn rate, showing they are still engaged. This indicates that recency is a strong predictor of churn.

* Complaints
- Total Complaints: 21
- Number of Customers Who Complained: 2,219
- Total Number of Customers: 2,240
Despite a high number of customers (2,219) who have lodged complaints, the total number of complaints is low (21), which suggests that customers may be raising multiple issues in one complaint. The large number of complaints might indicate dissatisfaction among the customer base, which could be a concern for retention.

* Customer Tenure and Churn Rate (Churn Threshold = 45 Days)
Average Tenure by Churn Status:
Churned (False): 4,052.92 days
Churned (True): 4,061.44 days
Churn Rate: 54.73%
The churn rate of 54.73% indicates that more than half of the customers are at risk of leaving. The average tenure of churned vs. non-churned customers is almost the same, indicating that tenure alone may not be a strong indicator of churn.

* Purchase Statistics
- Total Web Purchases: 9,150
- Total Catalog Purchases: 5,963
- Total Store Purchases: 12,970
- Average Order Value (AOV) for Web: $148.30
- Average Order Value (AOV) for Catalog: $227.57
- Average Order Value (AOV) for Store: $104.63
These statistics show that store purchases are the most frequent, followed by web and catalog purchases. However, the catalog purchases have the highest AOV ($227.57), meaning that customers spend more on average when ordering through catalogs. The lower AOV for store purchases ($104.63) might be due to smaller, more frequent transactions.

* Return on Investment (ROI)
- ROI for Web: 88,065.18%
- ROI for Catalog: 150,998.52%
- ROI for Store: 88,814.83%
The extremely high ROI percentages suggest that the campaigns have been highly effective in generating revenue relative to their cost, with the catalog channel being the most profitable. However, these values may need further validation to ensure they accurately reflect the costs and revenues.

* Relationship Between Campaign and Complaint Response
Cross-Tabulation Between Complaint and Campaign Response:
Complained and Responded: 20.78%
Complained and Did Not Respond: 79.22%
Did Not Complain and Responded: 9.52%
Did Not Complain and Did Not Respond: 90.48%
Customers who complained are less likely to respond to campaigns (9.52% response rate) compared to those who did not complain. This highlights that addressing complaints is crucial for improving campaign effectiveness.
Pearson’s Correlation Between Complaint and Campaign Response: -0.03
A weak negative correlation (-0.03) indicates that there is almost no relationship between complaints and campaign response. This suggests that the fact of complaining does not strongly predict whether a customer will respond to a campaign.

## INSIGHTS
* Age Group: The highest response rates are seen in the 26-35 (34.43%) and 76-85 (42.06%) age groups. The response rate tends to decrease in the 36-65 age range, with a slight increase in the older segment.
* Income Group: Customers earning between 90k-119k have the highest response rate (89.13%), while those earning 0-29k have the lowest (14.05%). Interestingly, the highest income group (150k+) shows no response, possibly due to limited engagement with campaigns.
* Marital Status: Customers with unusual marital statuses ("Absurd," "YOLO") have high response rates, but these are likely anomalies due to small sample sizes. Widowed customers show relatively high engagement, while married and "together" customers have lower response rates.
* Education: The response rate increases with education level, with PhD holders showing the highest engagement (32.51%).
* Recency and Churn: Customers who haven’t made a purchase in the last 61-90 days have a 100% churn rate, indicating that these customers are at high risk of leaving. The churn rate decreases to 0% for those who have made a purchase in the last 0-30 days.
* Tenure and Churn: The average tenure for churned and non-churned customers is almost identical, suggesting that tenure alone is not a strong predictor of churn.
* Complaints: A high number of customers (2,219) have lodged complaints, yet the total number of complaints is relatively low (21). This suggests that complaints might not be sufficiently addressed or resolved.
* Product Spending: Customers spend the most on wines ($303.94 on average) and meat products ($166.95 on average). These categories also contribute the most to total revenue.
* Purchase Channels: Catalog purchases have the highest Average Order Value (AOV) at $227.57, followed by web ($148.30) and store ($104.63) purchases.
* Return on Investment (ROI): Catalog campaigns deliver the highest ROI (150,998.52%), followed by store (88,814.83%) and web (88,065.18%).
* Campaign Response: Campaign response rates are generally low, with the highest being 14.91% for the most recent campaign. However, the long-term retention rate of campaign responders is 100%, indicating that those who do respond tend to remain loyal.
* Complaint Impact: Customers who have complained are less likely to respond to campaigns (9.52% response rate) compared to those who haven’t complained. There’s a weak negative correlation (-0.03) between complaints and campaign response.

## RECOMMENDATIONS
* Age-Specific Campaigns: Develop targeted campaigns for the 26-35 and 76-85 age groups, leveraging their higher response rates. Consider tailored offers or messaging for the 36-65 age group to boost engagement.
* Income-Sensitive Offers: Focus on middle-income customers (60k-119k), as they are more responsive to campaigns. For the high-income segment (150k+), consider personalized, premium offers or exclusive experiences to engage them.
* Marital Status Segmentation: Create campaigns that resonate with single and widowed customers, as they show higher response rates. The low response from married and "together" customers may require more personalized or family-oriented offers.
* Educational Content: Develop content-rich campaigns that appeal to highly educated customers, potentially offering educational materials or experiences that align with their interests.
* Proactive Engagement: Implement proactive engagement strategies for customers who have not made a purchase in 31-60 days, as this period is critical for preventing churn. Personalized reminders, special offers, or loyalty rewards could be effective.
* Complaint Resolution: Enhance the complaint resolution process to address customer grievances more effectively. Follow up with customers who have complained to improve satisfaction and reduce churn.
* Loyalty Programs: Consider developing a loyalty program that rewards customers for frequent purchases, particularly during the 0-30 day window, to keep them engaged and reduce the risk of churn.
* Product Promotion: Focus on promoting high-revenue products like wines and meat through targeted campaigns. Bundle these products with complementary items like fruits or sweets to increase average spending.
* Optimize Channels: Given the high AOV and ROI from catalog purchases, consider investing more in catalog marketing. Enhance the online shopping experience to boost web sales and improve store promotions to increase foot traffic.
* Cross-Selling Opportunities: Utilize the strong correlations between different product categories (e.g., meat and fish) to design cross-selling strategies, encouraging customers to buy complementary products.
* Improve Campaign Messaging: To boost response rates, consider refining campaign messaging, timing, and targeting. Use customer data to tailor offers that better match individual preferences.
* Address Complaints Before Campaigns: Ensure complaints are resolved before launching new campaigns to improve response rates. Acknowledge the resolution of complaints in follow-up communications to rebuild trust.
* Loyalty Campaigns: Given the high retention rate of campaign responders, design loyalty campaigns to maintain engagement and reward repeat customers. Consider offering exclusive deals or early access to new products as incentives.
* Customer-Centric Approach: Utilize segmentation analysis to tailor campaigns that resonate with different customer groups based on age, income, education, and marital status.
* Churn Prevention: Focus on proactive measures to retain customers who are at risk of churning, particularly those with higher recency scores.
* Product and Channel Optimization: Leverage product and channel performance data to maximize revenue and ROI, with an emphasis on catalog sales and high-spending product categories.
* Complaint Management: Improve complaint handling processes to reduce dissatisfaction and enhance the effectiveness of subsequent campaigns.

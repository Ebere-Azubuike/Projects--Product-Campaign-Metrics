# Product-Campaign-Metrics 
**(Comparing Marketing Campaigns against Competitors)**

 
**Click on the link to view the Looker Studio**

_(https://lookerstudio.google.com/u/0/reporting/98a88d43-155b-4f37-8463-41931f93eb15/page/p_somw71f9od)_

# Business Problem
TechTech faces a multifaceted business challenge that demands astute resolution. The core elements of this challenge encompass:

1. Competition Management: TechTech operates in an industry where competition is fierce, with both established giants and nimble newcomers vying for market share. Navigating this competitive landscape requires not only vigilance but also strategic acumen.
   
2. Resource Allocation: In an era of resource constraints, the judicious allocation of marketing resources is critical. Ensuring that every marketing dollar is optimally spent to yield the highest return on investment is an ongoing challenge
   
3. Performance Evaluation: To thrive in a competitive environment, TechTech must continually assess the effectiveness of its marketing campaigns. Understanding how its campaigns perform relative to competitors is crucial for maintaining a strong market presence
   
4. Brand Enhancement: In a marketplace teeming with choices, enhancing brand visibility and positioning is an imperative. TechTech must devise strategies that not only resonate with consumers but also strengthen its brand's foothold in the minds of its target audience.

# Rationale for the Project
In the dynamic realm of Marketing and Sales, assessing campaign effectiveness is pivotal. Here are the top five reasons that emphasize the significance of this project:

1. Competitive Edge: Understanding how TechTech's marketing campaigns fare against competitors will enable the company to maintain a competitive edge.
   
2. Resource Allocation: Efficient allocation of marketing resources based on data-driven insights can significantly enhance ROI.

3. Brand Visibility: By optimizing marketing strategies, TechTech can enhance its brand visibility in a highly competitive market.

4. Customer Engagement: Targeting the right marketing channels and tactics will lead to improved customer engagement.

5. Market Trends: Analyzing external factors and industry trends will provide TechTech with a better understanding of the market landscape.

# Aim of Project
This project has well-defined objectives aimed at addressing the business challenges through LOOKER:

1. Performance Analysis: Evaluate TechTech's marketing campaign performance.

2. Strategy Enhancement: Identify strengths and weaknesses in marketing strategies.

3. Channel Optimization: Determine the most effective marketing channels and tactics.

4. Actionable Insights: Provide actionable recommendations for improving campaign effectiveness.

# Data Description
This case study contains 4 datasets and they are as follows;
_
_**1. Marketing Campaigns Table:**__

Campaign ID (Text): A unique identifier for each marketing campaign. 

Customer ID (Text): A reference to the customer associated with the campaign.

Ad Spend (Currency, e.g., USD): The amount of money spent on the campaign.

Impressions (Number of Impressions): The total number of times the campaign materials were displayed to users.

Clicks (Number of Clicks): The number of times users clicked on the campaign materials.

Conversions (Number of Conversions): The number of desired actions taken as a result of the campaign.

Sales (Currency, e.g., USD): The revenue generated directly attributed to the campaign.

Campaign Start Date (Date): The date when the campaign started. Campaign End Date (Date): The date when the campaign ended.

_**2. Customers Table:**_

Customer ID (Text): A unique identifier for each customer.

Age (Years): The age of the customer.

Gender (Text): The gender of the customer (e.g., Male, Female, Other).

Location (Text): The geographical location of the customer (e.g., City, State, Country).


_**3. Competitor Campaigns Table:**_

Customer Segment (Text): A categorical designation of the customer (e.g., Premium, Regular, New).

Campaign ID (Text): A reference to the campaign in the Marketing Campaigns Table.

Competitor ID (Text): A unique identifier for each competitor.

Ad Spend (Currency, e.g., USD): The amount of money the competitor spent on their campaign.

Impressions (Number of Impressions): The total number of times the competitor's campaign materials were displayed.

Clicks (Number of Clicks): The number of times users clicked on the competitor's campaign materials.

Conversions (Number of Conversions): The number of desired actions taken as a result of the competitor's campaign.

Sales (Currency, e.g., USD): The revenue generated directly attributed to the competitor's campaign.

Campaign Start Date (Date): The date when the competitor's campaign started.

Campaign End Date (Date): The date when the competitor's campaign ended.


_**4. External Factors Table:**_

Date (Date): The date for which the external data is recorded.

GDP Growth Rate (Percentage): The percentage change in Gross Domestic Product (GDP) compared to the previous period.

Inflation Rate (Percentage): The percentage change in consumer price inflation compared to the previous period.

Consumer Sentiment Index (Index Score): An index representing consumer sentiment and confidence.

Industry Trends (Text): A description of emerging trends and developments in the industry.

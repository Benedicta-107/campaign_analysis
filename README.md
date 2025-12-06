# campaign_analysis
Author
Benedicta Ibeawuchi
Data Analyst | Agriculture & Tech Enthusiast
Manchester, UK
🔗 GitHub Profile


Project Overview

A startup company facing funding constraints needed to determine which single marketing campaign to continue running in order to maximise customer acquisition and profit margin.

As the company’s new Data Analyst, I analysed historical order data to evaluate the performance of all campaigns and recommended the one campaign that should remain active.

Tools & Technologies
	•	Python
	•	Libraries: pandas, numpy, matplotlib
	•	Google Colab for analysis
	•	GitHub for version control and project sharing
	•	Excel/CSV data for preprocessing

Dataset Description

File: Order_Data.csv
Column
Description
OrderID
Unique identifier for each order
CustID
Customer identifier
ProductPrice
The selling price of each product
ProductCost
Cost price of each product
OrderQuantity
Number of items purchased
OrderDate
Date of order
AcquisitionSource
Campaign or channel (e.g. Google Ads, Meta Ads, YouTube)
Fraud
Fraudulent flag (Yes/No)

Key Metrics Computed
Metric
Formula
Purpose
Revenue
ProductPrice × Quantity
Measures total sales
Cost
ProductCost × Quantity
Measures total cost
Margin
Revenue − Cost
Determines profitability
AOV (Average Order Value)
Revenue ÷ Orders
Indicates customer spend
Margin %
Margin ÷ Revenue
Measures efficiency
Fraud Rate
Fraudulent orders ÷ Total orders
Measures campaign quality

Analysis Process
	1.	Data Cleaning: Removed symbols (£, $, commas) and converted text to numbers.
	2.	Feature Engineering: Added Revenue, Cost, Margin columns.
	3.	Grouping: Aggregated data by AcquisitionSource to compare campaign performance.
	4.	Visualization: Created bar and line charts showing revenue and trends.
	5.	Scoring: Ranked campaigns using profitability and risk scores.

Google Ads achieved the highest margin and customer volume despite not having the top revenue, making it the most profitable and efficient campaign.

Key Insights
	•	Google Ads is the best-performing campaign with the highest score and zero fraud rate.
	•	Meta Ads and YouTube bring fair traffic but at higher costs and lower margins.
	•	Focused budget allocation to Google Ads will maximize ROI and sustain the company’s growth.

Recommendations
	•	Continue with Google Ads as the main campaign.
	•	Track AOV, conversion rates, and CPA weekly.
	•	Run A/B tests on creatives and landing pages to boost conversion.
	•	Maintain fraud detection monitoring, even if the current fraud rate is 0%.

Visual Outputs
	1.	Revenue by Campaign — Bar Chart
	2.	Weekly Revenue Trends — Line Chart
	3.	Profit Margin % by Campaign

It demonstrates data cleaning, KPI analysis, visualization, and business recommendation skills.

(All charts generated using Matplotlib in the notebook.)

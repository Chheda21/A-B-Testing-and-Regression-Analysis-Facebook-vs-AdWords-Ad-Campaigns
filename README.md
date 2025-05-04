# 📊 A/B Testing and Regression Analysis on Facebook and AdWords Campaigns

# Project Overview
In today's digital landscape, businesses rely heavily on online ads to drive traffic and conversions. This project uses A/B testing and regression analysis to compare the effectiveness of Facebook and Google AdWords ad campaigns. The goal is to determine which platform offers better performance based on clicks, conversions, and cost efficiency.

Through this analysis, I aim to provide insights into which advertising strategy delivers the highest return on investment and user engagement.

# Dataset Description

The dataset contains performance data from two digital advertising campaigns—one run on Facebook and the other on Google AdWords—over the course of one year (2019). Each row represents a single day, totaling 365 daily observations.

It captures a range of key performance indicators (KPIs) for both platforms, allowing for detailed comparative analysis. The primary columns include:

Date: The date of each campaign record

Ad Views: Number of impressions (times the ad was displayed)

Ad Clicks: Number of times users clicked on the ad

Ad Conversions: Number of users who completed a desired action (e.g., purchase, signup)

Cost per Ad: Total amount spent per day on the ad campaign

Click Through Rate (CTR): Percentage of views that resulted in clicks

Conversion Rate: Percentage of clicks that led to conversions

Cost per Click (CPC): Average cost incurred for each ad click

# Key Analyses

Exploratory Data Analysis (EDA): Visual comparisons of clicks and conversions using histograms and scatter plots

Conversion Category Analysis: Grouped days by conversion count to see trends

Cost Per Conversion Analysis: Compared average cost per conversion for each platform

Correlation Check: Checked how strongly clicks relate to conversions

Hypothesis Testing: Statistically tested whether Facebook conversions were significantly higher

Regression Modeling: Built a linear regression model to predict Facebook conversions based on clicks

Trend Analysis: Analyzed weekly and monthly trends to identify high performing time periods

Cointegration Test: Checked long term relationship between cost and conversions for Facebook

# 📈 Results Summary

Facebook has a stronger correlation between clicks and conversions

Facebook’s average Cost Per Conversion was $8.07 vs. AdWords at $24.71

T-test confirmed that Facebook ads had significantly higher conversions

Regression model showed clicks could reliably predict Facebook conversions

Weekly trends show Monday and Tuesday with higher conversions

Cointegration test showed a stable relationship between cost and conversions

# Conclusion

Facebook ads outperformed AdWords across key metrics in this dataset. These findings suggest reallocating more ad budget toward Facebook could drive better returns. Predictive modeling and temporal trend analysis further support Facebook’s efficiency in achieving marketing goals.




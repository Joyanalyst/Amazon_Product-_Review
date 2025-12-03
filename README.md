# AMAZON PRODUCT REVIEW
### Analysis of 12 million product reviews.
### Data Source: [Kaggle.com](https://www.kaggle.com/datasets/kritanjalijain/amazon-reviews)

## Table of Contents
- [Project Overview](#project-overview)
- [Tools Used](#tools-used)
- [Key Techniques](#key-techniques)
- [Data Cleaning Summary](#data-cleaning-summary)
- [Executive Summary](#executive-summary)
- [Insights](#insights)
- [Recommendation](#recommendation)
- [Limitations](#limitations)
- [Conclusion](#conclusion)

## Project Overview
### This project utilizes a publicly available dataset of 12 million Amazon product reviews to conduct a robust, data-driven analysis of e-commerce performance. The primary goal is to deliver actionable strategic recommendations regarding product quality, customer satisfaction, and the effectiveness of current pricing and discounting strategies. This analysis is presented through an interactive Power BI dashboard for executive consumption
### The aim of this project is to:
### •	Understand how review volume influences product ratings.
### •	Evaluate the impact of discount levels on perceived product quality.
### •	Identify which product categories deliver the most customer value.
### •	Pinpoint top-performing products based on satisfaction and engagement metrics.

## Tools Used
### •	 Power BI: Dashboard design, visual storytelling, statistical analysis (weighted Average calculation, Bias visualization), Dax Modelling (SUMX, CALCULATE, DIVIDE), Data Modelling (Fact/Dimension Structure)
### •	MYSQL: Data structuring and aggregation
### •	Excel /Power Query: Data cleaning and transformation

## Key Techniques
### •	Weighted Average Rating (W.A.R.): Adjusts for review count bias.
### •	Tiered Binning: Categorizes review volume and discount levels.
### •	Customer Satisfaction Score: Derived metric based on normalized review sentiment and engagement.
### •	Category Aggregation: Compares performance across product groups.

## Data Cleaning Summary (Excel Power Query)
### •	Removed duplicates based on Product Id
### •	 Filtered invalid ratings and discounts
### •	Standardized category labels
### •	Created review volume and discount tiers
### •	Converted review count to numeric scale

## Executive Summary
### The Analysis reveals that products with higher review volumes tend to have slightly better ratings, suggesting a correlation between popularity and perceived quality. Discount depth does not significantly degrade review scores, indicating that aggressive pricing can coexist with strong customer satisfaction. Among categories, Computers & Accessories and Musical Instruments deliver the most customer value, while Home & Kitchen lags. The analysis empowers stakeholders to make informed decisions about product promotion, pricing strategy, and category investment

<img width="1146" height="651" alt="Amazon Reviews" src="https://github.com/user-attachments/assets/43cd5a0c-87bf-43ae-8813-cc008d7165c4" />



## Insights

### 1.	Discount Depth Impact: Products with low to moderate discounts receive a 4.18 review rating, slightly outperforming those with high discounts at 4.17. This shows that heavy discounting doesn’t guarantee higher satisfaction, and Customers may trust fairly priced items more than heavily discounted ones.
### 2.	Category Value Delivery: Computers & Accessories and Musical Instruments have the highest customer value scores of 385 and 344, respectively, outperforming Home & Kitchen with a 20 value score. This indicates a lower recognition and weak emotional attachment to commodity goods
### 3.	Rating Reliability: Products with higher review volume tend to receive slightly higher ratings (+0.2 increase). This indicates that highly demanded items have stronger customer trust.
### 4.	Products like B01418SSD0 and B01418SX4Y have high ratings of 4.40, large review counts of 42k+,  and a strong satisfaction score of 6-8k, which makes them ideal candidates for promotion.


## Recommendation
### 1.	Promote high volume and high-rated products. These items show consistent quality and strong customer trust.
### 2.	Keep discounts below 50% to avoid devaluing the product. 
### 3.	Audit underperforming categories.  Focus on improving customer experience in Home & Kitchen by enhancing product descriptions, support, and quality assurance.
### 4.	Expand successful categories. Invest in Computers & Accessories and Musical Instruments to capitalize on high satisfaction.


## Limitations
### While the dashboard provides valuable insights into product ratings, review volumes, discount levels, and customer satisfaction, the analysis is constrained by the following missing contexts:
### •	Absence of sentence-level review sentiment: The analysis does not incorporate natural language processing to evaluate the tone or emotion within individual review texts.
### •	Lack of return/refund rate data: Product performance is assessed solely through ratings and satisfaction scores, without visibility into post-purchase behavior such as returns or complaints.
### •	No time-based trend analysis: The dashboard presents a static snapshot, without tracking changes in ratings, reviews, or satisfaction over time.

## Conclusion
### This project demonstrates how raw e-commerce review data can be transformed into a visually compelling narrative that drives business decision-making. Using advanced DAX techniques, combined with statistical corrections (Weighted Average Rating) and custom business metrics (Value_Score), the analysis delivers clear and actionable insights. The resulting Power BI dashboard is a production-ready asset that equips stakeholders with immediate strategies to enhance product performance and refine pricing approaches. By bridging technical rigor with business relevance, the project highlights the value of data analytics in shaping competitive advantage in e-commerce.







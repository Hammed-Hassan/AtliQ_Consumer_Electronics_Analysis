# Consumer Electronic Analysis - Power BI

![Alt text for the image](https://github.com/Hammed-Hassan/AtliQ_Consumer_Electronics_Analysis/blob/main/Front%20Page.png)

#
## Introduction
This project, "Consumer Electronic Analysis," tackles the challenge of declining profitability and competitive pressure by transforming sales data into actionable insights. This project was completed as part of a Power BI projects bootcamp at the online school Codebasics. Using a comprehensive Power BI dashboard, the analysis uncovers key trends in sales, customer behavior, and product performance. The goal is to optimize business strategies, improve profitability, and drive strategic growth.


### Skills Demonstrated
Technical Skills
- Data Wrangling and Cleaning
- Statistical Analysis
- Data Visualization
- Customer Segmentation
- DAX (Data Analysis Expressions)

Soft Skills
- Analytical Thinking
- Strong Communication
- Collaboration
- Problem-Solving

#
### Problem Statements
The core objectives of this analysis were to address the following key business questions:
- Sales & Profitability Trends
- Customer Segmentation
- Product Performance Lifecycle
- Market & Seasonal Fluctuations
- Inventory Optimization

#
### Data Sourcing 
This dataset was provided by the online school under strict confidentiality agreements and is classified as proprietary information. As such, it cannot be shared with third parties without explicit authorization.

#
### Data Tranformation & Manipulation
### Data Cleaning with Power Query
- Handling Missing Values: Removing and replacing null and blank data.
- Data Type Correction: Ensuring all columns have the correct format (e.g., text, date, number) and the first row in some cases and promoted as the headers.
- Renaming and Structuring: Renaming columns for clarity and using merges or splits to organize data.

### Measures (DAX)
- Dynamic measures were created with DAX to perform aggregations for key business metrics. These calculations respond to filters and slicers in the report. Few measures are shown below
  
  ![Alt text for the image](https://github.com/Hammed-Hassan/Consumer_Electronics_Analysis/blob/main/CS1.png)
  - Purpose: Display key Metrics in a tabular form.

  ![Alt text for the image](https://github.com/Hammed-Hassan/Consumer_Electronics_Analysis/blob/main/CS2.png)
  - Purpose: Display the net error meaning the forecasted quantity minus actual sales.
    
  ![Alt text for the image](https://github.com/Hammed-Hassan/Consumer_Electronics_Analysis/blob/main/CS3.png)
  - Purpose: Total net sales comapared to thesame quantity from the previous year.
  
#
### Data Modelling 
A star schema was implemented to structure the data for efficient analysis. This model consists of a central fact table connected to various dimension tables. This design ensures optimal performance and makes it easy to filter and analyze data across different dimensions.
![Alt text for the image](https://github.com/Midoford/AtliQ-Consumer-Electronics-Analysis/blob/main/1.png)
![Alt text for the image](https://github.com/Midoford/AtliQ-Consumer-Electronics-Analysis/blob/main/2.png)


# 
### Dashboard Design
### Finance View
![Alt text for the image](https://github.com/Midoford/AtliQ-Consumer-Electronics-Analysis/blob/main/3.png)
### Sales View
![Alt text for the image](https://github.com/Midoford/AtliQ-Consumer-Electronics-Analysis/blob/main/4.png)
### Marketing View
![Alt text for the image](https://github.com/Midoford/AtliQ-Consumer-Electronics-Analysis/blob/main/5.png)
### Supply Cahin View
![Alt text for the image](https://github.com/Midoford/AtliQ-Consumer-Electronics-Analysis/blob/main/6.png)

# Live Dashboard - [link](https://app.powerbi.com/view?r=eyJrIjoiOWViY2ZiYTEtNDcxMi00ZGUxLTljNDAtM2VmMTdkY2EwOTZhIiwidCI6IjAwMGRiMTM4LTRjODAtNDc0MC04NDY4LTFiYmMxN2Y5ZTNlYSJ9)

### Insights
The analysis revealed several key insights:
- Financial Performance: Our net sales have experienced explosive growth, skyrocketing from $111.37M to $3.74B in just four years. However, this growth was accompanied by a concerning initial decline in Gross Margin %, which only saw a modest recovery in 2022.
- Channel Performance: The Amazon sales channel is our largest revenue driver, generating $496.88M in Net Sales. Despite this, its Gross Margin of 36.78% is significantly lower than other channels like Neptune (46.70%) and AtliQ Exclusive (46.01%). This suggests a need to re-evaluate our strategy with Amazon.
- Product Categories: The Notebooks category is the top performer, accounting for $1,580.43M in Net Sales. All product segments, however, maintain a very consistent Gross Margin % between 38.01% and 38.45%, indicating stable profitability across the board.
- Overall Profitability: Despite the high growth in sales, the company recorded a total net profit loss of -$522.42M (-13.98%), with all regions being unprofitable.

#

### Conclusion & Recommendation 
Conclusion
- I noticed net sales have experienced explosive growth, but this was accompanied by a concerning decline in Gross Margin %, which suggests a profitability challenge. All regions currently show a net profit loss.
- I noticed too that While Amazon is our top revenue driver, its gross margin is significantly lower than other channels, indicating a need to re-evaluate our channel strategy.
- I also noticed the "Notebooks" category dominates sales, but all product segments maintain a highly consistent gross margin, suggesting that while the product mix is performing well, profitability issues lie elsewhere.
- Also the dashboard reveals significant seasonal sales patterns and allows for an assessment of inventory levels against sales velocity.

Recommedation
- Optimize High-Volume Channels: Investigate the low Gross Margin % for the Amazon channel and explore strategies to improve profitability, such as price adjustments or reducing fulfillment costs.
- Focus on Profitability: Conduct a deeper analysis to identify the root causes of the net profit loss across all regions and product categories. This is a critical step for sustainable growth.
- Customer-Centric Strategies: Leverage the customer segmentation analysis to create highly targeted marketing campaigns. This will help maximize customer lifetime value and retention.
- Strategic Inventory Management: Use the seasonal and sales velocity insights from the dashboard to optimize inventory levels. This will help minimize costs associated with overstocking and prevent lost sales from stock-outs.

# 

![Alt text for the image](https://github.com/Hammed-Hassan/AtliQ_Consumer_Electronics_Analysis/blob/main/istockphoto-1397892955-612x612.jpg)







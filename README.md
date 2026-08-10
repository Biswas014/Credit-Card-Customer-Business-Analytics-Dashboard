# Credit-Card-Customer-Business-Analytics-Dashboard
An interactive Power BI dashboard that analyzes weekly credit card performance through customer spending behavior, profitability metrics, credit limits, credit utilization, revolving balances, and delinquency indicators to support better business decision-making.

This two-paged Power BI report helps credit card issuers understand customers spending and revenue patterns while identifying customer segments that may require closer monitoring based on credit utilization, revolving balances, delinquency, income, education, and geographic factors.

## Tech Stack
The dashboard was built using the following tools and technologies:
•	Power BI Desktop: Used to build the interactive report and create visuals.
•	Power Query: Used for Data cleaning, transformation, and preparation before analysis.
•	DAX (Data Analysis Expressions): Used to create measures, calculated columns and conditional logics.
•	Data Modelling: Relationships established between customer, credit card transaction, and state tables to support analysis and filtering across the report.
•	SQL (Structured Query Language): Used for writing queries to create tables and inserting records
•	PostgreSql: Used as the relational database for storing the project data and serving it as a data source for Power Bi.

## Data Source :- 
Rishabh Mishra - Youtube

Contains data for more than 10,000 credit card customers during 2023, including customer demographics, income, occupation, geographic information, credit card types, transaction activity, utilization, revolving balances, interest earned, and delinquency indicators.

## Highlights :-

### Business Problem – 
Credit card issuer generates millions as revenue, but they are lacking to compare revenue, utilization and delinquency changes week over week and customer wise.
Key questions such as: 
Which customer segments generate the highest transaction amounts, and where are they located? Which weeks recorded the highest transaction activity? Which expense categories account for the highest transaction amounts? Which card categories perform best in terms of spending, revenue, and delinquency? Is higher interest earned associated with larger revolving balances? 

### Goal of the Dashboard – 
To provide a weekly view of customer spending, revenue indicators, credit utilization, revolving balances, and delinquency patterns. The report helps identify high-performing customer segments, weeks with elevated transaction activity, major sources of revenue, and customer groups that may require closer credit-risk monitoring.

The report consists two pages 
#### 1.	Customer Spending & Revenue –
Displays revenue indicators derived from transaction amounts, interest earned, and annual fees across customer segments and weekly trends.

Some Key insights from this page.

•	Total revenue indicators reached $55M in 2023, comprising $44.5M in transaction amounts, $7.8M in interest earned, and the remaining amount from annual fees. 

•	Male spent more than females approx. 30M whereas female spent 25M.

•	California, Texas, and New York recorded the highest transaction amounts among U.S. states. 

•	Platinum cardholders generated the lowest transaction amount among the card categories.

#### 2.	Credit Risk Indicators –
Displays the potential risks come from shifting dues to next months or average utilization rate affects becoming delinquent account or not on the basis of customer’s financial conditions and time.

Some key insights from this page – 

•	Customers with higher revolving balances tend to generate higher interest earned, indicating a strong association between revolving balances and interest revenue. 

•	Higher credit limits were not associated with higher delinquency rates in the customer data. 

•	Government employees, self-employed customers, and retirees collectively accounted for approximately 20% of all delinquent accounts. 

•	The average credit utilization ratio was 27.5%, while approximately 6.1% of accounts were delinquent, indicating that delinquency was concentrated among a relatively small proportion of the customer base. 

•	Customers with existing personal loans show almost similar delinquency rate against average utilization ratio compared with customers without personal loans. 

•	Customers who started taking service during July–December recorded higher satisfaction scores than those started earlier in the year.

## Conclusions:
The analysis shows that customer spending and revenue indicators vary considerably across customer demographics, geographic regions, card categories, and weeks. While revolving balances are associated with higher interest earned, higher credit limits alone do not appear to correspond with higher delinquency in the observed data.

## Screenshots:
How the report looks like - 

Customer Spending and Revenue

 ![Dashboard Preview](https://github.com/Biswas014/Credit-Card-Customer-Business-Analytics-Dashboard/blob/main/Screenshots/Customer%20Spending%20%26%20Revenue.JPG
)

Credit Risk Indicators

![Dashboard Preview](https://github.com/Biswas014/Credit-Card-Customer-Business-Analytics-Dashboard/blob/main/Screenshots/Credi%20Risk%20Indicators.JPG
)

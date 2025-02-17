# The Bureau of Transportation Statistics (BTS) Data Analysis in Power BI
## The_Bureau of Transportation Statistics (BTS) Data Analysis in Power BI
## WHY POWER BI?
 Power BI offers powerful data visualization, interactive dashboards, and seamless data integration from multiple sources. Its user-friendly interface, advanced analytics, automation, and real-time reporting make it ideal for uncovering freight movement patterns, identifying inefficiencies, and generating actionable insights for better decision-making in transborder freight analysis.

 ## USING THE CRISP-DM METHODOLOGY---
 CRISP-DM ensures a structured, repeatable approach to data analysis. It helps analysts extract meaningful insights while aligning findings with business needs.
 ## THE STEPS FOLLOWED INCLUDE:
 
## 1. Business Understanding
The objective of this analysis is to gain insights into transborder freight transportation between Canada and Mexico. The study identifies trends in freight charges, trade types, and modes of transport to provide recommendations for optimizing logistics and cost efficiency.

## BUSINESS PROBLEMS AND PROJECT OBJECTIVES
Transborder freight transportation plays a crucial role in international trade, impacting economies, supply chains, and logistics efficiency.
This analysis focuses on data from the Bureau of Transportation Statistics (BTS) to uncover patterns, inefficiencies, and trends in freight movement across borders. 
By leveraging data-driven insights, we can improve operational efficiency, reduce environmental impact, and enhance decision-making in the transportation sector.

The goal is to analyze freight data to identify inefficiencies, trends, and opportunities for BTS. Here are seven key analytical questions:


## 1 What are the top transportation modes used for freight, and how have they changed over time?
This will help understand the primary means of trade transportation.

## 2️ Which regions have the highest freight movement, and how does volume fluctuate seasonally?
## 3 Which US states export the highest volume of goods to Canada and Mexico?
By grouping data by USASTATE and COUNTRY CODE, you can analyze the key trade contributors.
What is the distribution of exports to Canada vs. Mexico based on transportation mode?


## Economic Disruptions & Safety
6️ How have recent economic or policy changes (e.g., trade agreements) affected freight movement?
7️ What are the most common causes of freight-related safety incidents, and how can they be minimized?

### ANALYTICAL QUESTIONS

### Freight Movement Patterns
## 1 What are the most common modes of transportation (DISAGMOT) used for exports from each US state?
This will help understand the primary means of trade transportation.

## 2 Which US states export the highest volume of goods to Canada and Mexico?
By grouping data by USASTATE and COUNTRY CODE, you can analyze the key trade contributors.

## 3 What is the distribution of exports to Canada vs. Mexico based on transportation mode?
This will provide insights into which transportation methods are preferred for each country.

## 4 Which Canadian provinces and Mexican states receive the highest number of exports?
A breakdown of CANADIAN PROVINCE and MEXICAN STATE can show the most frequently receiving regions.

## 5 What commodities (COMMODITY2) are most commonly exported, and how do they vary by transportation mode?
Helps in understanding which goods rely on air, truck, or vessel transport.

## 6 Are there any trade patterns or seasonal trends in exports based on the year and month (if available)?
This is to analyze how exports fluctuate over time.

## Operational Inefficiencies
## 7 Where are the most congested freight routes, and how do delays vary by transportation mode?
## 8 Which infrastructure elements (ports, highways, railways) are underutilized or overburdened?



## 2. Data Understanding
The dataset wasan initial zipped folder, which was made up of 5 different folders. Each folder contained 5 datasets for the years, 2020 to 2024, with about 4 files of dataset each for each month. It contained records of freight transactions categorized by country, trade type, transport mode, and freight charges.
It is made up of 
## 14 columns and 4,179,119 rows

Among the Various files for each month were:
Dot_1
Dot_2

## Key attributes include:
Country Code (Canada, Mexico)
Year and Month
Trade Type (Import, Export)
Transport Mode (Truck, Rail, Air, Vessel, Pipeline)
Freight Charges
Ship Weight


3. Data Preparation
Data cleaning: Removed null values and standardized column names.
Data transformation: Aggregated values by year, mode of transport, and trade type.
Feature engineering: Created additional calculated fields for better visualization.

4. Modeling

Built interactive dashboards in Power BI to visualize:

Freight charges by transport mode

Yearly trends in trade volume and charges

Import vs. Export trade distribution

Country-wise freight charge comparisons

5. Evaluation

The model accurately represents trends and patterns in transborder freight transport.

Insights extracted include:

Truck transport dominates the trade, contributing to congestion and higher costs.

Rail and air freight have significantly higher charges but lower volumes.

Canada has higher freight charges than Mexico.

6. Deployment

The Power BI dashboard is the final deliverable, designed for decision-makers to analyze freight data efficiently.

Recommendations include:

Improving rail infrastructure to reduce costs.

Enhancing road transport tracking systems for better efficiency.

This analysis serves as a foundation for improving transborder trade logistics and optimizing transportation costs.


# Restaurant Data Analytics
A restaurant analytics project using real world restaurant data to guide business decision making

### Business Questions

**Main**
1. What are the top selling products and worst selling products within a given time range?
2. How do certain events affect product sale in terms of quantity sold?
    * Holidays and special events
    * New menu and price changes
    * Social media activity
    * Lockdowns and quarantine
3. Is there a correlation between month of the year to quantity sold for a certain product?
4. Does season or even weather affect product sales?
    * Do certain products go up/down/stay neural in quantity sold during X season/weather? 
    * How does the change in sale or lack thereof compare to the year and the whole dataset?
5. Some products aren't in the menu anymore, is it possible that the removal of these products were badly decided in terms of how these products were selling during their lifetime?
6. Determine price elasticity - understand customers’ sensitivity to price changes
7. The establishment allows custom sales. Are there any popular custom products that could be added to the menu?
8. Is it possible build a model that can reliably predict product sales?

**Advanced**
1. Of all top n best selling products, how many are also being sold in top rated restaurants (of similar cuisine) 
    * in the local area
    * in the country
    * Of all these top products that are also being sold at top restaurants, how do they rank in their respective restaurants? (This might not be straightforward to answer as data is needed from different establishments)

#### Implications
* Menu optimisation
* Stock optimisation
* Save money
* Understand the business better

## Data Collection
Dataset was collected from a restaurant's Point of Sale in **daily** format consisting of 
a file for all the products sold on each day.

Data that can be used to identify the restaurant itself were either removed or replaced.

Stage 1: Collected Annual Data 
    - Annual data is not needed anymore but I learned about the data I will be dealing with
    - I need either daily data or monthly for more granular analysis
Stage 2: Collected Daily Data
    - I started collecting from 01 January 2022 up to 29 Feb 2024, it might be worth collecting 2021 data as well
    - Some days were missing so I need to collect these missing ones if possible

## Data Preparation
- Lowercased text columns
- Introduced new columns and removed some
- Corrected and standardised `category` 

**CURRENT** 
- standardising `name`
- 

## Exploratory Data Analysis
SOON

## Modeling
SOON

## Findings
SOON

## Learnings, Success, and Impact
By the end of this project I would hope to have done all of these:
- Initiated data-driven decision making by using raw daily sales data and performing an end-to-end data analytics process; uncovering data-informed insights resulting to more efficient use of resources by the company
- Utilised Python and Pandas, identifying patterns from raw data to automate data preparation leading to more time spent on data analysis
- Provided client of various improvements to their PoS system leading to better data quality and reduction of data cleaning times
- Presented data visualisations to client, effectively communicating insights derived from the visual representations
- Leveraged and evaluated ML models to forecast sales prediction ultimately providing the client with a basis for what factors drives sales and reference for future performance
- (MAYBE) Deployed Dash web application providing stakeholders a unified, user-friendly data exploration platform to further guide client's long-term data-informed business strategies
- (MAYBE) Designed and deployed a relational database system to provide the client with a structured data for future use
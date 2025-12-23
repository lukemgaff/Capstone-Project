# Metro Nashville Housing Affordability (2020�2023)
This capstone project examines changes in housing affordability in Metro Nashville during a period of significant market disruption between 2020 and 2023. The analysis focuses on how access to homeownership changed as home prices rose rapidly while household incomes, housing supply, and mortgage interest rates shifted unevenly across the region.

Using housing market, census, and mortgage rate data, this project evaluates the relationship between median home prices, median household income, housing supply conditions, and borrowing costs. In addition to metro-level trends, the analysis explores ZIP-code–level differences to assess whether affordability pressures were evenly distributed or concentrated in specific neighborhoods.

Overall, the project highlights how the combined effects of rising prices, tightening supply, and higher interest rates substantially reduced homeownership affordability in Metro Nashville, with particularly sharp impacts in certain ZIP codes.

---
## Table of Contents
- Dashboard
- Motivation
- Questions
- Standardizing the Data
- Problems and Hurdles
- Technologies Used
- Data Sources
- Conclusion
---

## Dashboard

---
## Motivation
This topic is of personal and analytical interest given my own experience navigating the Nashville housing market during this period of volatility. Having purchased a home in Nashville prior to the pandemic and later re-entering the market amid rising prices and higher interest rates, I observed firsthand how dramatically affordability conditions changed in a short period of time.

These experiences motivated me to examine the data behind those changes and better understand the forces driving affordability pressures across Metro Nashville. By analyzing market trends from 2020 to 2023, this project aims to move beyond experience and provide data-driven insight into how and where homeownership accessibility has shifted during one of the most disruptive housing market periods in recent history.

---
## Questions
1. How did median single-family home sale prices in Metro Nashville change between 2020 and 2023, and to what extent did median household income growth keep pace with these price changes?
2. How did housing inventory levels and home sales volume in Metro Nashville change between 2020 and 2023, and how did these market conditions correspond with changes in median home sale prices?
3. How did changes in 30-year fixed mortgage interest rates between 2020 and 2023 influence homeownership affordability for a median-income household in Metro Nashville?
4. Were changes in housing affordability evenly distributed across ZIP codes in Metro Nashville between 2020 and 2023, or did certain ZIP codes experience disproportionately larger shifts in affordability?
---
## Standardizing the Data
Data was standardized to a 2020-2023 annual timeframe. Monthly market indicators was aggregated annually, parcel data was filtered to single-family home sales, and ACS income data was aligned at the ZIP (ZCTA) level using population-weighted averages. A price-to-income ratio was then calculated by dividing median home sale prices by median household income, providing a consistent measure of housing affordability across time and geography.

---
## Problems and Hurdles
- Aligning ZIP codes across datasets
- Interpreting inventory as a market indicator
- Working with multi-year ACS estimates
- Modeling affordability assumptions
---
## Technologies Used
- Python (pandas, matplotlib)
- Power BI
- Jupyter Notebook
- GitHub
---
## Data Sources
- Metro Nashville Parcel Sales Data  
- Redfin Housing Market Data  
- U.S. Census ACS (5-Year Estimates)  
- Federal Reserve Economic Data (FRED)
---
## Conclusion
Between 2020 and 2023, housing affordability in Metro Nashville declined as home prices rose faster than incomes and mortgage rates increased sharply. Affordability pressures varied widely across ZIP codes, highlighting uneven impacts across neighborhoods.

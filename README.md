## Project Overview
This project analyzes single-family housing affordability in Metro Nashville from 2020 to 2023. Using parcel sales, Redfin market data, U.S. Census ACS income data, and mortgage rate data, it evaluates how changes in home prices, incomes, housing supply, and interest rates affected access to homeownership at both the metro and ZIP-code levels.

---
# Metro Nashville Housing Affordability (2020–2023)
Between 2020 and 2023, Metro Nashville experienced significant housing market disruption driven by rapid home price growth, constrained housing supply, and rising mortgage interest rates. During this period, access to homeownership changed dramatically, particularly for median-income households.

This capstone project examines how these forces interacted to reshape housing affordability across the region. While affordability declined at the metro level, the impacts were not evenly distributed. ZIP-code–level analysis reveals substantial variation, with some neighborhoods experiencing far sharper affordability losses than others.

Overall, the findings show that rising prices, tightening supply, and higher borrowing costs combined to significantly reduce homeownership affordability in Metro Nashville, with uneven effects across communities.

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
Interactive dashboard available here:  
[View Power BI Dashboard](https://app.powerbi.com/groups/me/reports/f6dad3aa-e25a-4657-b908-8c3085d5b4e8/c23b36cb9882f7af6e8d?experience=power-bi)
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
All data was standardized to a 2020–2023 annual timeframe. Monthly market indicators were aggregated annually, parcel data was filtered to single-family home sales, and ACS income data was aligned at the ZIP Code Tabulation Area (ZCTA) level using population-weighted averages.

Housing affordability was measured using a price-to-income ratio, calculated by dividing median home sale prices by median household income. This provided a consistent metric for comparing affordability across time and geography.

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
- Metro Nashville Parcel Sales Data from the Nashville Open Data Portal
- Redfin Housing Market Data  
- U.S. Census ACS (5-Year Estimates) imported using an API
- Federal Reserve Economic Data (FRED)
---
## Conclusion
Between 2020 and 2023, housing affordability in Metro Nashville declined substantially as home prices rose faster than incomes and mortgage interest rates increased sharply. These pressures were not evenly distributed, with some ZIP codes experiencing significantly larger affordability losses than others.

The findings highlight how affordability outcomes are shaped by the interaction of prices, incomes, financing costs, and supply conditions rather than any single factor alone.

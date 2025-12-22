# Metro Nashville Housing Affordability (2020–2023)

## Table of Contents
- Dashboard
- Motivation
- Questions
- Normalizing the Data
- Problems and Hurdles
- Technologies Used
- Data Sources
- Conclusion
---
* ## Dashboard
* **Link:** *(Insert Power BI or Tableau link here)*
---
## Motivation
Housing affordability has become a growing concern in many U.S. metropolitan areas, particularly during and after the COVID-19 pandemic. This project examines how housing affordability in Metro Nashville changed between 2020 and 2023, a period marked by rapid home price growth, shifting market conditions, and rising mortgage interest rates.
---
## Questions
1. How did median single-family home sale prices in Metro Nashville change between 2020 and 2023, and to what extent did median household income growth keep pace with these price changes?
2. How did housing inventory levels and home sales volume in Metro Nashville change between 2020 and 2023, and how did these market conditions correspond with changes in median home sale prices?
3. How did changes in 30-year fixed mortgage interest rates between 2020 and 2023 influence homeownership affordability for a median-income household in Metro Nashville?
4. Were changes in housing affordability evenly distributed across ZIP codes in Metro Nashville between 2020 and 2023, or did certain ZIP codes experience disproportionately larger shifts in affordability?
---
## Normalizing the Data
Data was standardized to a 2020–2023 annual timeframe. Monthly market indicators was aggregated annually, parcel data was filtered to single-family home sales, and ACS income data was aligned at the ZIP (ZCTA) level using population-weighted averages. A price-to-income ratio was then calculated by dividing median home sale prices by median household income, providing a consistent measure of housing affordability across time and geography.
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

## Airbnb Los Angeles Analytics Dashboard (2025)

## Project Overview

This project analyzes Airbnb listings in Los Angeles to understand pricing, occupancy, revenue performance, and neighborhood demand. Python was used for data cleaning and KPI creation, and Power BI was used to build an interactive one-page dashboard.

## Business Problem

Airbnb hosts and investors need clarity on:

1. Which neighborhoods generate the most revenue
2. What listing features influence occupancy and price
3. How seasonal demand changes
4. Which property types perform best

The raw data is large and messy, making manual analysis difficult.

## Key Steps Involved

- **Data Cleaning (Python)**: handling missing values, formatting prices, filtering 2025 data.
- **Feature Engineering**: calculating ADR, occupancy rate, estimated revenue.
- **Star Schema Modeling (Power BI)**: dim_listing, fact_reviews, dim_date, kpi_listing.
- **DAX Measures**: Total Revenue, Total Listings, Avg ADR, Avg Occupancy.
- **Dashboard**: KPIs + 6 visuals with interactive filters.
  
## Analysis Performed

- Revenue comparison across neighborhoods
- Occupancy patterns across the city
- ADR differences by property type
- Listing distribution by room type
- Monthly review trends
- Host-level revenue ranking

## Key Metrics

- Total Listings
- Total Revenue
- Average Daily Rate (ADR)
- Average Occupancy Rate
- Total Monthly Reviews

## Insights

- West Hollywood and Venice generate the highest revenue.
- Entire homes/apartments dominate listings and achieve the best ADR.
- Some outer LA neighborhoods show near-full occupancy due to low supply.
- Review activity peaks in summer months.
- A small number of hosts manage most of the high-earning listings.

## Recommendations

- Hosts in high-demand areas can increase ADR confidently.
- Investors should target high-occupancy, low-competition neighborhoods.
- Improve listing photos & amenities in low-performing areas to boost occupancy.
- Apply dynamic pricing during seasonal peaks.

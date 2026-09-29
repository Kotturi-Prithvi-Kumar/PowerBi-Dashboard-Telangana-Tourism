# Interactive Power BI dashboard — Telangana tourism trends with DAX forecasting to 2030
## Project Overview
- This repository contains a comprehensive Power BI Business Intelligence Dashboard analyzing historical tourism patterns across the districts of Telangana, India, using open-source government datasets.

- The project evaluates historical footfall dynamics (2016–2019), isolates seasonal trends, ranks district performance based on domestic-to-foreign visitor ratios, and leverages Advanced DAX Time Intelligence to project tourist footfall and tourism-driven revenue forward to the year 2030.

## Data Architecture & Schema
domestic_visitors(2016-2019): Tracks monthly and annual domestic traveler counts, location metrics, and computed CAGR fields.

foreign_visitors(2016-2019): Tracks international visitor arrivals, country-level allocations, and regional distributions.

Key Dimensions & Measures Included:
district: Administrative boundary tracking (e.g., Hyderabad, Bhadradri Kothagudem, Rajanna Sircilla).

date / month / year: Temporal alignment fields.

visitors: Primary metric aggregating visitor footfall counts.

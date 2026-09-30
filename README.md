# 🗺️ Telangana Tourism Dashboard (Power BI)

> Interactive Power BI dashboard analyzing tourism trends across Telangana districts — with DAX time-intelligence forecasting footfall and revenue through 2030.

![Dashboard](Telangana_Tourism.webp)

## The Problem
How has tourism in Telangana evolved, which districts drive it, and where is it headed? Built for planners who need district-level answers, not state-level averages.

## The Data
Open government datasets (2016–2019):
- `domestic_visitors(2016-2019).csv` — monthly/annual domestic traveler counts with CAGR fields
- `foreign_visitors(2016-2019).csv` — international arrivals and country-level allocations

## Approach
1. **Data modeling** — star schema with district and date dimensions; relationships between domestic and foreign visitor fact tables.
2. **DAX measures** — total footfall, domestic-to-foreign ratios, year-over-year growth, CAGR.
3. **Time intelligence** — DAX time-intelligence functions to project tourist footfall and tourism-driven revenue forward to **2030**.
4. **Visualization** — district map, trend lines, seasonal decomposition, district performance ranking.

## Key Findings
- [Top district by footfall — fill in]
- [Strongest seasonal pattern — fill in]
- [2030 projection headline number — fill in]

## Tech Stack
Power BI · DAX · Power Query · CSV

## Project Structure
```
├── telangana tourism.pbix                          # The dashboard (open in Power BI Desktop)
├── domestic_visitors(2016-2019).csv                 # Source data
├── foreign_visitors(2016-2019).csv                  # Source data
├── Telangana_Tourism.webp                           # Dashboard screenshot
└── telangana-district-map-with-neighbour-state-vector.jpg
```

## How to Run
Open `telangana tourism.pbix` in Power BI Desktop. Refresh against the CSVs if you move them.

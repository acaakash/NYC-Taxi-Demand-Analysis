# NYC Taxi Demand & Operations Analysis

## Problem Statement
This project analyzes New York City taxi trip data to uncover demand patterns, operational inefficiencies, and pricing behavior that can help optimise taxi operations.

## Dataset
- Source: NYC TLC Yellow Taxi Trip Records 2023
- Original size: ~36 million rows across 12 monthly files
- Sampled dataset: ~350,000 rows using hourly stratified sampling

## Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn, GeoPandas
- Jupyter Notebook

## Key Analysis
- Temporal demand analysis (hourly, daily, monthly trends)
- Revenue analysis across time periods
- Geospatial taxi zone demand analysis
- Pricing behavior and fare-per-mile evaluation
- Passenger tipping patterns

## Key Findings
- Peak demand occurs between 5PM–7PM with 23,000+ trips per hour
- JFK Airport, Upper East Side and Midtown are the top 3 pickup zones
- VeriFone charges nearly double for short trips vs Creative Mobile ($17.42 vs $9.79/mile)
- Short trips (0–2 miles) make up 55% of all NYC taxi trips
- Daytime generates 87.91% of total revenue
- Thursday is the busiest day of the week

  ## Business Recommendations
- Deploy maximum fleet during 5PM–10PM on weekdays — peak demand window
- Maintain cab presence at JFK Airport, Upper East Side and Midtown at all times
- Partner with VeriFone for short trips — charges nearly double per mile
- Implement surge pricing on Thursdays and Sundays which naturally command higher rates
- Deploy larger vehicles in outer borough zones where avg passenger count is 2–3.5

## Project Files
- `NYC_Taxi_EDA.ipynb` — Complete analysis notebook
- `NYC_Taxi_EDA_Report.pdf` — Full report with charts and recommendations

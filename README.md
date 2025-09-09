# tableau-visualization 
"the csv data file originally contains more than 1 million rows so for this upload it is customized to contain just few sample row. "
This dashboard explores housing price trends across Seattle zip codes, segmented by bedroom count and temporal revenue patterns. It was designed to help real estate stakeholders — from investors to urban planners — make data-driven decisions about pricing, inventory, and market timing.

“What drives housing price variation across zip codes and bedroom categories — and how can we visualize it for strategic action?”
Key Insights:
- Price scales with bedrooms: From $96K for 1-bed homes to nearly $600K for 6-bed listings.
- Inventory bottlenecks: 3-bedroom listings are surprisingly scarce (only 206), despite being the most desirable family size.
- Zip code disparities: Some areas consistently outperform others in price per square foot — signaling premium demand zones.
- Revenue seasonality: A clear upward trend from February to June suggests optimal listing windows for sellers.

Analytical Techniques
- DAX Measures: Built dynamic KPIs like Bed Occupancy Rate, Average Price per Bedroom, and Weekly Revenue Trends.
- Power Query Cleanup: Replaced null strings, enforced numeric types, and filtered out invalid records to ensure clean aggregations.
- Geo Mapping: Used zip code-level choropleths to highlight pricing hotspots.
- Time Series Analysis: Visualized revenue growth across weeks to uncover seasonal patterns.

 Impact & Use Cases
- For Investors: Identify undervalued zip codes with high growth potential.
- For Sellers: Time listings to peak revenue months.
- For Analysts: Monitor inventory gaps and pricing anomalies.
- For Planners: Understand housing density and affordability trends.

 Next Steps
- Integrate external datasets (e.g. crime rates, school zones) for deeper context
- Predict future prices using regression models
- Automate data refresh with cloud-based pipelines

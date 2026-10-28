# Zomato Data Analysis

## Project Overview
This project explores restaurant data from Zomato to understand restaurant distribution, cuisine trends, ratings, customer engagement, and market patterns. The analysis is presented through an interactive Power BI dashboard.

## Technologies Used
- **Power BI Desktop** — dashboard development, data visualization, report pages, slicers, and interactive analysis.
- **MySQL** — data storage and SQL-based querying/analysis.
- **SQL** — data cleaning, transformations, aggregations, and analysis queries.
- **DAX (Data Analysis Expressions)** — Power BI measures and calculations for KPIs and visualizations.
- **Power BI Theme JSON** — consistent dashboard styling using a Zomato-inspired dark theme.

> Dataset source and file format should be specified here if required for your submission.

## Dashboard Pages
The Power BI report contains four pages:

1. **Zomato Restaurant Analysis Dashboard** — overview KPIs such as restaurant count, average rating, votes, and countries represented.
2. **Cuisine Analysis** — analysis of cuisine categories and related restaurant/rating patterns.
3. **Customer Engagement** — analysis of table booking and customer engagement metrics.
4. **Market & Chains** — comparison of restaurant counts and ratings across countries, plus highly rated restaurant names.

## Key Metrics
The report includes measures such as:
- Total Restaurants
- Average Rating (excluding unrated/zero-rating records where applicable)
- Total Votes
- Countries Represented
- Average Rating by Table Booking availability
- Restaurant counts and country/cuisine comparisons

## Workflow
1. Load the restaurant dataset.
2. Clean and prepare the data using SQL and/or Power BI data preparation.
3. Store and query data in MySQL as part of the analysis workflow.
4. Build calculated measures in Power BI using DAX.
5. Create interactive report pages and visualizations.
6. Apply consistent report styling and validate KPI calculations.

## Project Files
- `Zomato_Project_Final.pbix` — Power BI report.
- `Zomato_Premium_Dark_Theme.json` — custom Power BI theme file, if included separately.
- Dataset and SQL scripts — include these files in the repository if they are part of your submission.

## How to Open
1. Install **Power BI Desktop**.
2. Open `Zomato_Project_Final.pbix`.
3. If Power BI requests a data source or credentials, update the connection settings to match your environment.
4. Review the report pages and use the slicers to explore the data.

## Notes
- Dashboard values depend on the dataset and the report's filters.
- Confirm the data source, refresh settings, and calculations before publishing or submitting.
- Restaurant names should not be interpreted as verified restaurant chains unless the dataset explicitly identifies chain membership.

## Author
Add your name here.

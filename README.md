# Airbnb Pricing & Value Analytics Dashboard

This project was created to help me better understand Airbnb pricing trends across 10 major European cities—Amsterdam, Paris, London, Barcelona, Berlin, Vienna, Lisbon, Rome, Budapest, and Athens—in preparation for my study abroad in Europe during spring 2026. Using SQL and Looker Studio, I analyzed listings to uncover how prices vary and what factors drive pricing differences.

##  Project Overview
The goal is to explore how Airbnb prices vary between weekdays and weekends, and identify key price drivers such as:
- Room type
- Host status (superhost vs. regular)
- Location (distance from city center)
- Guest satisfaction ratings

##  Dashboard
[View Full Dashboard](https://lookerstudio.google.com/s/gEqa_sKLDwU)

##  Tools Used
- **SQL (MySQL syntax)** for querying and transforming data
- **Looker Studio** for building interactive visualizations and maps
- **Excel** for minor data cleaning and merging files

##  Visualizations
- Average price by city and day type
- Superhost vs. non-superhost pricing
- Price by room type
- Price vs. distance from city center
- Heatmap of listing prices by location
- Guest satisfaction per dollar by city

##  Data
Original dataset from [Kaggle - Airbnb Prices in European Cities](https://www.kaggle.com/datasets/thedevastator/airbnb-prices-in-european-cities), merged into two main CSV files.
- `all_weekday_listings.csv`
- `all_weekend_listings.csv`

##  SQL Queries
All SQL queries used to build the visuals can be found in the `/sql` folder.

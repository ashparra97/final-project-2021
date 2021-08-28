# Final Project - Earthquake Prediction
### By Ashley, Jason, Kellen, Kimberly, Rosa

## Summary

We wanted to help build a model that predicts the magnitudes and depths of the next earthquakes. We used AWS in conjunction with the PostgreSQL database for data hosting to hold our original, cleaned, and generated dataset. Using machine learning (KNN and Random Forest), we modeled the datasets, which gave us a good look at predicted results that we visualized with Tableau. For presentation, we created a simple webpage that held the screenshots of our codes and the embedded Tableau snippets. 

## Data Sources
Instead of gathering data ourselves (very counterproductive), we will be using the data collected by USGS in the following formats:

- Earthquake data from USGS:
    - https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_month.geojson
- Earthquake data download from USGS
    - https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_month.csv
- Documentation 
    - https://earthquake.usgs.gov/earthquakes/feed/v1.0/csv.php

## Methods

Data ETL - We used Excel, Python, and Pandas to conduct our initial clean up and transformation. We then loaded onto our data server with SQLAlchemy.
Data Modeling - We used both KNN and Random Forest as our machine learning libraries to model our datasets and generate prediction outputs.
Data Visualization - We used Tableau as our visualization tool to generate all our graphs and charts.
 

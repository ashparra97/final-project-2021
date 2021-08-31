# Final Project - Earthquake Prediction
### By Ashley, Jason, Kellen, Kimberly, Rosa
### [Link to Project Proposal](https://docs.google.com/document/d/1Nt-aJl_EfmWYkahmt6LclemSTxTMJU65x4puOA2B76o/edit?usp=sharing)

## Summary

We wanted to build a model that would predict the magnitude and depth of the next earthquake. We used AWS in conjunction with the PostgreSQL database for data hosting to hold our original, cleaned, and generated dataset. Using machine learning (KNN and Random Forest), we modeled the datasets, which gave us a good look at predicted results that we visualized with Tableau. For our presentation, we created a simple webpage that holds screenshots of our codes and the embedded Tableau snippets. 
## Project Links

[GitHub pages](https://ashparra97.github.io/final-project-2021/)
[Tableau 1](https://public.tableau.com/app/profile/ksquinn/viz/shared/QF7P352R2)
[Tableau 2]
## Data Sources

Instead of gathering data ourselves (very counterproductive), we will be using the data collected by USGS in the following formats:

- Earthquake data from USGS:
    - https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_month.geojson
- Earthquake data download from USGS
    - https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_month.csv
- Documentation 
    - https://earthquake.usgs.gov/earthquakes/feed/v1.0/csv.php

## Methods

- Data ETL - We used Excel (CSV), Python, and Pandas to conduct our initial clean up and transformation. We then loaded onto our data server with SQLAlchemy.
- Data Modeling - We used both KNN and Random Forest as our machine learning libraries to model our datasets and generate prediction outputs.
- Data Visualization - We used Tableau as our visualization tool to generate all our graphs and charts.

## Screenshots

KNN training and testing on the dataset.

![train_test_knn](https://user-images.githubusercontent.com/36454639/131228322-4c06079b-e714-42e6-a9d0-50d289388646.JPG)

KNN predictions.

![prediction_code_knn](https://user-images.githubusercontent.com/36454639/131228349-a631bad0-ce07-4445-8e66-9a1a26ad903e.JPG)

Random Forest training and testing for magnitude.

![random_forest_mag_closeup](https://user-images.githubusercontent.com/36454639/131228597-ac9dc8f9-1682-456b-b9ff-fef4cfa6b756.png)

Random Forest training and testing for depth.

![random_forest_depth_closeup](https://user-images.githubusercontent.com/36454639/131228602-d7b39df1-1835-4d23-a00b-69354cec5e2b.png)
 
 
## Conclusion

Based on the predictions generated by both models (KNN and Random Forest), we are confident that they can handle this type of analysis, especially for magnitude and depths. While the amount of data predicted were small, if given enough time and data points, we can train a better model with even higher accuracy that generates more prediction data.

Future projects that can enhance this further would be finding and creating a model that can predict the time and location of future earthquakes. We may require data that we currently do not have, but we can expand upon it if time permits in the future.

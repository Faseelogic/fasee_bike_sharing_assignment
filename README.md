# BoomBikes Bike Sharing Demand Prediction
Predicting daily bike rental demand for BoomBikes using multiple linear regression and feature engineering.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- BoomBikes, a US bike-sharing company, experienced a sharp drop in revenue due to the Covid-19 pandemic.
- The business problem: Identify key factors influencing daily bike rental demand to guide strategy and meet customer needs.
- The dataset: `day.csv` contains daily rental counts and features such as weather, season, year, month, holiday, weekday, working day, temperature, humidity, windspeed, and user types.

## Conclusions
- The final regression model explains over 82% of the variation in bike demand (R² ≈ 0.84).
- Temperature, weather/seasonal conditions, and time-related variables are the most significant predictors.
- Demand is highest in September and lowest in winter months; holidays see reduced rentals.
- The model generalizes well, with similar R² scores for train (0.845) and test (0.816) sets.
- Recommendations: Targeted marketing in low-demand months, monitor weather trends, strengthen operations in winter, and promote usage on holidays.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python : 3.12.12
pandas : 2.2.2
numpy : 2.0.2
matplotlib : 3.10.0
seaborn : 0.13.2
scikit-learn : 1.6.1
statsmodels : 0.14.5

## Acknowledgements
- inspired by housing model provided in upgrad course
- Data dictionary and assignment structure provided by the course.
- Based on best practices in regression modeling and feature engineering 

## Contact
Created by [Faseehulla] - feel free to contact me!

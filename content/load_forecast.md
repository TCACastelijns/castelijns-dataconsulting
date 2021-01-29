---
weight: 1
title: "Load Forecasting | Thomas Castelijns"
nav_heading: "Forcasting Electricity Demand Case Study"
thumbnail: "load_forecast.jpg"
case_short_title: "Load Forecast"
case_title: "Load Forecast"
case_subtitle: "Congestion Management"
case_description: "Forecasting electricity load of congestion points in the electricity grid by combining data from sensors and weather forecasts."
case_feature_img: "congestions2.jpg"
draft: false
---

# Description
Within the current society we are used to and dependent on a reliable and affordably energy supply. Also, we see an increase of:
- Electric energy production on the customer side, for instance, by installing Photo Voltaic (PV) panels, leading to a bi-directional electricity flow.
- Number of users of electrical vehicles (EVs) leading to more than double the electricity consumption.
- Sustainable production plants leading to a larger share of volatile and less predictable electricity production from the supplier side.

Preventing capacity problems in the electricity grid is one of the main challenges of Dutch Network operators. 
The business needs predictions of electricity demand to select potential congestion areas. 
In these areas flexible load is offered for managing congestions.

Therefore, I worked on:

- Extracting and transforming time series data from sensors.
- Combining this with weather forecasts.
- Engineering of time based features.
- Forecasting the electricity load.

Also monitoring training experiments and model performance is part of the project. 

The end result is a deployed python package in production that generates predictions on a 15-min interval .  
These predictions are used by decision makers to offer flexible load in 

## Responsibilities
Project lead and stakeholder management.

## Tools
Python, Pandas, Snowflake, scikit-learn, MLflow, Docker, Gitlab CI/CD
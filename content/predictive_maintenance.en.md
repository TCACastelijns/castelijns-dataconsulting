---
weight: 2
title: "Predictive Maintenance | Thomas Castelijns"
nav_heading: "Predictive Maintenance Case Study"
thumbnail: "predictive_maintenance.png"
case_short_title: "Predictive maintenance"
case_title: "Predictive maintenance"
case_subtitle: "Preventing Excavation Damages"
case_description: "Predicting costly excavation damages and delivering the results automatically to an operational prevention team."
case_feature_img: "predictive_maintenance.png"
draft: false
---

# Description

Excavation damage are a major concern for utility companies since it lead to:

- Power outages.
- Gas leakages (and safety issues).

Restoring these damages is time-consuming and leads to high costs for society. 
Therefore, it is desired to accurately prevent those damages in advance. 

I worked on:

- Extracting, loading and transforming data such as time, place and polygon of excavation work.
- Combining this with internal utility asset data based on spatial geometries.
- Engineering of features such as complexity of excavation, number of assets in excavation area and the resonsible excavator
- Predicting the probability of excavation damage by a trained Machine learning model.

The end result is an automatically scheduled pipeline, on a daily basis that generate predictions for the outdoor prevention team.

## Responsibilities
Project lead and stakeholder management.

## Tools
Python, Pandas, scikit-learn, XGBoost, Oracle Geometries, AWS ECS, Docker, Gitlab CI/CD, Airflow.
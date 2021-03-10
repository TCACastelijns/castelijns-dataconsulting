---
weight: 2
title: "Preventief onderhoud | Thomas Castelijns"
nav_heading: "Preventief onderhoud Case Study"
thumbnail: "predictive_maintenance.png"
case_short_title: "Preventief onderhoud"
case_title: "Preventief onderhoud"
case_subtitle: "Voorkomen graafschades"
case_description: "Het identificeren van de meest risicovolle graafwerkzaamheden in het gas en elektriciteit netwerk."
case_feature_img: "predictive_maintenance.png"
draft: false
---

![](/img/predictive_maintenance.png)

# Beschrijving
Graafschades zijn een van de grootste kosten posten voor Nederlandse nutsbedrijven, omdat het leidt tot:

- Stroom onderbrekingen
- Gas lekken en de bijbehorende veiligheidsissues

Het herstellen van deze schades is tijdrovend en leidt tot hoge kosten voor de maatschappij.
Daardoor, is het gewenst om deze schades te voorkomen.

In dit project heb ik gewerkt aan het:

- Ophalen, Transformeren en Laden (ETL) van de data zoals het tijdtip, de plaats, het graaf gebied en de soort werkzaamheden.
- Combineren van deze informatie met interne asset data op basis van geometrische koppelingen.
- Engineeren van variabelen zoals de complexiteit van het graafgebied, het aantal assets in het gebied en de verantwoordelijke grond roerder.
- Voorspellen van de kans op graafschades o.b.v. een getraind machine learning model.

Het eind resultaat is een tool die automatisch, op dagelijkse basis voorspellingen genereert voor het preventie team.

## Verantwoordelijkheden
Team lead en stakeholder management.

## Tools
Python, Pandas, scikit-learn, XGBoost, Oracle Geometries, AWS ECS, Docker, Gitlab CI/CD, Airflow.
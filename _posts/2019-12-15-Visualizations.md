---
title: "Visualizations"
date: 2019-12-15
published: true
excerpt: "Embedding interactive charts on static pages using Jekyll."
folium-loader:
  folium-OD: ["charts/ODvolume.html", "400"]
hv-loader:
  holoviews-Total-Airfare: "charts/totalprice_byyear.html"
  holoviews-Total-Frequencies: "charts/Total_frequencies_byyear.html"
  holoviews-Departures-Dest-State2: "charts/Departure_DestState.html"
  holoviews-Departures-Origin-State2: "charts/Departure_OriginState.html"
  holoviews-Top-Carriers: "charts/Top5carrier_byyear.html"
  holoviews-Scatter-Plot: "charts/price_dist_plot.html"
  holoviews-percent-errors1: "charts/Prediction_pcterror_byOD(Unit_Price).html"
  holoviews-price-error: "charts/pcterror_byyear.html"
toc: true
toc_sticky: true
---

## Total Airfare

Unsurprisingly, the total money spent on airfare rose steadily over time. Growth was stagnant, however, from 2014 to 2017.

<div id="holoviews-Total-Airfare"></div> 

## Total Frequencies by Year

In terms of flight volumes, the most popular times to fly during the year are early summer and the winter holiday season. January through March are the slowest times of year.

Flight volumes have risen steadily over the study period, but unlike total receipts from airfare, growth continued between 2014 and 2017.

<div id="holoviews-Total-Frequencies"></div> 

## Departures by Destination State

The vast majority of flights are concentrated in a minority of states.

<div id="holoviews-Departures-Dest-State2"></div> 

## Departures by Origin State

Compared to the beginning of the decade, flights are spread relatively more evenly among the states (except for California).

<div id="holoviews-Departures-Origin-State2"></div>

## Top 10 Destination Airports

Each of the top 10 destination airports are major hubs.

![Top 10 Destination Airports]({{"/charts/top10dest.png" | absolute_url}})

## Flights by Top 5 Carriers

Delta began and ended the decade as the airline operating the greatest number of flights. Note that the sudden increase in American Airlines flight volumes in 2014 coincides with the airline's merger with US Airways.

<div id="holoviews-Top-Carriers"></div>

## OD Volumes

Explore the flight volumes between Origin and Destination pairs with the map below.

<div id="folium-OD"></div>

## Ticket Price vs. Flight Distance

This scatterplot shows the relationship between Ticket Price, our dependent variable, and Flight Distance, one of the independent variables in our model.

<div id="holoviews-Scatter-Plot"></div>

## Correlation Matrix for the Model

Below is the correlation matrix for the continuous variables in our model. Other than fuel price and GDP, our explanatory variables did not have much collinearity.

![Correlation Matrix]({{"/charts/correlation.png" | absolute_url}})

## Final Model Prediction Explorer

The widget below allows you to explore the outputs and errors from our model across specific OD pairs and years.

Note that we struggled to embed this properly, but it can be viewed as a standalone file by downloading [this link](https://github.com/CPLN-Flight-Control/Airline-Ticket-Price-Prediction/raw/master/charts/Prediction_pcterror_byOD(Unit_Price).html).

<div id="holoviews-percent-errors1"></div>

## Percent Error by Price

Our model had large errors and needs additional tuning. It performed especially poorly on lower cost tickets.

<div id="holoviews-price-error"></div>

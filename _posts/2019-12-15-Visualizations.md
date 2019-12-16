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
toc: true
toc_sticky: true
---

3

## Total Airfare

Made using altair

<div id="holoviews-Total-Airfare"></div> 

## Total Frequencies by Year

Made using altair

<div id="holoviews-Total-Frequencies"></div> 

## Departures by Destination State

Made using hvplot

<div id="holoviews-Departures-Dest-State2"></div> 

## Departures by Origin State

Made using hvplot

<div id="holoviews-Departures-Origin-State2"></div>

## Top 10 Destination Airports

Made using seaborn

![Top 10 Destination Airports]({{"/charts/top10dest.png" | absolute_url}})

## Flights by Top 5 Carriers

<div id="holoviews-Top-Carriers"></div>

## OD Volumes

Made using folium

Volumes map

<div id="folium-OD"></div>

## One Input Variable for our Model

Ticket price as a function of flight distance

<div id="holoviews-Scatter-Plot"></div>

## Correlation Matrix for the Linear Model

![Correlation Matrix]({{"/charts/correlation.png" | absolute_url}})





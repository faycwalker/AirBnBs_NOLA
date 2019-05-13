

```python
title: "Examining Blight and Short Term Rentals in New Orleans"
date: 2019-05-14
published: true
tags: [dataviz, folium]
excerpt: "Examining the relationship between code violations, lien foreclosures, blight demolitions, and AirBnBs in New Orleans"
folium-loader:
  folium-chart-1: ["charts/folium-lien.html", "400"]
  folium-chart-2: ["charts/folium-blight.html", "400"]
  folium-chart-3: ["charts/folium-airbnb.html", "400"]
  folium-chart-4: ["charts/folium-point.html", "400"]
toc: true
toc_sticky: true


This analysis examines the relationship between code violations, lien foreclosures, blight demolitions, and AirBnBs, or short term rentals in New Orleans. 
The following maps first show where there are concentration sof lien foreclosures, blight demolitions, and AirBnB licenses in the city. The fourth map shows
propertes that have AirBnB licenses and those that applied for licences, but were denied, and their violation history. Data for this anlaysis was pulled from the
New Orleans open data portal. 

## Heat map of lien foreclosures

<div id="folium-chart-1"></div>

The heat map shows how well lien foreclosures are dispersed thorughout the city. As the map shows, they are pretty well dispersed, with a particular concentration
in the core of the city. 

## Heat map of blight demolitions

<div id="folium-chart-2"></div>

The heat map shows the dispersion of blight demolitions in the city. The pattern of blight demolitions are very similar to those of lien foreclosures. 

## Heat map of AirBnB Licenses

<div id="folium-chart-3"></div>

The heat map shows the dispersion of AirBnBs licenses given out by the city. While less widespread than  either lien foreclosures or blight demolitions, however
the dispersion is similar to both, with a concentration in the core of the city. 

## Point Map of AirBnBs

The point map below shows properties with AirBnB licenses as well as properties that applied for an AirBnB license combined with thier violation history. The points are
filled in based on their violation history, with INSERT COLOR HERE points indicating properties with active violations and INSERT COLOR HERE points indicating properties with 
inactive violation cases. Hover over the point to see the violation that the property was cited for.  

<div id="folium-chart-4"></div>

As the map shows, there is a relationship between AirBnBs and code violations. Many of the homes with an AirBnB license has had a code violation in its recent history. 
```

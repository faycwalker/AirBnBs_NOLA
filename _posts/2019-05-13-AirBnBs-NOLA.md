
title: "Examining Blight and Short Term Rentals in New Orleans"
date: 2019-05-13
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

---

This analysis examines the relationship between code violations, lien foreclosures, blight demolitions, and AirBnBs, or short term rentals in New Orleans. The following maps first show where there are concentrations of lien foreclosures, blight demolitions, and AirBnB licenses in the city. The fourth map shows properties that have AirBnB licenses and those that applied for licences, but were denied, and their violation history. Data for this anlaysis was pulled from the New Orleans open data portal.

## Heat map of lien foreclosures

<div id="folium-chart-1"></div>

Lien foreclosures occur throughout the city. As the map shows, they are pretty well dispersed, with a particular concentration in the core of the city.

## Heat map of blight demolitions

<div id="folium-chart-2"></div>

The pattern of blight demolitions is very similar to the distribution of lien foreclosures, centered in the French Quarter and surrounding areas, but by no means limited to the city's core.

## Heat map of AirBnB Licenses

<div id="folium-chart-3"></div>

While AirBnB licenses (so approved AirBnBs) are less widespread than  either lien foreclosures or blight demolitions, the dispersion is similar to both, with a concentration in the core of the city.

## Point Map of AirBnBs

The point map below shows properties with AirBnB licenses as well as properties that applied for an AirBnB license combined with thier violation history. Green points are properties with licenses, blue points are properties without licenses. The points are filled in based on their violation history, with red fills indicating properties with active violations and purple fills indicating properties with
inactive violation cases. If it is an active violation you can hover over the point to see the violation that the property was cited for, if it is an inactive violation you can see how many past violations the property has.

There are a couple of key takeaways from this map:
1. Despite the fact that not having any active violations is a requirement for an airbnb license there are still approved airbnbs with active violations.
2. There are a small handful of properties (primarily multi-unit) that are a huge source of violations, with upwards of 200 past violations.
3. Approved AirBnBs are more concentrated near the French Quarter, while AirBnB applications are more distributed throughout the city.

<div id="folium-chart-4"></div>

```

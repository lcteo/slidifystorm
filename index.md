---
title: Welcome to Storms and Other Severe Weather Events Analysis
subtitle: Impacts to the Population and Economy
author: Teo Lye Choon
job: Reproducible Pitch Presentation
framework: io2012
highlighter: highlight.js
hitheme: tomorrow
widgets: bootstrap, quiz, shiny, interactive
ext_widgets : {rCharts: libraries/nvd3}
mode: selfcontained
---

## Storms and Other Severe Weather Events

Storms and other severe weather events can cause both public health and economic problems for communities and municipalities. Many severe events can result in fatalities, injuries, and property damage, and preventing such outcomes to the extent possible is a key concern.

This project involves exploring the U.S. National Oceanic and Atmospheric 
Administration's (NOAA) storm database. This database tracks characteristics of major storms and weather events in the United States, including when and where they occur, as well as estimates of any fatalities, injuries, and property 
damage.

The events in the database start in the year 1950 and end in November 2011. In 
the earlier years of the database there are generally fewer events recorded, 
most likely due to a lack of good records. More recent years should be 
considered more complete.

The year range from the starting year to the ending year can be varied from
the slider knots with the selected event types to observe the populution and 
economic impacts by state as well as graphically by year.

---



<div class="row-fluid">
  <div class="col-sm-4">
    <form class="well">
      <h2 align="center">Population Impact by Year</h2>
      <h3 align="Center">Note : Currently sliderInput not working for year selection</h3>
    </form>
  </div>
</div><iframe src=' assets/fig/nvd3plot1-1.html ' scrolling='no' frameBorder='0' seamless class='rChart nvd3 ' id=iframe- populationImpact ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

---

<div class="row-fluid">
  <div class="col-sm-4">
    <form class="well">
      <h2 align="center">Economic Impact by Year</h2>
      <h3 align="Center">Note : Currently sliderInput not working for year selection</h3>
    </form>
  </div>
</div><iframe src=' assets/fig/nvd3plot2-1.html ' scrolling='no' frameBorder='0' seamless class='rChart nvd3 ' id=iframe- economicImpact ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

---

## Summary

The application will enable the user to experiment with the storm and other severe weather event impacts to both population and economy. 
* Across the United States, the top 3 events that are most harmful with respect to population health are 
    - Tarnado 
    - Excessive Heat
    - TSTM Wind 
* Across the United States, the top 3 events that have the greatest economic consequences are
    - Tarnado
    - Flash Flood
    - TSTM Wind
* From experimenting, the user may be able to arrive at the conclusion that 
Tarnado is the most devastating to the population health and causes the greatest 
economic consequences.

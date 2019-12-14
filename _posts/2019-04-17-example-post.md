---
title: "Prediction of Taxi Demand Using Random Forest"
date: 2019-04-17
published: true
tags: [dataviz, altair, hvplot, holoviews]
excerpt: "This is an example blog post"
toc: true
toc_sticky: true
---

## Introduction

Random forest regression model is built here to predict the demand of taxi in a certain space unit across the Manhattan. We focus on the demand in each taxi zones, which are roughly based on NYC Department of City Planning’s Neighborhood Tabulation Areas (NTAs). The predcition result provide an overall view of taxi trips made in each taxi zone the next day. Here are some predictors we think that would be related to the number of taxi trips:
- # of **restaurants** in each taxi zone,
- # of **stores* in each taxi zone,
- # of **subway stops** in each taxi zone,
- **Percent of people commuting by taxi** of each taxi zone,
- **Median income** of each taxi zone.
- whether **rain or not** on the day when trip was made
- **Mean temperature** of the day when trip was made
- Is the day when trip was made **weekend**?

## Abandoned Cars

Below, we show the distance between residential sales and the average distance to the 5 nearest 311 calls for abandoned cars.

![distances-abandoned-cars]({{ site.url }}{{ site.baseurl }}/assets/images/distance_to_abandoned_cars.png)

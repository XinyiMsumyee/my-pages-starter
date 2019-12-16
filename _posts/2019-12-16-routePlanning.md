---
title: "Route planning tool built on dash + foilum"
date: 2019-12-16
published: true
tags: [dataviz, dash, folium]
excerpt: "This is the introduction of route planning tool."
toc: true
toc_sticky: true
---

## Introduction

This is a dashboard created by using `dash` and `folium`. The limitation is the selection of destination for users is limited by dropdown list, which should have been a text input. Also, we fail to deploy it by Heroku and could only run the app locally.

## User guide

This app enables user whose origin is times square to select their destination from the dropdown list. The destination could be:
- Museum of Arts and Design
- Empire state building
- New York Hilton Midtown
- Pennsylvania station
- Grand Central Terminal
- Trump tower

Here are two example:

![table]({{ site.url }}{{ site.baseurl }}/assets/images/routeplanning1.png)

![table]({{ site.url }}{{ site.baseurl }}/assets/images/routeplanning2.png)

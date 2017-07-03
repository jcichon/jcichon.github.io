---
title: 'Suwannee Hydrology'
subtitle: 'Santa Fe River near Hildreth'
author: "James Cichon"
job         : 6/23/2017
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit: slidify::knit2slides
---

## USGS River Discharge

1. Use readNWISdv function from dataRetrieval library to connect to the NWIS server
2. Download daily readings for river discharge for any station from any start date
3. Create interactive plot using plotly

--- .class #id

## Santa Fe River Discharge in cubic feet per second



<iframe src="sf_plot.html"> </iframe


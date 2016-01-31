---
title       : Unemployment in Europe Explorer
subtitle    : Developing Data Products Course Project
author      : Alfredo Parreño
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : standalone # {standalone, draft}
knit        : slidify::knit2slides
ext_widgets : {rCharts: libraries/nvd3}
---

## Dataset

The aplication is based on the data collected by [Eurostat](http://ec.europa.eu/eurostat).
The indicator focuses on the 15 to 74 years old.

The indicator provides a measure of difficulties that people with different levels of education have to face in the labour market and offers a first idea of the impact of education in reducing the chances of being unemployed.

The dataset has been obtained from [link](http://ec.europa.eu/eurostat/web/lfs/data/main-tables#).

--- 

## Education and gender

The education has been divided in the following levels
- Less than primary, primary and lower secondary education
- Upper secondary and post-secondary non-tertiary education
- Tertiary education
- All levels
- No response

While gender is divided in:
- Male
- Female
- Total (Both male and female)

---

## What can you do?


- You can compare the unemployment rates in the european countries by ploting the rates from 2003 to 2014.
There are unemployment data of 39 countries and agrupation of countries.
- You can filter data by sex.
- You can filter data by education.

---

## Interactive graphics
You will get an interactive graphic with the information selected.


<iframe src ='Figure1.html', width = "860px", height = "450px"></iframe>


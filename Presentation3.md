Presentation3
========================================================
author: Daniela Galatro 
date: March 8, 2019
autosize: true



## Developing data product - assignment week 3

The goal of the project is to create a web page presentation using R Markdown that features a plot created with Plotly, and to host the resulting web page on either GitHub Pages, RPubs, or NeoCities.

The plot presented in this assignment includes the homicide rates in Canada from years 1961 to 2017. Source: https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3510006801 section "Download options"


```r
rm(list=ls())
library(plotly)
library(data.table)
library(tidyr)
library(lubridate)
library(zoo)
```

## Data


```r
homicides <- read.csv('C:/Users/CocoCuchi/Desktop/JohnHopkins/DataProducts/Homicides.csv', header=T)
```

##Plot


```
Error in loadNamespace(name) : there is no package called 'webshot'
```

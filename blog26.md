

I am pleased to announce that my second R package, SWMPr, has been posted on CRAN.  I developed this package to work specifically with water quality time series data from the System Wide Monitoring Program (SWMP) of the National Estuarine Research Reserve System (NERRS).  SWMP was established in 1995 to provide continuous environmental data at over 300 stations in 28 estuaries of the United States.  SWMP data are collected with the general objective of describing dynamics of estuarine ecosystems to better inform effective coastal management.  However, simple tools for processing and evaluating the increasing quantity of data provided by the monitoring network have prevented broad-scale comparisons between systems and, in some cases, simple trend analysis of water quality parameters at individual sites. The SWMPr package was developed to address common challenges of working with SWMP data by providing functions to retrieve, organize, and analyze time series data from the monitoring network.  

The development version of this package lives on [GitHub](https://github.com/fawda123/SWMPr).  It can be installed from CRAN and loaded in R as follows:


```r
install.packages('SWMPr')
library(SWMPr)
```


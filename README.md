


# geoChina

[![Build Status](https://travis-ci.org/caijun/geoChina.png?branch=master)](https://travis-ci.org/caijun/geoChina)

A R package for geocoding address by calling the Google or Baidu Geocoding API and coordinate conversions for WGS-84, GCJ-02 and BD-09 geodetic system

## Introduction

In China the digital maps use two main Geographic Coordinate Systems (GCSs), namely GCJ-02 and BD-09, rather than the well known WGS-84 because of information security. geoChina provides functions for the mutual coordinate conversions between those three GCSs. Therefore, when geocoding address or reverse geocoding latitude/longitude location by calling either Google or Baidu Geocoding API, geoChina allows for inputting or outputting the coordinates in the GCS different from the one that Google or Baidu map uses. Besides, function for geocoding IP address is provided.

## Installation

Install the development version from GitHub (`devtools` package is required):

```r
devtools::install_github("caijun/geoChina")
```

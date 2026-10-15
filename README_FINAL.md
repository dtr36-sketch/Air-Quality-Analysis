# Trends of Air pollutants



## Introduction

With growing concern about the state of the environment worldwide and the effects of climate change, government organizations and researchers are paying closer attention to how human activity contributes to natural disasters. This project focuses on one area of environmental study: Changes in the levels of various pollutants and how they are placed on the Air Quality Index (AQI). Using data analytics, we will break down large datasets and present visualizations of key trends, which can help us forecast and inform future actions.

## Background and Motivation

The Allegheny County Health Department (ACHD) is a local government agency in Western Pennsylvania. It oversees a range of public health areas, including daily pollutant readings across the Pittsburgh Metropolitan Area, with each monitoring site having its own ID and location assigned.

I became interested in this topic because of the dangerous pollutant levels I have experienced over the past five years, and I wanted to better understand how pollutant trends develop. I also wanted to challenge myself by working with a dataset independently, without instruction, and drawing a reasonable conclusion from it. This project gave me the chance to expand my analytical skills more broadly.

## Own Findings / Data Analysis


For this project I was set to answer this question:
### How do seasonal patterns differ among pollutants within Pittsburgh across a 10 year period?
I wanted to find out what I can put away from this question
#

This dataset contains pollutant readings recorded daily across Pittsburgh neighborhoods over a period of roughly 10 years. The earliest date in the dataset is January 1, 2016, and I downloaded it on September 10, 2026, so the data spans January 1, 2016 to September 10, 2026, or about 10¾ years.
The dataset originally contained 8 columns and over 87,000 rows.

| Column | Type | Description |
|---|---|---|
| `_id` | integer | Row identifier |
| `date` | datetime | Gives the date of record |
| `site` | string | Gives the site of where the data was recorded |
| `parameter` | string | Title of the pollutant |
| `index_value` | integer | Pollutant level recorded |
| `description` | string | Determining if air is considered Good, Unhealthy, or Very unhealthy |
| `health_advisory` | string | Warning of dangerous air levels |
| `health_effects` | string | Describe health effects from dangerous air levels |



## Results

### PM25 Trends:
![alt text](image.png)

### PM10 Trends:
![alt text](<PM10 Trends.png>)

### CO Trends:
![alt text](<CO Trends.png>)

### Ozone Trends:
![alt text](<Ozone Trends.png>)

### SO2 Trends:
![alt text](<SO2 Trends.png>)

### NO2 Trends:
![alt text](<NO2 Trends.png>)

## Discussion & Recommendation
## Conclusion
## References
* Allegheny County Health Department, "Daily AQI Data", Western Pennsylvania Regional Data Center, September 10, 2026, https://data.wprdc.org/dataset/allegheny-county-air-quality/resource/4ab1e23f-3262-4bd3-adbf-f72f0119108b


# Air Quality Index Data Mining

## Introduction

Recently, air quality has become a concern of many for numerous reasons, mainly personal and environmental health. The United States Environmental Protection Agency (EPA) has been monitoring air quality for many years and has a well-developed system for gathering and recording the data. This project used data mining to make these complicated datasets more useful to the average person. To do this, we created a binary attribute for the average overall air quality.

The data contained 19 attributes such as the number of days with hazardous air quality and the number of days where the levels of the PM2.5 particulates surpassed the healthy threshold. Each tuple represented one US county.

Four attribute selection algorithms were used to select the most informative attributes. From these attribute selections, six algorithms such as Naive Bayes Classifier were used for classification. The results were then compared, and the top performing algorithms were used for application and analysis.


## Technologies
* R 3.4.4
* Weka 3.8.2

## Data
* The 2016 & 2017 AQI by County data from [EPA Air Quality Index](https://aqs.epa.gov/aqsweb/airdata/download_files.html) were used as training & testing data, respectively


## Room for Improvement

* Classify tuples according to non-binary, multi-level scaler values
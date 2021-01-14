# Analyzing-the-Trend-of-the-Used-Car-Deals

## Introduction

[_eBay Kleinanzeigen_](https://www.ebay-kleinanzeigen.de/) is a classifieds section of the German eBay website. In this project, we will use the used cars dataset from _eBay Kleinanzeigen_ to analyze the used cars ads created in Germany between 11th June 2015 and 7th April 2016.

The original dataset uploaded to Kaggle by user [orgesleka](https://www.kaggle.com/orgesleka) is no longer available on Kaggle, but it is still accessible on [data.world](https://data.world/data-society/used-cars-data).

In this project, we use the _modified_ version of the original dataset, which was prepared by Dataquest. The modifications are as follows:
- _50,000 data points_ have been sampled from the original full dataset, which originally contained 370,000 data points.
- The dataset _was dirtied_ slightly — to make it resembles a scraped dataset before data cleaning (the original dataset on Kaggle had been cleaned).

### The Goal of the Project
The goal of this project is to clean the data and analyze the trend of the used car deals.

## Reading the Data and Cleaning the Column Names
We read the `autos.csv` file into *pandas* and assign it to the variable name `autos`. The file could read by using `encoding=Latin-1` instead of the default encoding `UTF-8`.

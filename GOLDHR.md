---
title: "GOLDHR"
author: "GroupVAHAC"
date: "1/26/2017"
output: html_document
---






## Objectives of the project


## Data set
Load the data from Kaggle.com regarding HR analytics in a major US company

https://www.kaggle.com/ludobenistant/hr-analytics



## Descriptive statistics

We show the descriptive statistics of the factors


|                     |   min| 25 percent| median|   mean| 75 percent| max|   std|
|:--------------------|-----:|----------:|------:|------:|----------:|---:|-----:|
|satisfaction_level   |  0.09|       0.44|   0.64|   0.61|       0.82|   1|  0.25|
|last_evaluation      |  0.36|       0.56|   0.72|   0.72|       0.87|   1|  0.17|
|number_project       |  2.00|       3.00|   4.00|   3.80|       5.00|   7|  1.23|
|average_montly_hours | 96.00|     156.00| 200.00| 201.05|     245.00| 310| 49.94|
|time_spend_company   |  2.00|       3.00|   3.00|   3.50|       4.00|  10|  1.46|
|Work_accident        |  0.00|       0.00|   0.00|   0.14|       0.00|   1|  0.35|

We need to scale the data



Notice now the summary statistics of the scaled dataset:


|                     |   min| 25 percent| median| mean| 75 percent|  max| std|
|:--------------------|-----:|----------:|------:|----:|----------:|----:|---:|
|satisfaction_level   | -2.10|      -0.70|   0.11|    0|       0.83| 1.56|   1|
|last_evaluation      | -2.08|      -0.91|   0.02|    0|       0.90| 1.66|   1|
|number_project       | -1.46|      -0.65|   0.16|    0|       0.97| 2.59|   1|
|average_montly_hours | -2.10|      -0.90|  -0.02|    0|       0.88| 2.18|   1|
|time_spend_company   | -1.03|      -0.34|  -0.34|    0|       0.34| 4.45|   1|
|Work_accident        | -0.41|      -0.41|  -0.41|    0|      -0.41| 2.43|   1|


## Dimensionability reduction *(second priority)*

## Cluster Analysis

## Predictive machine learning (artificial stupidity)

## Executive summary and final conclusions

## Including Plots

You can also embed plots, for example:

![plot of chunk pressure](figure/pressure-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

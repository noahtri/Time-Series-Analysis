# Time-Series-Analysis

## Overview

I did the following analysis of Apple and Snapchat stock log return time series as part of a class I took in the Spring of 2024 from the University of Miami in pursuit of my Bachelor of Arts in Mathematics. The class was MTH 643: Statistical Analysis II with Financial Applications taught by Dr. Victor Pestien. Textbooks used in class—and this analysis—were (1) Statistics and Data Analysis for Financial Engineering, with R examples, 2nd edition, by David Ruppert and David S. Matteson, and (2) An Introduction to Statistical Learning, with Applications in R, by Gareth James, Daniela Witten, Trevor Hastie, and Robert Tibshirani, 2nd edition. Formulas and reference codes for the analysis come from these textbooks.

I chose to analyze the stocks of Apple and Snapchat as I hypothesized that there would be a slight positive relationship between them. I thought the relationship would be because Snapchat depends on Apple for access to customers in the Apple App Store, but Snapchat is only a social media while Apple is a broader technology company.

## Files Included

This repository includes the following files:
- `time_series_analysis.Rmd`   (the R notebook file)
- `time_series_analysis.html` (the knitted R notebook script for better viewing)

## Requirements

This project uses R for data analysis and data visualization. R can be downloaded on the official website:

https://cran.r-project.org

The packages used are as follows:

- `quantmod`
- `fGarch`
- `MASS`
- `mnormt`
- `copula`


To install these packages, run the following command in your R console:  

`install.packages(c("quantmod", "fGarch", "MASS", "mnormt", "copula))`  


Set your working directory to your folder containing `time_series_analysis.Rmd`.  

`setwd("path/to/directory")`


To run the R script, execute the following command:  

`source("time_series_analysis.Rmd")`



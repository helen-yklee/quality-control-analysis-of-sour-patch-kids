# Quality Control Analysis Of Sour Patch Kids Project

Hello and welcome to the Quality Control Analysis of Sour Patch Kids Project! This repository contains the Python code and resources for a quality control analysis of Sour Patch Kids gummies. 

## Project Overview

The project examines the differences between batches purchased from three different retailers. As one of the most popular candies in Canada and the U.S. and production ramps up to meet an increasing demand, Sour Patch Kids gummies must maintain consistent product quality including characteristics such as height, weight, color, and visible deformities. This study documents the real-word quality control methods used to analyze the variability among the samples.

## Approach

### 1. Data Collection Methodology

A total of six 150g bags were purchased, with two bags from each retailer, resulting in three batches. Note: it was assumed that the two bags from each retailer were produced in the same batch. 

Two types of data were collected. 

Type 1: Overall bag characteristics were measured: total bag weight, number of gummies, gummy colour proportions in each bag, and the empty bag weight. 

Type 2: Individual gummy characteristics were measured: weight, length, color, and visual deformities. Weight was measured in grams using a kitchen scale and length was measured in centimeters using a ruler. 

### 2. Exploratory Data Analysis (EDA) 

Initial exploratory data analysis revealed significant differences in color distribution. Since each bag contained five different colors (red, orange, yellow, green, and blue), the color red was by far the most frequent, doubling the least frequent color of yellow. Bag 1 displayed a deformity rate of 15.25%, nearly three times the overall average of 5.46%, suggesting potential out-of-control process conditions. Additionally, the Shapiro-Wilk test indicated that neither weight nor length measurements followed a normal distribution. This was further supported by a histogram analysis: weight distributions were slightly positively skewed, while length distributions varied between bimodal and unimodal shapes across different bags.

### 3. Quality Analysis Using Statistical Process Control Tools

X-bar charts, R-charts, and p-charts were used to evaluate weight, length, color distribution, and deformity. Results identified out-of-control points across all batches. Two out of three batches contained out-of-control points for both weight and length while the one batch was stable in weight but out-of-control in length. 

All bags contained samples of substantial variability in weight and size. The most common deformity were abnormally “small” gummies, with “mixed color” gummies in second place. One particular batch was displayed a significantly large quantity of these deformities. Additionally, two bags were underweight, weighing less than the 150g displayed on the package.

### 4. Key Findings

- The inconsistencies suggest underlying quality control issues that could negatively impact consumer satisfaction.
- The manufacturing process of Sour Patch Kids gummies demonstrates variability in color proportions, color mixing, weight, and length, thus indicating out-of-control processes.
- This study is crucial for maintaining product quality which is tied to brand recognition, consumer loyalty, and the company’s reputation.

## Acknowledgements

- Libraries used: 
  - [pandas](https://pandas.pydata.org): A Python library for data analysis.
  - [NumPy](https://numpy.org): A Python library used for working with arrays.
  - [seaborn](https://seaborn.pydata.org): A Python library for statistical data visualization.
  - [SciPy](https://scipy.org): A Python library for scientific computing.  

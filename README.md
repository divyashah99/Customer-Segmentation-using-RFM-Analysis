# Customer Segmentation using RFM Analysis

## Project Overview

This project revolves around leveraging an [eCommerce dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data) to conduct customer segmentation using RFM (Recency, Frequency, Monetary) analysis. RFM analysis is a powerful business technique that groups customers based on their purchasing behavior, facilitating targeted marketing strategies.

## Project Objectives

The main objectives of this project are:
1. To perform comprehensive RFM analysis on the provided [eCommerce dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data).
2. To segment customers based on their RFM scores, revealing valuable insights into customer behavior.
3. To enable the development of focused marketing campaigns and effective retention strategies through the identified customer segments.

## Dataset Information

The dataset encompasses transactions from a UK-based online retail company specializing in unique all-occasion gifts. Spanning from December 1, 2010, to December 9, 2011, it includes transactions from both individual customers and wholesalers.

## Data Cleaning and Inspection

The initial phase involved comprehensive data cleaning, addressing missing values, duplicate rows, and resolving issues related to StockCode and Description mapping. Negative values in Quantity and UnitPrice were also handled.

## RFM Analysis Highlights

RFM analysis was performed by calculating recency, frequency, and monetary values for each customer. The resulting RFM scores were then used to categorize customers into distinct groups such as "Best Customers," "Loyal Customers," "Almost Lost," and "Passerby Customers."

## Customer Segmentation Technique

Advanced K-means clustering was employed for further customer segmentation, considering data distribution and standardization. The Elbow method was utilized to determine the optimal number of clusters, ultimately selecting 4 clusters for segmentation.

## Customer Profiles and Recommendations

Detailed descriptions and actionable recommendations for each customer segment, including "Loyal Customers," "Passerby Customers," "Best Customers," and "Almost Lost Customers." These recommendations are designed to guide businesses in tailoring marketing strategies for enhanced customer retention and satisfaction.

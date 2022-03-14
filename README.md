# amazon_vine_analysis

## Overview
The purpose of this analysis is to identify any bias for Amazon product reviews which stem from the Vine program (paid reviews). This is done by performing ETL on a dataset to put it in a predefined database schema, and by exploring the data using Spark.

The dataset used was for software products from Amazon.

## Results
### Vine Reviews (Paid)
- 531 paid reviews
- 188 five-star reviews
- 35.4% of paid reviews were 5-stars
### Unpaid Reviews
- 40155 unpaid reviews
- 11836 five-star reviews
- 29.5% of unpaid reviews were 5-stars

## Summary
From the above results, it appears that there is bias. Paid reviews tend to have a higher percentage of 5 star reviews versus unpaid reviews.

Further analysis could include getting the average rate of 5-star reviews across a number of product categories, and completing a T-Test to verify that the statistical mean rate of 5 star reviews is different (or the same) between paid and unpaid reviews. 
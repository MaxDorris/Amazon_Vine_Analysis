# Amazon_Vine_Analysis

## Overview

The purpose of this analysis was to use AWS RDS, SQL, and Pyspark to interpret Amazon Vine review data and draw conclusions on the program's impact on product reviews across the marketplace.

## Results

Of the 40,000+ reviews not submitted by submitted by Vine program members, 39% of products were given 5 stars. Conversely, 50% of submissions by Vine product reviewers were given 5 stars. These results are shown below:

<p align="center">
  <img width=auto height="500" src=images/results.png>
  </p>

## Summary

Due to this 12% difference in five-star ratings between unpaid and paid reviewers, by rewarding its most top reviewers Amazon may be increasing their likelihood to give five-star ratings. A t-test comparing the mean rating of sample unpaid and paid reviews would be necessary to determine statistical significance.
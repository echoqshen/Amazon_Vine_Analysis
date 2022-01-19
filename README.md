# Amazon_Vine_Analysis
## Overview of the analysis:
* The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program, a service that allows manufacturers and publishers to receive reviews of their products and determine if there are any biases between Vine members and Non-Vine member's reviews.
* We use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
* We focused on the US reviews for softwares.

## Results:
### Total number of reviews
* Vine reviews

![](https://github.com/echoqshen/Amazon_Vine_Analysis/blob/main/images/vine%20review.png)
* Non-Vine reviews

![](https://github.com/echoqshen/Amazon_Vine_Analysis/blob/main/images/non-Vine%20review.png)

### Total number of 5-star reviews
* Vine reviews

![](https://github.com/echoqshen/Amazon_Vine_Analysis/blob/main/images/5%20star%20vine.png)
* Non-Vine reviews

![](https://github.com/echoqshen/Amazon_Vine_Analysis/blob/main/images/5%20star%20non%20vine.png)

### Percentage of 5-star reviews
* Vine reviews

![](https://github.com/echoqshen/Amazon_Vine_Analysis/blob/main/images/5%20star%20vine%20percent.png)

* Non-Vine reviews

![](https://github.com/echoqshen/Amazon_Vine_Analysis/blob/main/images/5%20star%20non%20vine%20percent.png)

## Summary
* For the software category, 41% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 29%. This describes a positivity bias for reviews in the Vine program.
* We could perform additional analysis on the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.

# Amazon_Vine_Analysis

## Analysis Overview
This project was to analyze Amazon Vine program to see if there is a bias toward favorable reviews from Vine members.\
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin in order to calculate different metrics.\
The dataset that was used was US reviews for video games.

## Resources
- Data Source: [Amazon Review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt), [Video Games Review dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz)
- Software: Google Colab Notebook, PostgreSQL, pgAdmin 4, AWS

## Results
### Total number of reviews
* Vine reviews: 94

* Non-Vine reviews: 40,471 

### Total number of 5-star reviews
* Vine reviews:48 

* Non-Vine reviews: 15,663

### Percentage of 5-star reviews
* Vine reviews: 51.11%

* Non-Vine reviews: 38.70%

## Summary
51% of the reviews in the Vine program were 5 stars reviews and the percentage in the non-Vine reviews is only 39%. This indicates that there could be a positivity bias for reviews in the Vine program.\
Additionally we could look at the data distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.

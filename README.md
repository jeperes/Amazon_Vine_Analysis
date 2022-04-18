# Amazon_Vine_Analysis

## Overview of the analysis: 

The purpose of this project is analyze a amazon vine program to determine if there is a bias toward favorable reviews on amazon. 
The review was made for amazon_us_watches.

## Resources

- PySpark
- Google Colaboratory
- PgAdmin
- Postgres

## Results: Using bulleted lists and images of DataFrames as support, address the following questions:

- How many Vine reviews and non-Vine reviews were there?

![paid_totalreviews.png](https://github.com/jeperes/Amazon_Vine_Analysis/blob/main/resources/paid_totalreviews.png)

![unpaid_totalreviews.png](https://github.com/jeperes/Amazon_Vine_Analysis/blob/main/resources/unpaid_totalreviews.png)

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

![paid5star_reviews.png.jpg](https://github.com/jeperes/Amazon_Vine_Analysis/blob/main/resources/paid5star_reviews.png.jpg)

![unpaid5star_reviews.png](https://github.com/jeperes/Amazon_Vine_Analysis/blob/main/resources/unpaid5star_reviews.png)

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

![paid5star_percentage.png](https://github.com/jeperes/Amazon_Vine_Analysis/blob/main/resources/paid5star_percentage.png)

![unpaid5star_percentage.png](https://github.com/jeperes/Amazon_Vine_Analysis/blob/main/resources/unpaid5star_percentage.png)

## Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

Based on the results, Vine members did not show bias when rating their products considering that the number of 5-star ratings was about 20% less than Non-Vine members (42% vs. 46.4%).
- 31.9% of the reviews for Vine members were rated 5 stars.
- 51.8% of the reviews for Non-Vine members were rated 5 stars.

# Amazon_Vine_Analysis

## Overview of the analysis:

The purpose of this analysis was to use the dataset of an Amazon review and using PySpark, perform an ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Additionally, determine if there is any bias in the review depending if the customer is a paid member for Vine.

## Results:

* How many Vine reviews and non-Vine reviews were there?

Their were a total of 94 Vine review, compared to a total of 40471 non-Vine review.

![]( https://github.com/Kevin-C3923/Amazon_Vine_Analysis/blob/main/Pictures/total_paided_reviews.jpg )
![]( https://github.com/Kevin-C3923/Amazon_Vine_Analysis/blob/main/Pictures/total_unpaided_reviews.jpg )

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

Their were a total of 48 5-stars Vine review, compared to a total of 15663 5-stars non-Vine review.

![]( https://github.com/Kevin-C3923/Amazon_Vine_Analysis/blob/main/Pictures/five_star_paided.jpg )
![]( https://github.com/Kevin-C3923/Amazon_Vine_Analysis/blob/main/Pictures/five_star_unpaided.jpg )

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

The percentage of 5 stars Vine reviews were 51.06%, while percentage of 5 stars non-Vine reviews were 38.70%.

![]( https://github.com/Kevin-C3923/Amazon_Vine_Analysis/blob/main/Pictures/star_percentage_paided.jpg )
![]( https://github.com/Kevin-C3923/Amazon_Vine_Analysis/blob/main/Pictures/star_percentage_unpaided.jpg )

## Summary:

While examing the analysis, it can be determine that there is a slight positivity bias for reviews in the Vine program. This statement was due to the fact that there are more non-Vine reviews compared to Vine reviews, 40471 to 94. As well, the 5-stars reviews percentage are more in favor for Vine reviews, 51.06% to 38.70%. In order to show that there is bias more analysis needs to be done, one analysis that can be done would be to determine if the reviewer actually purchased that said object by using the "verified_purchase" and determine if the reviews are genuine.

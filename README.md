# Amazon_Vine_Analysis
Big Data


# Overview:

The purpose of this analysis is to determine if paid Vine reviews make a difference in the percentage of 5-star reviews.  In this excercise I used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I also used PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset. 

# Results:

  - There were 7,598 Vine reviews and 1,760,004 non-Vine reviews.
  - There were 2,837 5-stars Vine reviews and 873,722 5-stars non-Vine reviews.
  - There was 37.33 percent of Vine reviews were 5-stars and 49.64 percent of non-Vine reviews were 5-stars.

# Summary:

Based on the percentage of 5-stars reviews, there seems to be no bias in Vine reviews.  The non-Vine reviews were much larger than the Vine reviews.  However, to make a conclusion using the percentage value alone might not be accurate.  To ensure that results are interpreted correctly, I would recommend using additional scientific method such as a t-test analysis.  In this case, I would use the two samples t-test, because I want to compare the difference between the two groups to see if it is statistically significant.

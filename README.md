# Amazon_Vine_Analysis
## Overview
The purpose of this challenge was to complete an analysis on Amazon product reviews. There are Amazon Vine members who are required and paid to complete a product review. Non-Vine members however, complete a review at their leisure. During this analysis I used PySpark to complete ETL on a dataset stored in AWS S3 cloud. I then transfered the cleaned data to my pgAdmin database to create SQL tables. These tables are exportable and effectively show clear results. After this analysis I will be able to determine if Vine members have biased reviews versus non Vine members. 
## Results
To better understand the reviews, I filtered the data to show only the relevant information,
![review_df](https://user-images.githubusercontent.com/93167609/155847400-ba7e6d9e-0b6d-4b27-b691-5a38f2a0e1ec.png)

1. How many Vine reviews and non-Vine reviews were there?
* There were 463 Vine members and 25,079 non-Vine member reviews. Vine members only make up 1.65% of total reviews while non-Vine members make up 98.35%.
 
 ![image](https://user-images.githubusercontent.com/93167609/155847766-eaca1d99-9398-4886-bf68-3e6ee1e8e52e.png)


2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
* 202 out of the total 463 reviews from Vine member reviews were 5 stars. 
* 12028 out of the 25079 total non-Vine member reviews were 5 stars.

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
* 43.6% of reviews given by Vine members were 5 stars.
* 47.9% of reviews given by non-Vine members were 5 stars.

## Summary
After analysing both Vine members and non-Vine member reviews, I conclude that there were not any bias shown when giving reviews and rating. 43.6% of Vine members rated products 5 stars while, 47.9% of non-Vine members rated products 5 stars. Since there is a 4.3% decrease in ratings amoungst Vine member, I would assume that Vine members are slightly more objective when giving reviews. However, this is an insignicant difference bringing us back to my original conclusion that the Vine members are unbiased. This anaylsis was completed on reviews of baby products only. In order to gain a more accurate result, an analysis completed on multiple categories would provide a broader view of whether Vine members submitted bias reviews or not. 
 

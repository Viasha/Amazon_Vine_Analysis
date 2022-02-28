# Amazon_Vine_Analysis
## Overview
The purpose of this challenge was to complete an analysis on Amazon product reviews. There are Amazon Vine members who are required and paid to complete a product review. Non-vine members however, complete a review at their leisure. During this analysis I used PySpark to complete ETL on a dataset stored in AWS S3 cloud. I then transfered the cleaned data to my pgAdmin database to create SQL tables. These tables are exportable and effectively show clear results. After this analysis I will be able to determine if vine members have biased reviews versus non vine members. 
## Results
To better understand the reviews, I filtered the data to show only the relevant information,
![review_df](https://user-images.githubusercontent.com/93167609/155847400-ba7e6d9e-0b6d-4b27-b691-5a38f2a0e1ec.png)

1. How many Vine reviews and non-Vine reviews were there?
* There were 463 vine members and 25,079 non vine member reviews. Vine members only make up 1.65% of total reviews while non vine members make up 98.35%. 
 ![image](https://user-images.githubusercontent.com/93167609/155847766-eaca1d99-9398-4886-bf68-3e6ee1e8e52e.png)


2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
* 202 out of the total 463 reviews from Vine member reviews were 5 stars. 
* 12028 out of the 25079 tot non Vine member reviews were 5 stars.
* 
 

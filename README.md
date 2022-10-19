# Amazon_Vine_Analysis

## Overview
The purpose of this analysis is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. In this analysis I will use PySpark to determine if there is any bias towards favorable reviews from Vine members in the Music dataset.

## Results
### Vine Reviews
![image](https://github.com/awill1786/Amazon_Vine_Analysis/blob/main/Resources/Vine_reviews.png?raw=true)
### Non-Vine Reviews
![image](https://github.com/awill1786/Amazon_Vine_Analysis/blob/main/Resources/Non-Vine_reviews.png?raw=true)
### 5-Star Vine Reviews
![image](https://github.com/awill1786/Amazon_Vine_Analysis/blob/main/Resources/Vine_5star_reviews.png?raw=true)
### 5-Star Non-Vine Reviews
![image](https://github.com/awill1786/Amazon_Vine_Analysis/blob/main/Resources/Non-Vine_5star_reviews.png?raw=true)
### 5-star Vine Review Percentage
![image](https://github.com/awill1786/Amazon_Vine_Analysis/blob/main/Resources/Vine_5star_review_percentage.png?raw=true)
### 5-star Non-Vine Review Percentage
![image](https://github.com/awill1786/Amazon_Vine_Analysis/blob/main/Resources/Non-Vine_5star_review_percentage.png?raw=true)
## Summary
With 0% of the Vine Reviews being 5 stars and 63.7% of Non-Vine reviews being 5 stars, it can be determined that there is no positivity bias in the Vine program in regards to the music dataset. An additional analysis that could be explored is the types of reviews that were a verified purchase. 

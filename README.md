# Big Data: Analyzing the Amazon Vine Review Program
A classwork example in which Amazon Vine reviews are analyzed using big data techniques with PySpark, AWS, pgAdmin, and SQL. 

# Overview of Project 
This project will analyze reviews written by memebers of the paid Amazon Vine program. Amazon Vine is a service that allows manufacturers and publishers to receive reivews for products. SellBy, the company that requested this analysis, pays a small fee to Amazon to buy products, then they supply these products to consumers, who in turn review the product on Amazon's website. I have taken a dataset that holds all products that have been tagged as "Beauty" on Amazon's retail site. After filtering the dataset down to hold helpful reviews of products that have 20 or more votes, we created a dataset that holds reviews from verified purchasers and second that holds reviews from unverified purchasers. 

## Purpose
We will analyze whether a review is more likely to have a 5-star rating if the reviewer is a verified purchaser. We will answer how many total Vine and non-Vine reviews there were, how many Vine and non-Vine reviews were 5-stars, and what percentage of Vine and non-Vine reviews were 5-stars. 

---

# Results
![Review total outputs](/Resources/review_totals.png)
*Review Totals*

![5-star Review total outputs](/Resources/5star_review_totals.png)
*5-Star Review Totals*

![Review percent outputs](/Resources/review_percents.png)
*Review Percents*

# Summary
Reviews that came from Vine users are less likely to be 5-stars. Manufacturers who partner with the Amazon Vine program should be wary that reviews will not always be 5-star due to incentives.  

In addition, we could analyze the data further to see the results of 4-, 3-, 2-, and 1-star reviews published by Vine and non-Vine reviewers. Examining if the disparity was present in other star-ratings would solidify my previous statement, that reviews from Vine users are less likely to be 5-stars and manufacturers should be wary of the preceived incentive they are offering.

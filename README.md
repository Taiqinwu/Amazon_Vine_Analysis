# Amazon_Vine_Analysis
* Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

* In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

# Overview of the analysis
* Perform ETL on Amazon Product Reviews
* Determine Bias of Vine Reviews
* In this project, I will perform analysis on the Toys reviews.

## Result
<img width="783" alt="image" src="https://user-images.githubusercontent.com/107168891/194455599-89e77d53-59bb-466a-8a7b-dbe2b994afbc.png">

* Based on the analysis we performed there are a total of 1,203 vine reviews and 58,018 are non-vine reviews. 
* Out of 1,203 vine reviews 410 are 5-star reviews, and out of 58,018 non-vine reviews 28,043 of the reviews are 5-star.
* Therefore, the percentage of 5-star reviews for vine review is 34.08% and for non-vine reviews is 48.33%

# Summary
* One bias is that there are more non-vine reviews than vine reviews, and non-vine reviews have more 5-star reviews than vine review.
* Therefore, vine program is not really effective here because non-vine member had more reviews.
* To further the analysis, we could compare the review accross all stars reviews, and we should have a equal amount of dataset on both vine and non-vine reviews. 

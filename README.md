# Amazon_Vine_Analysis
![Amazon](https://user-images.githubusercontent.com/111723067/210913932-1a4118b0-883e-4ab0-84a6-5928eff971f9.jpg)

# Overview
Analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis to submit to the SellBy stakeholders.

# Results
## How many Vine reviews and non-Vine reviews were there?
![image](https://user-images.githubusercontent.com/111723067/210914651-f179817e-070a-43e0-86ec-88a2ce80a5c6.png)

## How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
![image](https://user-images.githubusercontent.com/111723067/210914866-8f57b700-25c6-4f22-b011-4328f9cd53bc.png)

## What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
![image](https://user-images.githubusercontent.com/111723067/210914963-6668569d-764d-4598-af5c-1a497d7a1d00.png)

# Summary
- Overall, there does not seem to be a bias in reviews when comparing reviews from members of the Vine program and regular customers/unpaid reviewers.
- If there is a difference in reviews between the two groups, it may be most significant in the written reviews and their professionalism. I would be able to complete this analysis by searching for negative and positive keywords of reviews and seeing which group the words correlate with the most. I expect the more straight-forward, harsher negative reviews to be written by unpaid reviewers. 

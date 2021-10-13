# Amazon_Vine_Analysis

--------------------------------------------------

#**Overview of Analysis**

- Analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products.
- In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.

[https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Home_Improvement_v1_00.tsv.gz](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Home_Improvement_v1_00.tsv.gz)

--------------------------------------------------

#**Results**

How many Vine & non-Vine reviews were there

- Vine = 266
- Non-Vine = 38,829

How many Vine & non-Vine reviews were 5 stars?

- Vine = 125
- Non-Vine = 18246

What % of Vine & non-Vine reviews were 5 stars?

- Vine = 46.99%
- Non-Vine = 46.99%

# Analysis code 
![deliverable2.PNG](https://github.com/Bionicbabes/Amazon_Vine_Analysis/blob/main/pics/deliverable2.PNG)

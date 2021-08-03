# Amazon Vine Analysis

## Project Purpose
The purpose of this analysis is to gain any insights on Amazon reviewers who are part of the Vine program, and if there is any positive bias towards them, all while gaining a greater understanding of Hadoop, Spark, and cloud services can help interact with and store Big Data.  

## Resources
- Software: 
	- Spark 3.1.2
	- Google Colab
	- S3 on AWS (Simple Storage Solutions on Amazon Web Services)
	- pgAdmin 4
	- PostgreSQL 13.3
- Data:
 - [Amazon Review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)
 - [Video Games Review dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz)
 
## Results

### Amazon Vine Reviewers and Five Star Reviews

![reviewDF](images/reviewDF.png)

Looking at this DataFrame, we can see the corresponding numbers of reviews for reviewers who are and are not part of the Vine program. Non-Vine reviewers compared to Vine partners had a much greater amount of reviews (135,483 vs 395) and five star reviews (15,663 vs 48). Non-Vine reviewers however, had a slightly lower percentage of five star reviews (11.56% vs 12.15%).

## Summary

Looking at this data, it seems that there may be a slight positive bias towards Vine partnered reviews, however the difference in five star review percentages may be too small to have any statistical meaning. Further analysis with more data and different categories of Amazon reviews will be needed for a more conclusive result.
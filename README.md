# Analyzing Yelp Reviews using AWS and EMR 

In this project I've analyzed 10 Gb of Yelp's dataset from [Kaggle](https://www.kaggle.com/yelp-dataset/yelp-dataset).  <br />
I have used Several features of AWS. First dataset has been downloaded on a local host and then uploaded to S3. Here are links to my S3 buckets: <br />
[Business Dataset](https://sta9760-spark-yelp.s3.us-east-2.amazonaws.com/yelp-dataset/yelp_academic_dataset_business.json) <br />
[User Dataset](https://sta9760-spark-yelp.s3.us-east-2.amazonaws.com/yelp-dataset/yelp_academic_dataset_user.json) <br />
[Review Dataset](https://sta9760-spark-yelp.s3.us-east-2.amazonaws.com/yelp-dataset/yelp_academic_dataset_review.json) <br />
After that I've leveraged EMR for data analysis using PySpark. Here are pictures of Notebook as well as Cluster configurations:

![Image](https://github.com/Adzic/AnalyzingYelpReviews/blob/master/Screen%20Shot%202020-04-29%20at%204.03.37%20PM.png)
![Image](https://github.com/Adzic/AnalyzingYelpReviews/blob/master/Screen%20Shot%202020-04-29%20at%204.04.46%20PM.png)

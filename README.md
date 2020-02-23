# Recommendation Engine in Pyspark
This Repository contains all code and data required for building recommendation engine in pyspark environment. 
The project is built in AWS's EMR CLuster

### 1. Installations

Here's the python packages that were used in exploring the dataset and trainining the recommendation engine:
pandas
matplotlib.pyplot

The AWS's EMR cluster provided the packages for pyspark Environment.
This project was using emr-5.29.0 version 
Here's the EMR Cluster Setup

![image_1](https://github.com/pashalaksamana/pyspark_recommendation_engine/blob/master/img/aws-setup.png)

### 2. Project Motivation

The project aimed to build a recommendation engine that run on big data environment (spark). 
The dataset used here is coming from Amazon S3 that was provided by Udacity Nanodegree Course.
dataset link: s3n://udacity-dsnd/sparkify/sparkify_event_data.json


### 3. File Descriptions

The github repository is consist of data exploration and engine training in jupyter notebook format and html format

### 4. How to Interact with your project

To understand how the orginal dataset and how the training dataset is build on, please open: Exploration Data.ipynb
To understand how the recommendation engine was built in pyspark environment, please open: Music Recommendation Engine.ipynb

### 5. Licensing, Authors, Acknowledgements, etc.

Thanks Udacity Data Science Course for providing the instruction and dataset to build on.
Thanks to Kevin Liao, for suggesting ALS as recommender system that can be applied in Spark Environment and several code that was adapted to this project
https://towardsdatascience.com/prototyping-a-recommender-system-step-by-step-part-2-alternating-least-square-als-matrix-4a76c58714a1

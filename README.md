# Movie-Recommendation-System

# Business Problem
Recommendation system is using variety of recognized areas like Netflix, YouTube and Spotify, Amazon, eBay, Facebook, Twitter many more. Streaming service provider are becoming popular increasingly as user can access thousands of films and television programs by paying minimum subscription fee. Recommendation system is playing great role to user to select movies which are close to their preference.  In this project, we have designed a movie recommender system using cluster-computing framework Spark.

# Problem Statement
* as size of the data are large then how to handle? 
* how to improve performance of the algorithm?

# Dataset Description
Data has been collected from the [MovieLens dataset] (https://grouplens.org/datasets/movielens/latest/). 
Two datasets are used, one contains movie descriptions and others movie rating. 
* There are 9,000 unique movie IDs.
* There are 6000 unique user IDs.
* There are 100,000 ratings. Ratings are on a five star (integral) scale from 1 to 5.
* There is a date on which the movie is rated by the user.

# Technologies and algorithms
## Prerequisites
You need to have installed following softwares, libraries in your machine before running this project.
* Python 3
* Apache Spark 
* IBM Cloud - need a valid acoouct to run your project 

## Built With
* Jupyter-notebook - Python Text Editor
* pyspark.sql - data handling library
* pyspark.ml - Machine learning library

## Algorithms
We have studied two algorithms in Collaborative filtering:
* ALS : A model-based collaborative filtering, which use latent factors to predict missing entries. Alternating Least Squares (ALS) algorithm has been to learn latent factors.
* ALS + bias : Same algorithm but add bias to calculate latent factors.

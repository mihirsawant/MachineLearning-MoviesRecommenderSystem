# Movies_Recommender_System
<img src="Capture3.jfif" alt="Drawing" style="width: 100%;"/>

# Abstract:
In this notebook we are trying to implement a Movie Recommendation System for which we have used Movielens dataset. It is a research is about implementing different algorithms on Movielens dataset and recommending movies to users. Different filtering techniques have been incorporated initially to check how well they perform on the dataset. Collaborative filtering being one of the most widely used technique for recommendation systems is implemented here. These techniques have their own drawbacks which is the purpose of this research project. We have implemented various functions which takes corresponding inputs to determine which movies to recommend against that input.

# Data fields:
This notebook uses 3 CSV files i.e. for users, movies and ratings. There are approximately 6040 users and 3705 movies. The ratings file has corresponding ratings of users for particular movie. The data fields in respective files are as follows:

# Users:
user_id: Id for user
gender: Gender of user
age: Age of user
occupation: Occupation of user
zipcode: Zipcode of user
age_desc: Describe the class of age group
occ_desc: Describe the class of occupation

# Movies:
movie_id:Id for movie
title: Movie Title
genres:Genres in which movie can be categorized

# Ratings:
user_id:Id for user
movie_id:Id for movie
rating:Ratings given by that user to that movie
timestamp:Timestamp when booking was done

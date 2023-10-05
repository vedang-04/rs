# RECOMMENDER_SYSTEM

# Introduction

Building a content-based recommendation system by calculating the item-item interaction from the given data. Inputting the valid NETFLIX name of the Movie or the TV Show will lead to the model making the description of the content-based recommendations.<br>

# Description

The model used for recommendation is a combination of the Tfidf Vectorizer for text-to-vector conversion and then the unsupervised algorithm of Nearest Neighbors was used to find the cosine distance between the vectors corresponding to the movies/TV shows.<br> The recommendations will be based on the minimum cosine distance i.e., maximum cosine similarity between the two movies, a movie, and a TV show or TV show and a TV show.<br>

# Dataset

We used 3 different datasets and then merged them to form the final dataset. All of them are available on Kaggle.<br>
Netflix Movies and Shows: https://www.kaggle.com/shivamb/netflix-shows <br>
IMDB Movies and Shows: https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset <br>
IMDB Ratings: https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset <be>  

They are given in the datasets folder. Use accordingly in the notebook.

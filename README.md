# musicrecommender

Content-based methods are known for their computational efficiency and interpretability. They can also be easily adapted to accommodate new items or users. However, a significant drawback of content-based recommendation systems is that they primarily suggest items similar to those the user is already engaging with, such as songs they are currently listening to. While this can be beneficial, it often lacks the element of surprise that comes from discovering entirely new recommendations.

Collaborative-based methods utilize an interaction matrix, also referred to as a rating matrix. The goal of these algorithms is to predict whether a user will find an item appealing—essentially whether they are likely to purchase, listen to, or watch that item.

Within collaborative-based systems, there are two main types: user-item filtering and item-item filtering.

The objective of this project is to:

Create a content-based music recommender system using a dataset that includes the name, artist, and lyrics of 57,650 English songs, sourced from Kaggle. This data was scraped from LyricsFreak by the author.
Develop a collaborative filtering music recommender system using the Million Song Dataset, which is a publicly available collection of audio features and metadata for one million contemporary popular music tracks.
This repository is organized into two packages containing the following files:

I. Content-Based Recommendation System:

A Jupyter notebook titled content_based_music_recommender, which includes the code and analysis for the recommendation system.
A CSV file named songdata, containing the data for the songs utilized in the system.
II. Collaborative Recommendation System:

A Jupyter notebook named collaborative_music_recommender, which contains the code and analysis for the recommendation system.
A CSV file called songs, which includes the data for the songs used in the system.

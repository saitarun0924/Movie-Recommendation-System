# Movie-Recommendation-System
I built this recommendation system with simple techniques and small datasets. 
The two datasets I used for this model are:
1) recent_movies.csv
   (movieId, title, genres, year)
   This dataset has some information about some movies.
   
3) recent_ratings.csv
   (userId, movieId, rating, timestamp) 
   This dataset has information about the ratings given by users on a respective movie.
   
I built this model to recommend movies using Collaborative filtering and Hamming distance.

Hamming Distance:
Measures how different two sequences are. It is % of disagreement. A value of 1 indicates sequences are very different, and 0 indicates they are very similar.

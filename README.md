# Collaborative-FIltering
Item based collaborative filtering  on movies rating data set with Spark 

The dataset used had data from 943 users and 100,000 ratings on 1682 items (movies). The data can be downloaded from the grouplens.org website. The dataset is old and will not include recent movie names.

The u.data file contains the movie ratings associated with each user
The columns from left to right are

User ID, Movie ID, Movie Rating, Time Stamp

The u.item file has the movie information associated with each movie ID. 
The columns are more or less '|' separated. The elements are
movie ID | movie title | release date | video release date | IMDB url | unknown | <19 columns specifying the genre with a 1 indicating the movie is of that genre, and 0 otherwise>.

The 19 genres are listed in the u.genre file.

Goal is to develop a item based recommendation system which can suggest movies similar to a particular chosen movie.

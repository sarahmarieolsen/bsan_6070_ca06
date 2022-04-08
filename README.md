# bsan_6070_ca06

**Recommending Movies Using K Nearest Neighbors**

*Introduction:*
The data used in this project contains thirty movies, including data for each movie across seven genres and their IMDB ratings. The labels column values are all zeroes because we aren’t using this data set for classification or regression. You can ignore this column. The implementation assumes that all columns contain numerical data. Additionally, there are relationships among the movies that will not be accounted for (e.g. actors, directors, and themes) when using the KNN algorithm simply because the data that captures those relationships are missing from the data set. Consequently, when we run the KNN algorithm on our data, similarity will be based solely on the included genres and the IMDB ratings of the movies.

In this project, we will use a K nearest neighbor algorithm to recommend five movies to a user. The input of the algorithm is the data for the movie The Post, and the the output is five movie titles from the data that are most similar to The Post.

*Process:*
The data is stored at a github raw link. Run this file and the output will be the five movies most similar to The Post.

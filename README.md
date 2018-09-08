# movie-recommender-system
Implementation of collaborative filtering learning algorithm on a dataset of movie ratings.

### Dataset
This dataset consists of ratings of movies on a scale of 1 to 5. The dataset has 943 users, and 1682 movies. The list of all movies and their number in the dataset can be found listed in the file movie idx.txt.

### Learning Algorithm
The objective of collaborative filtering learning algorithm is to predict movie ratings for the movies that users have not yet rated, that is, the entries with R(i; j) = 0. It is by computing the cost function and optimizing it using gradient descent. Reguralization factor is also added to keep the learning from becoming baised on training dataset.

### Disclaimer
This exercise is done as part of the online Machine Learning course available on coursera, offered by Stanford and taught by Andrew Ng. The instructions, data and some of the code files provided in the exercise are from the course catalog.

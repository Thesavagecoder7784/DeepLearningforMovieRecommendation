# Deep Learning for Movie Recommendation

A movie recommendation engine implemented with TensorFlow Recommendation (TFRS) library. The system is trained on a dataset of movie ratings, and is able to make recommendations for a particular user based on their previous ratings.

## Data
The system uses a dataset of 100k movie ratings from the MovieLens website. The data contains the user ID, movie title, and rating (on a scale of 0.5 to 5 stars) for each movie. The system also uses a dataset of metadata for the movies, including the movie title and some additional information such as the release year, genre, and budget.

## Model
The recommendation engine is built using the TFRS library, which is a TensorFlow library for building recommendation systems. The system uses an embedding model to represent each user and each movie as a dense vector in a high-dimensional space. The model also includes a neural network to predict the ratings given a user and movie representation.

The system uses two tasks in the TFRS library: ranking and retrieval. The ranking task is used to predict the rating a user would give to a movie based on the user and movie representations. The retrieval task is used to find the most similar movies to a given movie, based on the movie representations.

The system is trained using a combination of the two tasks, with the relative importance of each task being controlled by the loss weights.

## Results
The recommendation engine is able to make accurate recommendations for movies based on a user's previous ratings. The system is able to use the movie embeddings to find the most similar movies to a given movie, and to predict the rating a user would give to a movie. The system can also be used to recommend movies to a user based on their previous ratings.

## Usage
The code for this recommendation engine is provided as a Jupyter Notebook, which can be run in a local environment or in the cloud using a service such as Google Colab. The system requires the TensorFlow and TensorFlow Recommendation libraries to be installed. The MovieLens data files are also required and can be downloaded from the MovieLens website.

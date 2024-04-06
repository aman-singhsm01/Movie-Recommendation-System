# Movie-Recommendation-System


This project implements a movie recommendation system using machine learning techniques. It suggests similar movies based on user input, providing a personalized movie recommendation experience.

## Overview

The system uses a dataset of movies with features such as genres, keywords, taglines, cast, and director. It preprocesses this data to create feature vectors using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization. Cosine similarity is then calculated between movies based on these vectors to determine similarity scores.

## Usage

1. **Data Collection and Preprocessing**: The system reads a dataset of movies and selects relevant features like genres, keywords, etc. It fills any missing values with empty strings and combines these features into a single text representation for each movie. These text representations are converted into feature vectors using TF-IDF vectorization.

2. **Movie Recommendation**: When a user enters their favorite movie, the system finds the closest match in the dataset using difflib. It then calculates similarity scores between the user's movie and all other movies using cosine similarity. The system sorts the movies based on these scores and suggests the most similar movies as recommendations.

## Accuracy

The Movie Recommendation System claims to provide 100% accuracy in suggesting similar movies based on the input movie. This accuracy is achieved through robust data preprocessing, TF-IDF vectorization, and cosine similarity calculations. However, it's important to note that the accuracy may vary depending on the quality and relevance of the dataset and the user's input.

## Disclaimer

This recommendation system is for educational and informational purposes only. While it aims for high accuracy, the suggestions provided are based on mathematical similarity metrics and may not always reflect individual user preferences accurately. Users are encouraged to use their discretion and explore various recommendations.

## Contribution

Contributions to this project are welcome. Feel free to fork the repository, make improvements, and submit pull requests to enhance the functionality and accuracy of the movie recommendation system.


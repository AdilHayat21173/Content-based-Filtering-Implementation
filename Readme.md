# Content-Based Movie Recommendation System

## Step 1: Dataset Preparation
- Download the dataset from [TMDB Movie Metadata](https://www.kaggle.com/tmdb/tmdb-movie-metadata).
- Read the dataset.
- Remove unnecessary columns.
- Merge both datasets (movies and credits) based on the 'id' column.

## Step 2: Content-Based Recommendation System
- Convert text to vectors, as models require data in vector form or to find similarity.
- Use the Sigmoid function.
- This matrix is used to calculate similarities between items.

## Step 3: Implementation
- Get Movie Index: Find the index of the movie title in the dataset.
- Calculate Similarity Scores: Calculate similarity scores between the chosen movie and all other movies in the dataset.
- Sort Scores: Sort the similarity scores to find the most similar movies.
- Select Top Similar Movies: Choose the top 10 most similar movies (excluding the movie itself).
- Return Recommendations: Return the titles of these top 10 similar movies.

## Step 4: Testing and Documentation
- Test the content-based recommendation system with the movie "Spy Kids."
- Update the README.md file with corrected English grammar and format.

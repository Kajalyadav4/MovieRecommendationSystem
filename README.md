# Movie Recommender System

This project implements an item-based collaborative filtering movie recommender system using the MovieLens 100k dataset. The system recommends movies similar to a selected title based on user rating patterns.

## Features

- Item-based collaborative filtering using Pearson correlation
- Real-time recommendations based on similarity scores
- Popularity filtering to avoid recommending obscure titles
- Data preprocessing using Pandas

## How It Works

1. Load and clean the MovieLens dataset.
2. Create a user-movie ratings matrix.
3. Compute similarity scores between movies based on user ratings.
4. Given a movie title, return a list of similar movies with high correlation.
5. Apply popularity filtering to improve recommendation quality.

# Problem Statement 

With thousands of movies available across streaming platforms, users often struggle
to find content that matches their personal taste. Manually browsing through large catalogs is time-consuming and often leads to poor viewing choices.

This project addresses the problem of personalized movie discovery by building a recommendation system that
automatically predicts what movies a user is likely to enjoy — based on the viewing and rating patterns of other users with similar preferences.

Using the MovieLens 100K dataset, the system applies User-Based Collaborative Filtering with Cosine Similarity
to identify like-minded users and surface the most relevant
unwatched movies for any given user. The model is evaluated using RMSE, MAE, and Precision@5 to measure both prediction accuracy and recommendation quality.

The core challenge: most users have rated only a small fraction of available movies (~6.3% of the full catalog), 
making the user-item matrix highly sparse and similarity computation unreliable — a fundamental problem this project explores and addresses at a baseline level.

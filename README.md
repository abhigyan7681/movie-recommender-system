# Movie Recommendation System

A user-based collaborative filtering recommendation system built 
on the MovieLens 100K dataset.

## Algorithm
- User-Based Collaborative Filtering
- Cosine Similarity to find similar users
- Top-N recommendation generation

## Results
| Metric       | Score  |
|--------------|--------|
| RMSE         | 2.3742 |
| MAE          | 2.0880 |
| Precision@5  | 0.2400 |

## Dataset
[MovieLens 100K](https://grouplens.org/datasets/movielens/100k/) — 
100,000 ratings from 943 users on 1,682 movies.

## How to Run

### Option 1 — Google Colab (recommended)
Open `movie_recommender.ipynb` directly in Colab and run all cells.

### Option 2 — Local
```bash
pip install -r requirements.txt
jupyter notebook movie_recommender.ipynb
```

## Project Structure
- `movie_recommender.ipynb` — main notebook with all code
- `ml-100k/` — MovieLens dataset files
- `requirements.txt` — Python dependencies
- `plots.png` — rating distribution and user activity plots

## Limitations
- High RMSE due to dataset sparsity
- Cold start problem for new users
- No content-based features used



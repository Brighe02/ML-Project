# Music Genre Classification and Analysis

A Machine Learning project exploring music genre classification and recommendation using the Spotify audio features dataset.

## Project Overview

This project investigates how well mathematical features extracted from audio signals can capture the complex nature of musical genres. The main objectives are:

- **Genre Classification**: Predict music genres (Pop, Rock, R&B, Rap, EDM, Latin) using supervised learning algorithms (KNN, Random Forest, AdaBoost)
- **Clustering Analysis**: Explore the intrinsic structure of music data using K-Means and PCA
- **Recommendation System**: Build a content-based recommender using cosine similarity

The analysis is performed on the "30,000 Spotify Songs" dataset from Kaggle, utilizing audio features such as danceability, energy, tempo, acousticness, and others.

## Key Findings

- Tree-based models (Random Forest) outperform distance-based methods (KNN) for genre classification
- Musical genres do not form clearly separable clusters in the feature space
- Features like energy, danceability, and acousticness are the strongest predictors of genre
- Content-based recommendation provides a viable solution for the "Cold Start Problem"

## Repository Structure

- `src/` - Source code folder
  - `MLProject.ipynb` - Data exploration and preprocessing
  - `ReccomenderSystem.ipynb` - Classification, clustering and recommendation
- `Project-Report.pdf` - Full project report
- `README.md` - Project documentation

## Technologies Used

- Python 3.x
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Dataset

The dataset used is [30,000 Spotify Songs](https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs) available on Kaggle.

## Author

**Alessio Brighenti**  
Master's Degree in Artificial Intelligence  
University of Verona

## Course Information

Machine Learning - Academic Year 2025/2026  
Professor: Cigdem Beyan
# Movie Recommendation System

## Overview
This repository contains a Jupyter notebook implementing a movie recommendation system. The recommendation system is based on collaborative filtering using the SVD algorithm from the Surprise library.

## Dataset
The dataset used in this project is the MovieLens dataset, which contains user ratings for various movies. The dataset includes features such as 'userId', 'movieId', and 'rating'.

## Dependencies
- Python
- Pandas
- Surprise
- Jupyter

## Usage
1. Clone the repository: `git clone https://github.com/yourusername/movie-recommendation-system.git`
2. Navigate to the cloned project: `cd movie-recommendation-system`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Open the Jupyter notebook: `jupyter notebook`

## Methodology
The recommendation system is implemented using the SVD algorithm from the Surprise library. The data is split into a training set and a test set. The model is trained on the training set and the predictions are made on the test set. The accuracy of the predictions is evaluated using RMSE (Root Mean Square Error) and MAE (Mean Absolute Error).

## Results
The model achieved an RMSE of X and an MAE of Y. (Replace X and Y with your actual results)

## Future Work
Future improvements could include trying different algorithms, tuning hyperparameters, and incorporating additional features such as movie genres or user demographics.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

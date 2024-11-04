# Movie Recommendation System

A collaborative filtering-based recommendation system using Singular Value Decomposition (SVD), trained on the MovieLens dataset to generate personalized movie recommendations. This project demonstrates how to build, evaluate, and interact with a recommendation system using Python and the Surprise library.

## Project Overview
This recommendation system is designed to predict user ratings for movies they haven't seen and provide personalized recommendations. The model leverages collaborative filtering with SVD, a popular matrix factorization technique. 

The notebook includes:
- **Data Loading and Preprocessing**: Loading the MovieLens dataset and preparing it for training.
- **Model Training and Evaluation**: Training an SVD model and evaluating it using metrics like RMSE, Precision, and Recall.
- **Interactivity**: An input field for testing recommendations for any user in the dataset.

## Setup and Requirements

### Required Installations
To run this project, you’ll need the following Python libraries. You can install them via pip:

```
pip install pandas scikit-surprise scikit-learn ipywidgets
```

### Running the Notebook
1. **Clone the Repository**:
   Clone this repository to your local machine:
```
   git clone https://gitlab.com/ntmebane/movie-recommendation-system.git
   cd movie-recommendation-system
```
2. **Download the Dataset**:
   Download the [MovieLens 100k dataset](https://grouplens.org/datasets/movielens/100k/) and place the `u.data` and `u.item` files in the project directory.

3. **Run the Jupyter Notebook**:
   Open the Jupyter Notebook to explore and run the code:

   jupyter notebook movie_recommendation_system.ipynb

4. **Interact with the Notebook**:
   - **Train the Model**: Run each cell to load data, preprocess, train, and evaluate the model.
   - **Generate Recommendations**: Use the interactive input field in the notebook to type a user ID and view personalized movie recommendations.
# Chess Game Data Analysis and Prediction

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Feature Engineering](#feature-engineering)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Results](#results)


## Introduction
The goal of this project is to analyze a dataset of chess games and build machine learning models to predict the outcome of a chess game. We explore the dataset, engineer features, visualize data trends, and evaluate the performance of different classification models.

## Dataset
The dataset used in this project contains chess game data with the following columns:
- `id`: Unique identifier for each game
- `rated`: Whether the game is rated or not
- `created_at`: Timestamp when the game was created
- `last_move_at`: Timestamp of the last move in the game
- `turns`: Number of turns in the game
- `victory_status`: How the game was won (e.g., checkmate, resignation, timeout)
- `winner`: The winner of the game (white, black, or draw)
- `increment_code`: Increment code used for the game
- `white_id`: Player ID of the white player
- `white_rating`: Rating of the white player
- `black_id`: Player ID of the black player
- `black_rating`: Rating of the black player
- `moves`: The moves made in the game
- `opening_eco`: ECO code of the opening played
- `opening_name`: Name of the opening played
- `opening_ply`: Number of half-moves in the opening phase

## Installation
To run the code in this repository, you need to have Python installed along with the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required libraries using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/chess-game-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd chess-game-analysis
   ```
3. Run the Jupyter notebook or Python script to perform the analysis:
   ```bash
   Internship.ipynb
   ```
   

## Exploratory Data Analysis
In the EDA section, we display the first few rows of the dataset to understand its structure. We check for basic statistics, data shape, and information about the columns. We also check for missing values and visualize the distribution of key variables.

## Feature Engineering
We preprocess the data by encoding categorical variables using label encoding. We also handle outliers and create new features such as `match_time` which represents the duration of the game in seconds.

## Model Training and Evaluation
We split the data into training and testing sets and train various classification models including:
- Logistic Regression
- Decision Tree
- Random Forest

We evaluate the performance of these models using accuracy, precision, recall, and F1-score.

## Results
The performance of the models is compared, and the best model is selected based on the evaluation metrics. Visualizations such as scatter plots and count plots are used to illustrate the trends and patterns in the data.


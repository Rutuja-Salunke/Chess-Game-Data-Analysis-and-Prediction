# Chess Game Data Analysis and Prediction

This repository contains the analysis and prediction models for chess game outcomes using a dataset from Lichess.org.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Feature Engineering](#feature-engineering)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
- 🎯 **Goal:** Analyze chess game data and predict game outcomes.
- 🔍 **Methods:** EDA, feature engineering, visualization, model training.

## Dataset
- 📁 **Source:** Lichess.org
- 📊 **Content:** Includes game ID, ratings, moves, results, and more.
- 🏆 **Features:** Player ratings, game duration, opening names.

## Installation
- 💻 **Python Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn.
- 📦 **Install with pip:**
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn
  ```

## Usage
- 📝 **Clone Repository:**
  ```bash
  git clone https://github.com/yourusername/chess-game-analysis.git
  ```
- 📂 **Navigate:**
  ```bash
  cd chess-game-analysis
  ```
- 🚀 **Run Analysis:**
  ```bash
  jupyter notebook analysis.ipynb
  ```
  or
  ```bash
  python analysis.py
  ```

## Exploratory Data Analysis
- 🔎 **Inspect Data:** View dataset structure, statistics, and check for missing values.
- 📊 **Visualizations:** Plot distributions and trends in key variables.

## Feature Engineering
- 🛠️ **Preprocessing:** Encode categorical variables, handle outliers.
- ⏱️ **New Features:** Create `match_time` to represent game duration.

## Model Training and Evaluation
- 🧠 **Models:** Logistic Regression, Decision Tree, Random Forest.
- 📈 **Metrics:** Evaluate using accuracy, precision, recall, and F1-score.

## Results
- 🏅 **Comparison:** Select the best model based on evaluation metrics.
- 📉 **Visuals:** Scatter plots and count plots illustrate data trends.

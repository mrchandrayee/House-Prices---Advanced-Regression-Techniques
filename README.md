# House-Prices---Advanced-Regression-Techniques

# House Prices Prediction

This repository contains code and documentation for predicting house prices using advanced regression techniques as part of the Kaggle competition ["House Prices - Advanced Regression Techniques"](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

## Overview

In this project, we aim to predict the sale prices of houses based on various features provided in the dataset. The dataset contains information about different aspects of residential properties such as their size, location, amenities, and more.

## Contents

- `data_description.txt`: Full description of each column in the dataset.
- `sample_submission.csv`: A benchmark submission file.
- `train.csv`: The training set.
- `test.csv`: The test set.

## Approach

### Data Preprocessing:

- Loaded the training and test datasets.
- Explored the data to understand its structure, missing values, and distributions.
- Handled missing values using imputation techniques.
- Encoded categorical variables using one-hot encoding.
- Performed feature scaling to normalize numerical features.

### Feature Engineering:

- Created new features such as total square footage of the house.
- Transformed skewed features using techniques like log transformation.

### Model Selection:

- Selected regression models including Random Forests and Gradient Boosting Machines (GBMs).
- Implemented models using libraries like scikit-learn and XGBoost.

### Training and Evaluation:

- Split the training data into training and validation sets.
- Trained the selected models and evaluated their performance using RMSE.
- Tuned hyperparameters using techniques like cross-validation.

### Prediction:

- Made predictions on the test dataset using the trained models.
- Combined predictions from different models, e.g., by averaging, to potentially improve performance.

### Submission:

- Prepared the submission file with the predicted sale prices for the test dataset.

## Results

- Achieved an RMSE of [2586/4474*] on the Kaggle leaderboard.

## Getting Started

To run the code locally or reproduce the results, follow these steps:

1. Clone this repository.
2. git clone https://github.com/mrchandrayee/House-Prices-Prediction.git
3. Run the Jupyter notebooks or Python scripts for data preprocessing, feature engineering, model training, and prediction.

## Author

[Chand Rayee](https://github.com/mrchandrayee)

## Connect With Us

Feel free to reach out to us through any of the following platforms:

- Telegram: [@crupgrade](https://t.me/crupgrade)
- LinkedIn: [Mr. Chandrayee](https://www.linkedin.com/in/mrchandrayee/)
- GitHub: [mrchandrayee](https://github.com/mrchandrayee)
- Kaggle: [mrchandrayee](https://www.kaggle.com/mrchandrayee)
- Instagram: [@chandrayee](https://www.instagram.com/chandrayee/)
- YouTube: [Chand Rayee](https://www.youtube.com/channel/UCcM2HEX1YXcWjk2AK0hgyFg)

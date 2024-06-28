# House Price Predictor

Welcome to the House Price Predictor repository! This project utilizes machine learning algorithms to predict house prices based on various features. The aim is to provide accurate and reliable predictions to assist in real estate decision-making.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Models](#models)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

House Price Predictor is a machine learning project designed to predict the price of houses based on multiple features such as location, size, number of bedrooms, etc. This project aims to help potential buyers and real estate agents make informed decisions.

## Features

- Data preprocessing and feature engineering
- Multiple machine learning models for price prediction
- Model evaluation and comparison
- Visualization of data and results

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Poojitha237/house_price_predictor.git
    cd house_price_predictor
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

## Usage

1. Ensure that the dataset is in the `data` directory. You can download the dataset from [Kaggle](https://www.kaggle.com/).

2. Open the Jupyter notebook:
    ```bash
    jupyter notebook bhp.ipynb
    ```

3. Follow the instructions in the notebook to preprocess the data, train the models, evaluate the models, and make predictions.

4. The trained model is saved as `banglore_home_prices_model.pickle`. You can use this file to make predictions on new data.

## Data

The dataset used for this project includes various features such as:

- Location
- Size (square footage)
- Number of bedrooms
- Number of bathrooms
- Year built
- ... and more.

Ensure the dataset is in CSV format and placed in the `data` directory.

## Models

This project implements and compares several machine learning models, including:

- Linear Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost

## Results

The results of the models are evaluated based on metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared. The best-performing model is selected for making predictions.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The dataset used in this project was obtained from [Kaggle](https://www.kaggle.com/).
- Special thanks to the open-source community for providing tools and libraries that made this project possible.

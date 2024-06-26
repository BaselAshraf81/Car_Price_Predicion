# THIS PROJECT IS A SIMPLE EFFORTLESS PROJECT FOR UNIVERSITY COURSE NUMBER CSE338 Artifical Intelligence

# Car Price Prediction Model

![Project Image](https://github.com/BaselAshraf81/Car_Price_Predicion/blob/main/car.webp)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains a machine learning model for predicting car prices based on various features. The model is developed using TensorFlow and Keras.

## Features

- **Outlier Exclusion**: Utilizes a weighted approach to exclude outliers in the target variable during data preparation.
- **Data Visualization**: Provides pairplot analysis for visualizing feature distributions and correlations.
- **Model Creation**: Implements a neural network architecture with batch normalization and early stopping techniques.
- **Training and Evaluation**: Splits the dataset, compiles, trains, and evaluates the model using appropriate metrics.
- **Result Visualization**: Generates loss curves and bar plots to visualize model performance and predicted vs. true values.
- **Layer Analysis**: Conducts layer weight analysis to identify redundant layers in the model.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/BaselAshraf81/Car_Price_Predicion.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Navigate to the project directory:

    ```bash
    cd Car_Price_Predicion
    ```

2. Run the Jupyter Notebook:

    ```bash
    jupyter notebook car_price_prediction.ipynb
    ```

3. Follow the instructions in the notebook to execute the project.

## Contributing

Contributions are welcome! Here's how you can contribute to the project:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/feature-name`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push your branch (`git push origin feature/feature-name`).
5. Create a new Pull Request.

## License

This project is licensed under the terms of the [MIT License](LICENSE.txt).

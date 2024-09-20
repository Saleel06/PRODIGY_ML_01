
# House Price Prediction using Linear Regression

This project involves predicting house prices using linear regression, based on features like square footage, number of bedrooms, and number of bathrooms. The dataset used for this project is sourced from the [Kaggle House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
In this project, a linear regression model is built to predict the sale prices of houses based on various features. The primary objective is to explore the relationship between house features and their prices, and to develop a model that can make accurate predictions for unseen data.

## Dataset
The dataset used is from the Kaggle competition "House Prices - Advanced Regression Techniques." It includes 79 explanatory variables describing various aspects of residential homes in Ames, Iowa.

- **Training Dataset:** `train.csv`
- **Test Dataset:** `test.csv`

The training dataset contains house prices along with various features, while the test dataset contains the features without the price, for which predictions need to be made.

## Model
The model used for this project is a simple linear regression model, trained using the following features:
- `GrLivArea`: Above ground living area square footage
- `BedroomAbvGr`: Number of bedrooms above ground
- `FullBath`: Number of full bathrooms above ground

### Model Evaluation
The model is evaluated using the Root Mean Squared Error (RMSE) to measure the prediction accuracy.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/house-price-prediction.git
   cd house-price-prediction
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) and place it in the project directory.

## Usage
1. Run the `house_price_prediction.py` script to train the model and generate predictions:
   ```bash
   python house_price_prediction.py
   ```

2. The script will output the predictions in a CSV file named `house_price_predictions.csv`.

3. You can modify the features used for training by updating the `feature_columns` list in the script.


## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to submit a pull request or open an issue.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


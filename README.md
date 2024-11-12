# Gold Price Prediction

## Project Overview
This project focuses on predicting the price of gold using a dataset that includes various financial indicators. The goal is to build a regression model that can accurately estimate the price of gold (GLD) based on the relationships with other financial factors such as stock market indices, oil prices, and currency exchange rates.

## Dataset
The dataset contains the following columns:
- **Date**: Date of the record
- **SPX**: S&P 500 Index, representing the stock market performance
- **GLD**: The price of gold (target variable)
- **USO**: Oil prices (tracked by the United States Oil Fund)
- **SLV**: Silver prices (tracked by the iShares Silver Trust)
- **EUR/USD**: Euro to US Dollar exchange rate

## Model
To predict the price of gold, I have applied the **Random Forest Regressor**, a powerful ensemble machine learning algorithm that uses multiple decision trees to improve the accuracy of predictions. This model is trained on historical data, and its performance is evaluated using various regression metrics.

## Approach
1. **Data Preprocessing**: The data is first cleaned and preprocessed, handling missing values and ensuring that all features are in a format suitable for training the model.
2. **Model Training**: A Random Forest Regressor is trained using the financial indicators as input features.
3. **Model Evaluation**: The performance of the model is evaluated using regression metrics such as R-squared and Mean Absolute Error (MAE) to ensure the predictions are accurate and reliable.

## Results
The model is capable of predicting gold prices based on historical data and financial indicators. The effectiveness of the model depends on the quality of input features and the relationships between the predictor variables and the target.

## Technologies Used
- Python
- Pandas (for data manipulation)
- Scikit-learn (for machine learning models and evaluation)
- Matplotlib/Seaborn (for visualization)

## Installation
To run this project, clone the repository and install the required dependencies:
```bash
git clone https://github.com/your-username/gold-price-prediction.git
cd gold-price-prediction
pip install -r requirements.txt

### Key Sections in the README:
- **Project Overview**: Briefly describes the objective of the project.
- **Dataset**: Details about the dataset and the columns used.
- **Model**: Explains the use of the Random Forest Regressor for prediction.
- **Approach**: Describes the steps followed in data preprocessing and model training.
- **Results**: Mentions the model’s predictive capabilities.
- **Technologies Used**: Lists the tools and libraries used in the project.
- **Installation and Usage**: Guides for setting up the project and running the code.
- **License**: Specifies the project license (e.g., MIT).

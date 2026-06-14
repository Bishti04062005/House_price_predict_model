# House_price_predict_model
House Price Prediction using Linear Regression
This repository contains a Jupyter Notebook that demonstrates a simple house price prediction model using Linear Regression. The model is trained on the 'Housing Prices Dataset' and includes steps for data loading, preprocessing, model training, evaluation, and making predictions for new house features.

# Dataset
The dataset used in this project is the 'Housing Prices Dataset' from Kaggle, which includes various features of houses such as area, number of bedrooms, bathrooms, stories, and other amenities, along with their prices.

# Model
A Linear Regression model from scikit-learn is used for predicting house prices. The data is preprocessed by converting categorical features into numerical representations and scaling numerical features using StandardScaler.

# Notebook Contents
1.Data Loading: Downloads the dataset from Kaggle Hub.

2.Data Preprocessing:
   
   -->Converts 'yes'/'no' columns to 1/0.
   
   -->Maps 'furnishingstatus' to numerical values (unfurnished: 0, semi-furnished: 1, furnished: 2).

3.Train-Test Split: Splits the data into training and testing sets.

4.Feature Scaling: Applies StandardScaler to normalize numerical features.

5.Model Training: Trains a LinearRegression model on the scaled training data.

6.Model Evaluation: Evaluates the model's performance using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2) score.

7.Visualization: Plots actual vs. predicted prices to visualize model performance.

8.Prediction: Includes a section to predict prices for new house features after applying the same preprocessing steps.

# How to Use
To run this notebook and predict house prices:

1.Clone the repository (if hosted on GitHub).

2.Open the Jupyter Notebook (or Google Colab).

3.Install Dependencies: Ensure you have kagglehub, pandas, scikit-learn, matplotlib, and seaborn installed.

4.Run all cells: Execute the cells sequentially to download data, preprocess it, train the model, and evaluate its performance.

5.Make Predictions: Modify the new_house_features dictionary in the last code cell to input your desired house features and get a price prediction.

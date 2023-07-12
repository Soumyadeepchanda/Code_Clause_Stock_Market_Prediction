# Stock Prediction with LSTM
This repository contains code for building and evaluating an LSTM-based predictive system for stock price prediction. The model is trained on historical stock data and used to make predictions on unseen test data.

### Introduction
Stock price prediction is a challenging task that has attracted significant attention in the field of finance. Predicting stock prices accurately can provide valuable insights to investors and traders. This project aims to develop a predictive system using Long Short-Term Memory (LSTM) neural networks, a type of recurrent neural network (RNN) architecture known for its ability to capture long-term dependencies.

### Install Dependencies and Setup
Before running the code, you need to install the required dependencies. The necessary dependencies are listed in the requirements.txt file. You can install them using the following command:

Make sure you have the following dependencies installed:

##### -pandas: For data manipulation and analysis
##### -numpy: For numerical operations
##### -matplotlib: For data visualization
##### -seaborn: For statistical data visualization
##### -yfinance: For downloading stock data from Yahoo Finance
##### -sklearn: For data preprocessing and evaluation metrics
##### -tensorflow: For building and training the LSTM model

### Usage

#### 1.Download and Convert the Data: 
In the code, specify the stocks you want to download by updating the stocks list. Run the code to download and convert the historical stock data into a pandas DataFrame.

#### 2.Explore the Data: 
Use the provided functions and visualizations to explore the downloaded data. The functions allow you to examine the data's summary statistics, distribution, box plots, correlation matrix, time series decomposition, and the relationship between closing price and volume.

#### 3.Data Cleaning: 
Check for missing values in the data and handle them appropriately. Convert the data types of the columns if needed.

#### 4.Exploratory Data Analysis (EDA):
Conduct EDA on the data to gain insights and understand the relationships between variables. Use visualizations to analyze trends and patterns in the data.

#### 5.Data Preprocessing: 
Prepare the data for model training. Split the data into input features (X) and the target variable (Y). Scale the data using a suitable scaling technique. Split the data into training and test sets.

#### 6.LSTM Model Building: 
Build an LSTM-based sequential model using the tensorflow.keras library. Configure the model architecture by adding LSTM layers with dropout regularization. Compile the model with an appropriate optimizer and loss function.

#### 7.Model Training: 
Train the LSTM model using the training data. Specify the number of epochs and batch size for training. Monitor the training progress and evaluate the model's performance on the validation set.

#### 8.Model Evaluation: 
Evaluate the trained model on the test data. Calculate metrics such as the coefficient of determination (R^2), mean absolute error (MAE), mean absolute percentage error (MAPE), and root mean squared error (RMSE) to assess the model's performance.

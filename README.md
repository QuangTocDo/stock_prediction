# Stock Price Prediction Using Machine Learning and Deep Learning
## 1. Project Overview
This project aims to predict stock prices using various Machine Learning (ML) and Deep Learning (DL) techniques on four distinct datasets, representing different companies' stock data. We focus on analyzing patterns and trends to forecast future stock prices, providing valuable insights for investors and analysts.
Companies Included:
FPT Corporation (FPT)
Masan Group (MSN)
Phú Nhuận Jewelry (PNJ)
Vingroup (VIC)

###Main Objectives:
Build predictive models for stock prices based on historical data.
Compare the performance of ML and DL models.
Provide visualizations and insights from the results.
## 2. Datasets
The project utilizes stock data from 4 companies (FPT, MSN, PNJ, VIC) which have been pre-processed and merged into a single DataFrame for unified analysis. The dataset includes:
Date
Open, High, Low, Close prices
Volume traded
## 3. Requirements

Main libraries:
Pandas: For data manipulation and analysis.
Numpy: For numerical computations.
Scikit-learn: For implementing ML models.
TensorFlow / Keras: For building DL models.
Matplotlib: For visualizing data and results.
## 4. Usage Instructions
Step 1: Clone the repository
Clone the repository to your local machine:
git clone <repository-link>
cd stock-price-prediction
Step 2: Data Preprocessing
Preprocessing is crucial for preparing the dataset for modeling. It includes:
Handling missing values.
Normalizing the data using MinMaxScaler.
Splitting the dataset into training and test sets.
Step 3: Model Training
3.1 Machine Learning Models:
We explore various traditional ML algorithms, including:
Linear Regression
XGBoost
3.2 Deep Learning Models:
For DL, we implement Long Short-Term Memory (LSTM) networks, which are particularly suitable for time series data.
Step 4: Evaluation
After training, the models are evaluated based on metrics such as:
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R-squared (R²) Score
## 5. Results & Visualizations

All results, including loss functions, accuracy, and predicted vs actual stock prices, will be visualized and saved in the results folder. Example charts include:

Predicted vs Actual Prices.
Model loss over epochs (for DL models).
## 6. Conclusion

This project demonstrates the application of both traditional ML models and advanced DL models for stock price prediction. By comparing different approaches, we aim to identify the most effective model for forecasting stock market trends.

## 7. Future Work

Potential improvements include:

Incorporating external factors such as economic indicators or news sentiment.
Fine-tuning models for better accuracy.
Experimenting with other DL architectures like Transformers.


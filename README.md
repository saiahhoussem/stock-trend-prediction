# Stock Trend Prediction using Machine Learning
## Overview
This repository contains code for a stock trend prediction application using machine learning. The application uses historical stock data to train a deep learning model and predicts future stock prices based on the learned patterns. The user interface is built with Streamlit, providing an interactive way to input stock tickers and visualize predictions.
## Dependencies
- NumPy
- Pandas
- Matplotlib
- Keras
- yfinance
- Streamlit
- Scikit-learn
## Usage
1. Install the required dependencies using the following command:
   ```bash
   pip install numpy pandas matplotlib keras yfinance streamlit scikit-learn
3. Run the Streamlit app:
   ```bash
   streamlit run app.py
5. Enter a stock ticker in the provided text input to retrieve historical stock data and view trend predictions.
## Code Structure
- **app.py:** Streamlit application script for user interaction.
- **keras_model.h5:** Pre-trained deep learning model for stock price prediction.
- **README.md:** Documentation file providing an overview and usage instructions.
## Data Collection
The historical stock data is obtained using the **yfinance** library. Users can input the desired stock ticker, and the app fetches data from Yahoo Finance within the specified date range.
## Data Visualization
The application displays descriptive statistics of the stock data and visualizes the closing prices over time. Additionally, it includes charts with moving averages (MA) to illustrate trends more clearly.
## Model Training and Testing
The deep learning model is trained on historical stock data, and predictions are made for the testing dataset. The model is loaded from the pre-trained keras_model.h5 file. The predictions are then compared to the actual stock prices, and the results are visualized using Matplotlib.
## Contributing
Feel free to contribute by submitting bug reports, feature requests, or pull requests. Your feedback and contributions are highly appreciated.

  

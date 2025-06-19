# Time-series-prediction
A time-series forecasting model using a Long Short-Term Memory (LSTM) network to predict future request volumes based on historical hourly data. This project demonstrates the process of data loading, preprocessing, model training, and prediction for time-series data.

# LSTM Time-Series Forecasting for Request Volume

This project is a practical implementation of a Long Short-Term Memory (LSTM) recurrent neural network for time-series forecasting. The model is trained on historical hourly request data to predict future request volumes for the next 600 hours.

## About The Project

The core of this project is to demonstrate how LSTMs can be effectively used to capture temporal dependencies in sequential data. The notebook provided covers the following key steps:

* **Data Loading and Preprocessing:** Reads time-series data from a CSV file, parses dates, and scales the target variable.
* **Data Sequencing:** Transforms the time-series data into sequences suitable for training an LSTM model.
* **Model Building:** Constructs a sequential model in Keras with LSTM layers.
* **Model Training:** Trains the LSTM model on the prepared sequences.
* **Forecasting:** Uses the trained model to predict future values.
* **Visualization:** Plots the historical data along with the model's predictions to visually assess performance.

### Built With

* [TensorFlow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)
* [Pandas](https://pandas.pydata.org/)
* [NumPy](https://numpy.org/)
* [Matplotlib](https://matplotlib.org/)
* [Scikit-learn](https://scikit-learn.org/stable/)

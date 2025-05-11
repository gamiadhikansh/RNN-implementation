Time Series Forecasting with LSTM on Monthly Milk Production Dataset using Python

This project demonstrates how to use a **Recurrent Neural Network (RNN)** with **Long Short-Term Memory (LSTM)** units to forecast monthly milk production over time. The dataset contains monthly milk production (in pounds per cow) from January 1962 to December 1975, making it a classic univariate time series problem.

Using Python along with libraries like **TensorFlow/Keras**, **Pandas**, **Matplotlib**, and **Scikit-learn**, the workflow involves:

Key Steps:

**Data Preprocessing:**

  * Parsing and formatting the time series data
  * Normalizing the values for better model convergence
  * Creating sequences of past observations to train the LSTM model

**Model Architecture:**

  * A stacked LSTM model is built with memory units designed to capture long-term dependencies in the data
  * Dropout layers are included to reduce overfitting
  * Dense output layer to predict future values

**Training & Evaluation:**

  * The model is trained to minimize mean squared error (MSE)
  * Final performance is evaluated using **Root Mean Squared Error (RMSE)**
  * Achieved an **RMSE of approximately 28%** relative to the average milk production — indicating a reasonably accurate forecast

**Visualization:**

  * Actual vs Predicted values plotted for visual inspection
  * Clear trends and seasonality are captured by the model

This project serves as a practical example of how deep learning techniques like LSTM can effectively model and forecast real-world time series data with temporal patterns and seasonality.

---

Let me know if you want a shorter version for GitHub, or a more technical/academic style!

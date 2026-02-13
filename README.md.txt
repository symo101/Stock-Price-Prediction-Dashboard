Stock Price Prediction Dashboard (LSTM)

📌 Project Overview
This project demonstrates the application of Deep Learning in financial time-series forecasting. I developed a model to predict the closing prices of NSE Tata Global Beverages stocks. To make the model accessible, I built an interactive web dashboard that allows users to visualize historical data alongside model predictions.

🛠️ Technical Stack
Language: Python 3.14.

Deep Learning: Keras/TensorFlow using LSTM (Long Short-Term Memory) architecture.

Data Handling: Pandas, NumPy, and Scikit-learn (MinMaxScaler).

Frontend/Deployment: Dash by Plotly for the web interface.

🚀 Key Features
Time-Series Forecasting: Uses 60-day windows of historical stock data to predict future prices.

Interactive Visualization: A dynamic graph with a clear legend identifying Historical, Actual (Validation), and Predicted prices.

Real-time Server: Runs on a local Flask server via Dash for instant data exploration.

📈 Results
The model successfully identifies overall market trends and momentum. The visualization highlights the model's ability to track the validation data closely, providing a clear comparison between reality and the LSTM's forecast
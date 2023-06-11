# Hackathon-Online-Cryptocurrency-Prediction
![image](https://github.com/bright-arparwut/Hackathon-Online-Cryptocurrency-Prediction/assets/124503010/83f3fb60-21b9-4666-a9fc-01cc10f13b43)
**Introduction**
In this project, we aim to predict cryptocurrency prices for the next 952 days. Leveraging time series analysis and PyCaret, an open-source, low-code machine learning library in Python, we develop a model that enables us to forecast future prices.

**Data**
The data used in this project comprises historical prices for a particular cryptocurrency along with some derived features. The dataset features columns for date, price, a 7-day moving average, a 30-day moving average, a 7-day standard deviation, a 30-day standard deviation, the Relative Strength Index (RSI), and price change.

**Methodology**
Data Cleaning and Preprocessing
The dataset was preprocessed to handle missing values and create features to help improve the performance of the model.

**Feature Engineering**
We generated several features from the raw data. These include a 7-day moving average, a 30-day moving average, a 7-day standard deviation, a 30-day standard deviation, the RSI, and price change. These features provided more contextual information for the model to learn from.

**Model Selection**
We used PyCaret, a machine learning library in Python, to select the model. PyCaret's simplicity and effectiveness made it a great choice for this project. The library includes several built-in models for regression tasks, which we leveraged to select the best performing model.

**Model Training**
We trained the selected model on our dataset, tuning its hyperparameters to ensure the best performance.

**Model Evaluation**
The model was evaluated using various metrics appropriate for regression tasks, including the R-squared, Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE).

**Model Prediction**
The trained model was used to predict the cryptocurrency prices for the next 952 days.

**Results**
After training and tuning the model, we were able to obtain a forecast of the cryptocurrency prices for the next 952 days.



**OUTCOME**

**Ranked** 🎖️#10 amongs 43 teams

**Evaluation Metric** Metric Mean Absolute Error (MAE)

**Scored** 0.17735 in private leaderboard

![image](https://github.com/bright-arparwut/Hackathon-Online-Cryptocurrency-Prediction/assets/124503010/c55bbcf9-4fa9-4721-b779-44406dade1cf)


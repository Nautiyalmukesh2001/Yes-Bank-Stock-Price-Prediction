# Yes Bank Stock Closing Price Prediction  

## Project Overview  
This project focuses on predicting the closing stock price of **Yes Bank** using **time series analysis** and **machine learning techniques**. The objective is to assist investors and financial analysts in making informed decisions by forecasting future price movements and managing risks.  

## Dataset  
The dataset consists of historical **Yes Bank stock prices**, including:  
- 📅 **Date**  
- 📈 **Open Price**  
- 📊 **High Price**  
- 📉 **Low Price**  
- 💰 **Close Price**  

## Methodology  

### 🔹 Data Preprocessing  
✔ Cleaned and handled missing values  
✔ Converted date column to a datetime format and set it as an index  

### 🔹 Exploratory Data Analysis (EDA)  
✔ Visualized stock price trends and volatility patterns  
✔ Identified key patterns such as seasonality and cyclic trends  

### 🔹 Feature Engineering  
✔ Created lagged features for better time series forecasting  
✔ Implemented rolling window statistics for trend smoothing  

### 🔹 Model Implementation  
✔ **Time Series Models:** ARIMA, SARIMA  
✔ **Machine Learning Models:** Linear Regression, Lasso, Ridge  

### 🔹 Model Evaluation  
✔ Used **Mean Squared Error (MSE)** and **R-squared (R²)** for assessing model accuracy  

## Key Findings  
- **ARIMA & SARIMA:** Captured trends and seasonality well, offering reasonable predictions.  
- **Machine Learning Models:** Regularized models like **Lasso and Ridge** improved predictive accuracy by reducing overfitting.  
- **Challenges:** Exclusion of external factors (e.g., economic indicators, market news) limited model accuracy.  

## Solutions to Business Objective  
✔ **Risk Management:** Forecasted price fluctuations help investors mitigate risks.  
✔ **Investment Strategies:** Provides data-driven insights for portfolio optimization.  
✔ **Market Analysis:** Enhances decision-making by correlating stock performance with financial indicators.  

## Conclusion & Future Work  
✔ This project demonstrates the effectiveness of **data-driven approaches** in predicting stock prices, despite market volatility.  
✔ Future improvements can include **macroeconomic data, sentiment analysis**, and **deep learning models** (e.g., LSTMs).  
✔ While absolute accuracy is challenging, this project helps investors **make informed decisions** with greater confidence.  

## Technologies Used  
🔹 Python (Pandas, NumPy, Matplotlib, Seaborn)  
🔹 Statsmodels (ARIMA, SARIMA)  
🔹 Scikit-learn (Linear Regression, Lasso, Ridge)  


## Usage

To explore the project, follow these steps:

1. Clone the repository.
2. Open the Jupyter Notebook in Google Colab.
3. Run the cells to execute the code and view the visualizations.

## Author

* Mukesh Nautiyal
* LinkedIn: [https://www.linkedin.com/in/mukesh-nautiyal-23978a2b1/]

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

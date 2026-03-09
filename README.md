📊 Crude Oil Import & Export Forecasting for India

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1NkqUQ5xvISRto4FjTC2Y92_7ZOU-e_TK/view?usp=sharing)

This project forecasts India's crude oil imports and exports using statistical and deep learning models such as ARIMA, GARCH, LSTM, and CNN-LSTM.
📌 Project Overview

This project focuses on forecasting India's crude oil imports and exports using time series analysis and deep learning models.
The goal is to analyze historical crude oil data and build predictive models to estimate future import and export trends.

The project compares classical statistical models and modern deep learning techniques to identify the most accurate forecasting approach.

This project was developed as part of a Final Year Capstone Project.

🎯 Objectives

Analyze historical crude oil import and export data

Perform data cleaning and preprocessing

Apply time series forecasting models

Compare statistical and deep learning approaches

Evaluate forecasting accuracy using multiple metrics

📂 Project Workflow

The notebook follows the workflow below:

1️⃣ Data Preprocessing

Data cleaning

Handling missing values

Structuring time series data

2️⃣ Exploratory Data Analysis

Visualization of import and export trends

Seasonal pattern analysis

Decomposition of time series

3️⃣ Statistical Forecasting Models

EWMA (Exponentially Weighted Moving Average)

ETS / Holt-Winters Exponential Smoothing

ARIMA

SARIMA

4️⃣ Volatility Modeling

GARCH (Generalized Autoregressive Conditional Heteroskedasticity)

5️⃣ Deep Learning Models

LSTM (Long Short-Term Memory)

CNN + LSTM Hybrid Model

6️⃣ Hybrid Forecasting Model

GARCH + LSTM integration

7️⃣ Forecast Evaluation

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Mean Absolute Percentage Error (MAPE)

R² Score

🤖 Models Used
1️⃣ Statistical Models

EWMA

ETS Decomposition

Holt-Winters Exponential Smoothing

ARIMA

SARIMA

GARCH

2️⃣ Deep Learning Models

LSTM

CNN + LSTM

3️⃣ Hybrid Models

GARCH + LSTM

These models were used to compare forecasting performance between traditional econometric models and neural networks.

📈 Key Techniques

Time Series Decomposition

Stationarity Testing (ADF Test)

Residual Analysis

Volatility Modeling

Deep Learning Forecasting

Hybrid Modeling

🛠️ Technologies Used
Programming Language

Python

Libraries

Pandas

NumPy

Matplotlib

Statsmodels

Scikit-learn

TensorFlow / Keras

XGBoost

ARCH (for GARCH models)

📊 Evaluation Metrics

Model performance is evaluated using:

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

MAPE (Mean Absolute Percentage Error)

R² Score

These metrics help compare forecasting accuracy across models.

📁 Project Structure
Crude-Oil-Forecasting
│
├── Final year Capstone - Crude Oil import and Export Forecasting.ipynb
├── dataset/
│   └── crude_oil_data.csv
├── README.md
└── requirements.txt

🚀 How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/yourusername/crude-oil-forecasting.git
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Open the notebook
Run using:
Jupyter Notebook
Google Colab
VSCODE 

📊 Results
The project compares the forecasting performance of:

Statistical models

Deep learning models

Hybrid models

Deep learning models such as LSTM and CNN+LSTM show improved forecasting capability when capturing complex patterns in crude oil demand and supply.

📌 Applications
This project can be useful for:
  1. Energy demand forecasting
  2. Government policy planning
  3. Oil import/export management
  4. Economic trend analysis
  5. Energy sector research

👨‍💻 Author
Rahul Raj S Suthrave
thatsrightrahulraj@gmail.com
Final Year Capstone Project

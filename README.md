# 📈 Stock Price Analysis & Forecasting – Major Project

## 📌 Project Overview
This is a **Major Project** focused on **Stock Price Analysis and Forecasting** using **Machine Learning and Time Series models**.  
The project analyzes historical stock market data and applies multiple models to predict future stock prices, with a special focus on **Netflix stock price**.

The project demonstrates the **complete data science workflow**:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Machine learning modeling
- Time series forecasting
- Deep learning
- Model comparison and business insights

---

## 🎯 Project Objectives
- Analyze historical stock price data
- Understand relationships between stock prices and market factors
- Build baseline and advanced predictive models
- Compare traditional ML, time-series, and deep learning approaches
- Forecast future stock prices
- Derive meaningful business insights

---

## 📂 Project Structure

Stock_Price_Analysis_Major/
│
├── 01_Data_Preprocessing_and_EDA.ipynb
├── 02_Linear_Regression_Model.ipynb
├── 03_ARIMA_Stationarity_and_Forecasting.ipynb
├── 04_LSTM_Stock_Price_Prediction.ipynb
├── 05_Model_Comparison_and_Insights.ipynb
│
├── US_Stock_Data.csv
└── README.md

---


---

## 🧾 Dataset Description
**Dataset Used:** `US_Stock_Data.csv`

The dataset contains historical financial data including:
- Date
- Netflix stock price
- Crude oil price
- Natural gas price
- Market indices (S&P 500, Nasdaq, etc.)
- Trading volume and related indicators

---

## 🛠️ Technologies Used
- **Python**
- **Google Colab**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Statsmodels**
- **TensorFlow / Keras**
- **GitHub**

---

## 📘 Notebook-wise Explanation

### 🔹 01_Data_Preprocessing_and_EDA.ipynb
- Data loading and cleaning
- Handling missing values
- Date conversion and sorting
- Feature engineering
- Exploratory Data Analysis (EDA)
- Trend analysis and correlation visualization

---

### 🔹 02_Linear_Regression_Model.ipynb
- Baseline machine learning model
- Feature selection including lag variables
- Time-series-aware train-test split
- Model evaluation using MAE, RMSE, and R²
- Residual analysis and interpretation

---

### 🔹 03_ARIMA_Stationarity_and_Forecasting.ipynb
- Stationarity check using ADF test
- Differencing to achieve stationarity
- ARIMA model implementation
- Short-term stock price forecasting
- Evaluation using error metrics

---

### 🔹 04_LSTM_Stock_Price_Prediction.ipynb
- Data normalization using MinMaxScaler
- Sequence creation for time-series input
- LSTM deep learning model
- Training and prediction
- Performance evaluation
- Visualization of actual vs predicted prices

---

### 🔹 05_Model_Comparison_and_Insights.ipynb
- Comparison of all models (Linear Regression, ARIMA, LSTM)
- Model performance comparison using RMSE and MAE
- Best model selection
- Business insights
- Limitations and future scope
- Final conclusion

---

## 📊 Model Comparison Summary

| Model | Description | Performance |
|------|------------|------------|
| Linear Regression | Baseline ML model | Moderate |
| ARIMA | Statistical time-series model | Improved |
| LSTM | Deep learning time-series model | Best |

---

## 📌 Key Insights
- Stock prices show strong dependency on historical values
- Time-series models outperform simple regression
- LSTM captures long-term dependencies effectively
- Short-term forecasting is more reliable than long-term forecasting

---

## ⚠️ Limitations
- Models rely on historical data only
- Sudden market events are not captured
- External factors like news sentiment are not included

---

## 🚀 Future Scope
- Integration of real-time stock market APIs
- Sentiment analysis using financial news
- Advanced deep learning models (Transformers)
- Web-based dashboard deployment

---

## 👨‍🎓 Acknowledgement
This project was developed as part of the **AI & Machine Learning Training and Internship Program conducted by Skill Ladder**.  
I would like to thank **Skill Ladder** for their guidance, mentorship, and learning resources throughout the program.

---

## 👤 Author
**Yogesh Negi**  
AI & Machine Learning Trainee  
Skill Ladder Training & Internship Program

---

## 📎 How to Run the Project
1. Open **Google Colab**
2. Upload the notebook files
3. Upload `US_Stock_Data.csv`
4. Run the notebooks in sequence:
   - 01 → 02 → 03 → 04 → 05

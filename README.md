# 📈 Apple Stock Price Analysis and Prediction

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** and **Machine Learning** on Apple's historical stock market data. The goal is to understand stock price trends, visualize important patterns, and build a simple Linear Regression model to predict future stock prices.

This project demonstrates the complete Data Science workflow from data preprocessing to prediction.

---

## 🎯 Objectives

* Load and preprocess stock market data
* Perform Exploratory Data Analysis (EDA)
* Visualize stock price trends
* Analyze feature relationships using a correlation heatmap
* Train a Linear Regression model
* Evaluate model performance
* Predict Apple's future stock price

---

## 📂 Dataset

**Dataset:** `apple_stock.csv`

The dataset contains Apple's historical stock prices with the following columns:

* Date
* Open
* High
* Low
* Close
* Volume

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📊 Project Workflow

1. Import libraries
2. Load dataset
3. Data cleaning
4. Convert data types
5. Handle missing values
6. Exploratory Data Analysis (EDA)
7. Feature Engineering
8. Train-Test Split
9. Train Linear Regression Model
10. Evaluate Model
11. Predict Future Stock Price
12. Visualize Results

---

## 📈 Visualizations

The project includes:

* Closing Price Trend
* Trading Volume Analysis
* Histogram of Closing Prices
* Box Plot for Outlier Detection
* Correlation Heatmap
* Actual vs Predicted Price Comparison

---

## 🤖 Machine Learning Model

**Algorithm Used**

* Linear Regression

### Feature

* Day (Time Index)

### Target

* Closing Stock Price

---

## 📊 Model Evaluation Metrics

The model is evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 🔮 Future Prediction

The model predicts Apple's stock price 30 trading days into the future.

Example:

```python
future_day = pd.DataFrame({"Day": [len(df) + 30]})
future_price = model.predict(future_day)

print(f"Predicted Price: ${future_price[0]:.2f}")
```

---

## 📁 Project Structure

```text
Apple-Stock-Price-Prediction/
│
├── apple_stock.csv
├── Stock_Prediction.ipynb
├── README.md
└── images/
    ├── closing_price.png
    ├── volume.png
    ├── histogram.png
    ├── boxplot.png
    ├── heatmap.png
    └── actual_vs_predicted.png
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Apple-Stock-Price-Prediction.git
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the Jupyter Notebook

```bash
jupyter notebook
```

4. Run all cells.

---

## 📚 Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Engineering
* Machine Learning
* Linear Regression
* Model Evaluation
* Time Series Data Analysis
* Financial Data Analysis

---

## 📌 Future Improvements

* Use Moving Average features
* Add Lag Features
* Predict multiple days ahead
* Implement Random Forest Regression
* Implement XGBoost
* Build an LSTM Deep Learning model
* Deploy the project using Streamlit

---

## 📄 License

This project is created for educational and learning purposes.

---

## 👨‍💻 Author

**Subrat Kumar Sahoo**

* GitHub: https://github.com/ssubratkumar106-blip
* Portfolio: https://ssubratkumar106-blip.github.io/Portfoilo-Of-Subrat/

If you found this project helpful, consider giving it a ⭐ on GitHub.

# 🛒 Walmart Sales Prediction 📈

A machine learning project that forecasts weekly sales for Walmart stores using historical data. This model helps predict future sales trends, aiding in better inventory and business planning decisions.

---

## 🧠 Problem Statement

Retail companies like Walmart face challenges in anticipating sales due to seasonal effects, store events, and economic factors. The goal of this project is to build a predictive model to estimate weekly sales based on historical performance, holiday events, and store-specific data.

---

## 🛠 Technologies Used

- Python 3.x  
- Pandas, NumPy for data manipulation  
- Scikit-learn for modeling  
- Matplotlib & Seaborn for visualizations  
- Jupyter Notebook  
- XGBoost, Random Forest, and Linear Regression  

---


## 📁 Project Structure

```
Walmart-sales-prediction/
├── data/                 # Raw and cleaned data files
├── notebooks/            # Jupyter notebooks for EDA & modeling
├── models/               # Trained model files
├── src/                  # Python scripts (if applicable)
├── Walmart_Sales.ipynb   # Main notebook
├── requirements.txt
└── README.md



---

## 🔍 Exploratory Data Analysis

- Time-series sales patterns  
- Holiday effects on sales  
- Correlation between features (temperature, fuel price, etc.)  
- Boxplots and heatmaps for outlier detection  
- Sales per store and department  

---

## 📊 Models & Performance

| Model               | RMSE       | R² Score   |
|--------------------|------------|------------|
| Linear Regression   | 38,400     | 0.49       |
| Random Forest       | 34,200     | 0.65       |
| XGBoost Regressor   | 32,500     | 0.70       |

> ✅ XGBoost outperformed others with the best prediction accuracy.

---

## ▶️ How to Run This Project

```bash
git clone https://github.com/Mounika-malluri/Walmart-sales-prediction
cd Walmart-sales-prediction
pip install -r requirements.txt
jupyter notebook Walmart_Sales.ipynb
```
---

## 📈 Future Work

- Tune hyperparameters using GridSearchCV  
- Add macroeconomic indicators (e.g., CPI, unemployment rate)  
- Deploy as an interactive dashboard using Streamlit  
- Add more detailed holiday impact features

---

## 📌 License

This project is licensed under the MIT License.

---

## 🙋‍♀️ Author

**Mounika Malluri**  




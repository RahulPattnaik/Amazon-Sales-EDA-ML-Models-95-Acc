# 📊 Amazon Product Dataset Analysis

## 📌 Project Overview

This project analyzes an Amazon product dataset (1,465 rows, 16 columns) scraped using BeautifulSoup and WebDriver. It explores pricing strategies, discount patterns, ratings, and reviews, and applies machine learning models to predict discounted prices.

## 📂 Dataset

* **Rows:** 1,465
* **Columns:** 16
* **Features:** Product ID, Name, Category, Prices, Discounts, Ratings, Reviews, Product Links
* **Source:** Scraped from Amazon (for learning purposes only)

## ⚙️ Workflow

1. **Data Collection** – Scraping Amazon with BeautifulSoup & Selenium WebDriver
2. **Data Preprocessing** – Cleaning, handling missing values, encoding, feature engineering
3. **Exploratory Data Analysis (EDA)** – Histograms, scatter plots, correlation heatmaps, distribution of discounts & ratings
4. **Modeling** – Linear Regression, Decision Tree, Random Forest, Gradient Boosting, XGBoost
5. **Evaluation** – Comparing models using RMSE, MAE, and R²

## 📈 Results

* Discounts between 40–70% are most common
* Majority of products have 4★ ratings
* **XGBoost outperformed all models** with RMSE = 0.16 and R² = 0.97

## 🚀 Tech Stack

* **Languages:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, XGBoost
* **Tools:** Jupyter Notebook, Anaconda

## 📝 How to Run

1. Clone this repository

  git clone https://github.com/your-username/amazon-analysis.git

2. Install dependencies

  pip install -r requirements.txt

3. Open Jupyter Notebook and run the analysis

 jupyter notebook


## 📌 Future Work

* Add sentiment analysis on customer reviews
* Deploy predictive model as a web app

## 🙌 Acknowledgments

This project is for educational purposes and uses publicly available Amazon product data.

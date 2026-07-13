# 📈 Financial Stock Price Data Analytics & Feature Engineering

## 📌 Overview

This project focuses on performing exploratory data analysis (EDA) and feature engineering on historical stock market data to uncover trends, patterns, and meaningful financial indicators.
The objective of this project is to build a structured data analytics workflow that includes data cleaning, transformation, visualization, and creation of analytical features that can support further financial analysis.
The focus is on preparing and analyzing financial time-series data through a complete data analytics pipeline.

## 📂 Project Structure
```
├── Images/                               # Visualizations generated during analysis
├── stock_price_data.csv                  # Dataset containing marketing information
├── Finance_Stock_Data_Analytics.ipynb    # Jupyter Notebook with analysis and findings
├── README.md                             # Project documentation
```
## 📊 Dataset

The dataset contains historical stock market information used for financial data exploration and analysis.

### Dataset Features:

- Open: Opening stock price

- High: Highest price during trading session

- Low: Lowest price during trading session

- Close: Closing stock price

- Volume: Number of shares traded

## ⚙️ Installation

### 1️⃣ Clone the repository:

```bash
git clone https://github.com/asna-amjad/Marketing_Department_Project.git](https://github.com/asna-amjad/Finance-Stock-Price-Data-Analytics-Project.git
cd Finance-Stock-Price-Data-Analytics-Project
```

### 2️⃣ Install dependencies:

Ensure you have the following Python packages installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## 🔍 Methodology

**1. Data Loading & Understanding**
* Imported financial datasets using Python
* Reviewed dataset structure and data types
* Checked summary statistics

**2. Data Cleaning & EDA**
Performed data quality checks including:
* Handling missing values
* Removing duplicate records
* Check Correlation

**Visualizations included:**
Here are some visualizations from the project:

  ![alt text](https://github.com/asna-amjad/Finance-Stock-Price-Data-Analytics-Project/blob/4992a47575dd990c2158e3e80e7c73b365c938e4/Images/plot1.png)
  ![alt text](https://github.com/asna-amjad/Finance-Stock-Price-Data-Analytics-Project/blob/4992a47575dd990c2158e3e80e7c73b365c938e4/Images/corrplot2.png)

**4. Feature Engineering**
Created additional analytical features to better understand stock behavior.
Feature engineering steps included:

* Add basic features for future time series problems
* Moving averages
* Rolling statistics
* Volatility measurements
These engineered features provide additional insights into market trends and price behavior.

## 🛠️ Technologies Used

- **Python**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **Jupyter Notebook**
- **Git & GitHub**

## 🚀 Future Improvements
Future enhancements for this project may include:
* Building interactive dashboards using Tableau
* Performing comparative analysis across multiple companies
* Integrating real-time stock market APIs
* Developing statistical models for deeper financial analysis
* Applying machine learning models for future predictive analysis

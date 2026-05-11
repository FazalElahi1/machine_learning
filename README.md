

# 📈 Stock Market Analysis & Machine Learning Project

🚀 A complete **data analysis and machine learning project** that explores stock market data, performs deep exploratory analysis, visualizes trends, and builds a classification model using **Decision Tree Classifier**.

---

## 📌 Project Overview

This project analyzes stock market data to uncover insights such as:

* 📊 Stock price trends
* 🏢 Company performance comparison
* 📉 Volume vs price behavior
* 🤖 Machine learning-based company classification

It combines **Data Analysis + Visualization + Machine Learning** in a single pipeline.

---

## 🧰 Tech Stack

* 🐍 Python
* 🧮 Pandas & NumPy
* 📊 Matplotlib & Seaborn
* 🤖 Scikit-learn

---

## 📂 Dataset

The dataset (`stock.csv`) includes:

* 🏢 Company
* 📅 Date
* 💰 Open, High, Low, Close Prices
* 📦 Volume
* 📈 Price

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing

* Removed missing values
* Converted currency columns into numeric format
* Sorted data by date
* Handled data cleaning issues

---

### 2️⃣ Exploratory Data Analysis (EDA)

* 📌 Highest price & volume analysis
* 📌 Company-wise performance comparison
* 📌 Average stock behavior analysis

---

### 3️⃣ Feature Engineering

Created additional insights for specific company (AAPL):

* 📊 Price Range = High - Low
* 📉 Price Difference = Price - Open

---

### 4️⃣ Data Normalization

* Applied **MinMaxScaler** for scaling numerical features

---

### 5️⃣ Data Visualization 📊

Includes multiple visualizations:

* 🔥 Heatmaps (Price trends)
* 📈 Line plots (Yearly performance)
* 📊 Bar charts (Average price comparison)
* 📉 Scatter plots (Volume vs Price)
* 📦 Box plots (Price distribution)
* 🥧 Pie charts (Market share view)
* 📊 Stack plots (Company trends over time)

---

### 6️⃣ Machine Learning Model 🤖

* Model: **Decision Tree Classifier**
* Features:

  * Open
  * High
  * Low
  * Volume
* Target:

  * Company classification

---

### 7️⃣ Model Evaluation 📏

Performance metrics used:

* 🎯 Accuracy Score
* 🎯 Precision Score
* 🎯 Recall Score

---

## 📊 Results

The model successfully classifies companies based on stock behavior patterns and achieves measurable performance using evaluation metrics.

---

## 🚀 How to Run the Project

### 1️⃣ Clone Repository

```bash
git clone https://github.com/FazalElahi1/machine_learning.git
```

### 2️⃣ Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3️⃣ Run Script

```bash
python main.py
```

---

## 🔮 Future Improvements

* 📉 Add stock price prediction (Regression models)
* 📡 Integrate real-time stock API
* 📊 Build interactive dashboard (Streamlit / Dash)
* 🤖 Try advanced ML models (Random Forest, XGBoost)
* 📈 Add time-series forecasting (LSTM)

---

## 👨‍💻 Author

**Fazal Elahi**

📊 Machine Learning | Decision Tree Classifier 

---


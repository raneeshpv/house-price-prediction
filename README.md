# 🏠 House Price Prediction

A machine learning project that predicts house prices using the **XGBoost Regression** algorithm.

## 📌 Project Overview

This project uses the Boston House Price dataset to build a regression model for predicting house prices based on property and neighborhood features.

The project includes:

* Data loading and exploration
* Missing-value checking
* Statistical analysis
* Correlation analysis
* Train-test splitting
* XGBoost model training
* Model evaluation
* Actual vs. predicted price visualization

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

## ⚙️ Machine Learning Workflow

```text
Dataset
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Correlation Analysis
   ↓
Train / Test Split
   ↓
XGBoost Regression
   ↓
Prediction
   ↓
Model Evaluation
```

## 🤖 Model

The project uses **XGBRegressor** from XGBoost for house price prediction.

The dataset is divided into:

* **80% training data**
* **20% testing data**

The model is evaluated using:

* **R² Score**
* **Mean Absolute Error (MAE)**

## 📊 Visualization

The project includes a visualization comparing:

**Actual Prices vs. Predicted Prices**

This helps evaluate how closely the model's predictions follow the actual house prices.

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/raneeshpv/house-price-prediction.git
```

### 2. Install the required libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

### 3. Run the Python file

```bash
python house_price_prediction.py
```

You can also open the `.ipynb` notebook using **Jupyter Notebook** or **Google Colab**.

## 📁 Project Files

```text
house-price-prediction/
│
├── house_price_prediction.py
├── house_price_prediction.ipynb
└── README.md
```

## 👨‍💻 Author

**Abdul Raneesh P V**

B.Tech Computer Science and Engineering
National Institute of Technology, Calicut

GitHub: [raneeshpv](https://github.com/raneeshpv)

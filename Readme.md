# 🍽️ Food Delivery Time Prediction

Predicting the estimated delivery time for food orders using machine
learning.

## 📌 Overview

This project focuses on forecasting delivery time based on various
features like distance, weather, traffic, and delivery partner
performance. It utilizes core Supervised Learning concepts, especially
**Linear Regression**, to model and evaluate delivery time predictions.

## 🚀 Features

-   Clean and processed dataset
-   Exploratory Data Analysis (EDA)
-   Feature engineering
-   Linear Regression model
-   Train/Test split
-   Evaluation using MAE, MSE, RMSE, R²
-   Easy-to-run structure

## 🧠 Machine Learning Concepts Used

-   Supervised Learning
-   Linear Regression
-   Train-Test Split
-   Cost Function
-   Model Evaluation Metrics


## 📊 Dataset

Typical columns include: - 'Order_ID', 'Distance_km', 'Weather', 'Traffic_Level', 'Time_of_Day',
       'Vehicle_Type', 'Preparation_Time_min', 'Courier_Experience_yrs',
       *('Delivery_Time_min)*

## 🧪 Model Evaluation

Metrics used: - **MAE** - **MSE** - **RMSE** - **R² Score**

Score = 81%
## ▶️ How to Run

1.  Clone the repo:

    ``` bash
    git clone https://github.com/pryainshu/food-delivery-prediction.git
    ```

2.  Install dependencies:

    ``` bash
    pip install -r requirements.txt
    ```

3.  Run the notebook:

    ``` bash
    jupyter notebook main.ipynb
    ```

## 📦 Technologies Used

-   Python
-   Pandas & NumPy
-   Matplotlib, Seaborn
-   Scikit-learn
-   Jupyter Notebook

## 💡 Future Improvements

-   Add Random Forest, XGBoost models
-   Hyperparameter tuning
-   Add a Streamlit interface
-   Convert code into automated ML pipeline

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

## 📄 License

Licensed under the **MIT License**.

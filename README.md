#  House Price Prediction (Linear Regression)

A Jupyter Notebook-based project that demonstrates how to predict house prices using a simple **linear regression** model. Built using Python and designed for educational purposes and quick experimentation.

---

##  Repository Overview

```

├── HousingData.csv         # Dataset containing housing features and prices
├── linear\_regression.ipynb # Jupyter Notebook with data exploration, model training, and evaluation
└── README.md               # Project documentation (this file)

````

---

##  Purpose

This project aims to predict house prices using the linear regression algorithm. It walks you through:

- Loading and inspecting the housing dataset
- Performing exploratory data analysis (EDA)
- Training a linear regression model
- Evaluating performance with metrics like Mean Squared Error (MSE) and R²

---

##  Dataset

The `HousingData.csv` file contains typical features used in real estate price prediction:

| Column                   | Description                                  |
|--------------------------|----------------------------------------------|
| `Avg. Area Income`       | Average income of households in the area     |
| `Avg. Area House Age`    | Average age of houses in the area            |
| `Avg. Area Number of Rooms` | Average number of rooms                    |
| `Avg. Area Number of Bedrooms` | Average number of bedrooms              |
| `Area Population`        | Population of the area                       |
| `Price`                  | Actual house price (target)                  |
| `Address`                | Physical address of the house                |

---

##  Getting Started

### 1. Clone this repository:

```bash
git clone https://github.com/manishgk9/house_price_prediction_linear_regression.git
cd house_price_prediction_linear_regression
````

### 2. Install required packages:

```bash
pip install numpy pandas scikit-learn matplotlib notebook
```

### 3. Launch the notebook:

```bash
jupyter notebook linear_regression.ipynb
```

---

## What’s in the Notebook (`linear_regression.ipynb`)

1. **Importing libraries**: `pandas`, `numpy`, `matplotlib`, `scikit-learn`
2. **Loading data** from `HousingData.csv`
3. **Exploratory Data Analysis (EDA)**: visualizations of relationships between features and price
4. **Data Preprocessing**: train-test splitting
5. **Training** a linear regression model
6. **Evaluating** using MSE and R²
7. **Visualizing** predictions vs actual values

---

## Future Improvements

* Experiment with polynomial or regularized regression (Ridge, Lasso)
* Try more complex models (Decision Trees, Random Forests, XGBoost)
* Add cross-validation for better evaluation
* Deploy as a simple web app using Flask or Streamlit

---

## License

Feel free to use this project for learning and experimentation. Attribution appreciated!

---

### Questions or suggestions?

Let me know — happy to help!

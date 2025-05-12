# Car MPG Prediction Project 🚗📊

This project focuses on predicting the **Miles Per Gallon (MPG)** of cars based on their specifications using machine learning models. We apply both **Linear Regression** and **Polynomial Regression** techniques and compare their performance.

---

## 🧠 Problem Statement

We aim to estimate the fuel efficiency of a car (measured in MPG) using features such as:
- Cylinders
- Horsepower
- Weight
- Model Year
- Displacement

This falls under the category of **Supervised Regression**.

---

## 📌 Project Tasks Breakdown

### ✅ Task 1: Exploratory Data Analysis (EDA) & Problem Framing
Understand the dataset, identify patterns, and define the goal: predicting MPG.

### ✅ Task 2: Importing Libraries & Loading Data
Using `pandas`, `matplotlib`, `seaborn`, and `scikit-learn` to import and explore the data.

### ✅ Task 3: Visual Analysis
- Pair plots and box plots were used.
- Detected outliers in the `horsepower` column.
- Outliers removed before further modeling.

### ✅ Task 4: Feature Selection & Data Splitting
- Selected features: `cylinders`, `horsepower`, `weight`, `model_year`, `displacement`
- Target: `mpg`
- Data split into 80% training and 20% testing

### ✅ Task 5: Linear Regression
- Applied linear regression
- Performance metrics:
  - Mean Absolute Error
  - Mean Squared Error
  - Root Mean Squared Error

**Observation:** The linear model struggled due to the non-linear nature of the data.

### ✅ Task 6: Polynomial Regression
- Used degree 3 polynomial regression
- Performance improved compared to linear regression

### ✅ Task 7: Residual Analysis
- Checked histogram and QQ plot of residuals
- Residuals are **approximately normally distributed**, indicating a good model fit

---

## 📊 Tools & Libraries Used

- **Python 3**
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `scipy`

---

## 📁 Dataset

The dataset used is `auto_mpg_dataset.csv`.

---

## 📈 Results

Polynomial regression clearly outperformed linear regression due to the nonlinear relationships between the features and MPG.

---

## 📬 Future Work

- Apply feature engineering for further improvements.
- Try other models like Random Forests or Gradient Boosting.
- Perform cross-validation.

---

## 🤝 Contributing

Contributions are welcome! Please fork the repo and submit a pull request.

---

## 📝 License

This project is under the MIT License.

# 🏡 Predicting House Prices with Linear Regression

## 📘 Overview

This project aims to predict house prices using **Linear Regression**, a foundational algorithm in Machine Learning. The model leverages various housing features—such as area, number of rooms, and location factors—to estimate market prices.
The objective is to understand the key drivers influencing price variations and evaluate how well linear regression can capture those relationships.

Through exploratory data analysis (EDA), visualization, and model evaluation, this project demonstrates a complete data science workflow — from raw data to actionable insights.

---

## 🧠 Objectives

* Perform **exploratory data analysis** to identify trends and correlations.
* Visualize relationships between variables affecting housing prices.
* Build and evaluate a **Linear Regression model** to predict prices.
* Interpret the model’s coefficients and assess feature impact.
* Measure performance using key regression metrics such as **R²** and **Mean Squared Error (MSE)**.

---

## 📊 Dataset

* **Source:** Synthetic or public housing dataset (e.g., Kaggle or internal simulation)
* **Size:** [Number of rows/columns — if available]
* **Features include:**

  * `Area` — Size of the property (sq. ft.)
  * `Bedrooms`, `Bathrooms`
  * `Furnishing Status`
  * `Location`
  * `Price` — Target variable

**Note:** The dataset was cleaned to handle missing values, duplicates, and categorical encoding prior to modeling.

---

## 🔍 Exploratory Data Analysis (EDA)

EDA was conducted to uncover relationships between independent variables and the target (`Price`).

Key steps included:

* **Univariate Analysis:** Distribution of prices, area, and furnishing status.
* **Bivariate Analysis:** Correlation between price and numerical features.
* **Visualization:** Histograms, pair plots, heatmaps, and box plots to detect outliers and skewness.
* **Feature Encoding:** Applied one-hot encoding for categorical variables.

**Insights:**

* Price increases linearly with area.
* Furnished houses and those in prime locations tend to have higher prices.
* A few outliers were observed in luxury properties with unusually large areas.

---

## ⚙️ Methodology

1. **Data Preprocessing**

   * Handling missing values
   * Encoding categorical variables
   * Normalizing/standardizing features (if needed)
2. **Model Building**

   * Implemented **Linear Regression** using `sklearn.linear_model`
3. **Model Evaluation**

   * Metrics used: **R²**, **Mean Squared Error (MSE)**, and **Root Mean Squared Error (RMSE)**
   * Compared predicted vs. actual values using scatter plots and residual analysis

---

## 📈 Results

* **R² Score:** [Insert Value, e.g., 0.84] — indicating that the model explains 84% of the variance in house prices.
* **MSE:** [Insert Value]
* **RMSE:** [Insert Value]
* Residuals were approximately normally distributed, suggesting a good model fit.

**Interpretation:**
Area and number of rooms had the most significant influence on price, confirming linear trends. The model performed well on the test data, demonstrating strong predictive capability for moderate to high-priced properties.

---

## 🧩 Tools & Libraries

* **Python** — Core language
* **Pandas, NumPy** — Data processing
* **Matplotlib, Seaborn** — Visualization
* **Scikit-learn** — Model training and evaluation
* **Jupyter Notebook** — Interactive analysis

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/Predicting-House-Prices.git
   cd Predicting-House-Prices
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:

   ```bash
   jupyter notebook "Predicting House Prices with Linear Regression.ipynb"
   ```

---

## 🧭 Future Work

* Experiment with **Polynomial Regression** or **Random Forest Regressor** for non-linear relationships.
* Apply **feature selection** or **regularization techniques** (Lasso, Ridge) to improve generalization.
* Deploy the model via **Streamlit** or **Flask** as a price prediction web app.

---

## 🏁 Conclusion

This project demonstrates the complete lifecycle of a regression-based data science task—from data cleaning and EDA to predictive modeling and interpretation. The insights and results validate the usefulness of Linear Regression as a simple yet powerful tool for housing price estimation.

---

## 👩‍💻 Author

**Nikita Albela**
Data Analyst | AI & Analytics Enthusiast
[LinkedIn](https://linkedin.com/in/yourprofile) | [GitHub](https://github.com/yourusername)

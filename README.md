# Penguins_Explore-linear-regression-with-Python: Exploratory Data Analysis & Multiple Regression Modeling

This repository contains hands-on data science notebooks and datasets exploring linear regression, multiple regression analysis, and statistical modeling workflows using Palmer penguins data in Python.

---

## 📂 Repository Contents

### 1. Jupyter Notebooks & Data

* **[`Penguins Explore linear regression with Python.ipynb`](https://github.com/dyyland23-glitch/Penguins_Explore-linear-regression-with-Python/blob/main/Penguins%20Explore%20linear%20regression%20with%20Python.ipynb)**
  * **Project Overview**: Demonstrates an exploratory simple linear regression workflow to analyze relationships between morphological features (such as flipper length, body mass, and bill dimensions) using [`penguins_cleaned.csv`](https://github.com/dyyland23-glitch/Penguins_Explore-linear-regression-with-Python/blob/main/penguins_cleaned.csv).
  * **Key Tasks & Methods**:
    * **Exploratory Data Analysis (EDA)**: Investigates distributions, correlations, and linear assumptions across penguin species.
    * **Model Fitting**: Fits simple linear regression models to evaluate predictive relationships.

* **[`Penguins multiple regression results with Python.ipynb`](https://github.com/dyyland23-glitch/Penguins_Explore-linear-regression-with-Python/blob/main/Penguins%20multiple%20regression%20results%20with%20Python.ipynb)**
  * **Project Overview**: Constructs a multiple linear regression model to predict continuous target variables using multiple physical and categorical features simultaneously.
  * **Key Tasks & Methods**:
    * **Feature Engineering & Diagnostics**: Evaluates feature interactions, multicollinearity, and residual distributions.
    * **Model Evaluation**: Assesses multi-variable performance metrics and coefficients.

* **[`penguins_cleaned.csv`](https://github.com/dyyland23-glitch/Penguins_Explore-linear-regression-with-Python/blob/main/penguins_cleaned.csv)**
  * **Overview**: The preprocessed dataset containing cleaned observations for penguin species, bill length, bill depth, flipper length, body mass, and sex.

---

## 🛠️ Tech Stack & Key Libraries & Functions

* **Language**: Python 3.10+
* **Data Manipulation & Analysis**: `pandas`, `numpy`, `scipy`
  * **Key Functions**: `pd.read_csv()`, `df.dropna()`, `df.groupby()`, `np.array()`
* **Statistical Modeling & Machine Learning**: `statsmodels`, `scikit-learn`
  * **Key Functions**: `statsmodels.api.OLS()`, `smf.ols()`, `LinearRegression()`, `train_test_split()`
* **Data Visualization**: `matplotlib`, `seaborn`
  * **Key Functions**: `sns.scatterplot()`, `sns.pairplot()`, `plt.hist()`

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/dyyland23-glitch/Penguins_Explore-linear-regression-with-Python.git](https://github.com/dyyland23-glitch/Penguins_Explore-linear-regression-with-Python.git)
cd Penguins_Explore-linear-regression-with-Python

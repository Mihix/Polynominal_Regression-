# Polynomial Regression

A Jupyter Notebook (`Polynomial_Regression.ipynb`) demonstrating how to model non-linear relationships using **Polynomial Regression** in Python.

## 📌 Overview

Standard linear regression fits a straight line through data, which fails when relationships are complex or curved (e.g., predicting salary growth over a career or disease spread over time). **Polynomial Regression** transforms features into powers ($x^1, x^2, x^3, \dots, x^n$), enabling a linear model to fit a flexible, curved trend line.

$$\hat{y} = \theta_0 + \theta_1 x + \theta_2 x^2 + \dots + \theta_n x^n$$

---

## 🛠️ Tech Stack & Dependencies

* **Python 3.x**
* **scikit-learn** (`PolynomialFeatures`, `LinearRegression`)
* **pandas** & **NumPy** (Data manipulation)
* **matplotlib** / **seaborn** (Visualization)

---

## 🚀 Key Steps in the Notebook

1. **Data Preprocessing:** Load dataset and handle independent ($X$) and dependent ($y$) variables.
2. **Feature Transformation:** Apply `PolynomialFeatures(degree=n)` to generate higher-degree feature terms.
3. **Model Training:** Train a `LinearRegression` model on the transformed polynomial features.
4. **Visualization:** Plot the original scatter data against the fitted polynomial curve.
5. **Evaluation:** Compare prediction results against standard Linear Regression to evaluate improvement.

---

## 📊 Quick Start

Clone the repository and open the notebook using Jupyter:

```bash
git clone <your-repo-url>
cd <your-repo-folder>
jupyter notebook Polynomial_Regression.ipynb

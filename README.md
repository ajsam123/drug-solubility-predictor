# Drug Solubility Prediction Using Multiple Linear Regression

## Project Overview

This project develops a **Multiple Linear Regression** model to predict the **experimentally measured aqueous log solubility** of drug molecules using molecular descriptors.

Drug solubility is an important physicochemical property in pharmaceutical science because it influences drug absorption, bioavailability, formulation, and therapeutic effectiveness. Experimentally determining the solubility of every new compound is expensive and time-consuming. This project demonstrates how machine learning can be used to estimate drug solubility from molecular properties.

---

## 🎯 Objective

To build a machine learning model capable of predicting the measured aqueous log solubility of drug molecules using six molecular descriptors.

---

## Dataset

**Dataset:** Delaney Processed Drug Solubility Dataset

The dataset contains molecular descriptors for each compound together with its experimentally measured log solubility.

### Features

- Minimum Degree
- Molecular Weight
- Number of H-Bond Donors
- Number of Rings
- Number of Rotatable Bonds
- Polar Surface Area

### Target

- Measured Log Solubility (mol/L)

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Machine Learning Workflow

1. Load Dataset
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Feature Selection
5. Train-Test Split
6. Train Multiple Linear Regression Model
7. Predict Drug Solubility
8. Evaluate Model Performance
9. Interpret Results

---

## 📈 Model Performance

| Metric | Value |
|---------|--------:|
| MAE | 0.892 |
| MSE | 1.389 |
| RMSE | 1.179 |
| R² Score | 0.702 |

### Interpretation

The model explains approximately **70.2%** of the variation in experimentally measured drug solubility using the selected molecular descriptors.



## 👤 Author

**Samuel Ajose**

Pharmacy Student | Machine Learning Enthusiast | Frontend Developer

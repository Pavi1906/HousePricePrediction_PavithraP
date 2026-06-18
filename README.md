# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts residential house prices using Machine Learning techniques. The goal is to analyze housing data, identify key factors affecting house prices, perform exploratory data analysis (EDA), and build predictive models.

The project includes data preprocessing, feature engineering, visualization, model training, and evaluation using Linear Regression and Random Forest Regression.

---

## 🎯 Objectives

- Understand the housing dataset through EDA.
- Identify important features affecting house prices.
- Visualize relationships between variables.
- Build predictive machine learning models.
- Compare model performance and determine the better model.

---

## 📂 Dataset

**Dataset:** Housing.csv

The dataset contains information about house characteristics such as:

- Area
- Bedrooms
- Bathrooms
- Stories
- Main Road Access
- Guest Room
- Basement
- Hot Water Heating
- Air Conditioning
- Parking
- Preferred Area
- Furnishing Status
- Price (Target Variable)

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

## 📊 Exploratory Data Analysis (EDA)

The following visualizations were created:

### 1. House Price Distribution
Shows the distribution of house prices in the dataset.

### 2. Correlation Heatmap
Displays relationships between numerical features and the target variable.

### 3. Area vs Price Scatter Plot
Illustrates the relationship between house area and selling price.

### Additional Visualizations
- Top 10 Feature Importances
- Actual vs Predicted House Prices

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Encoded categorical variables
- Feature selection
- Train-Test Split (80:20)

---

## 🤖 Machine Learning Models

### Linear Regression

A baseline regression model used for house price prediction.

### Random Forest Regression

An ensemble learning model used to improve prediction accuracy and capture non-linear relationships.

---

## 📈 Model Evaluation

Models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

### Result

Random Forest Regression achieved better performance than Linear Regression due to its ability to model complex relationships within the housing data.

---

## 📁 Project Structure

```text
HousePricePrediction_PavithraP/
│
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
├── charts/
│   ├── price_distribution.png
│   ├── correlation_heatmap.png
│   ├── area_vs_price.png
│
└── README.md
```

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/Pavi1906/HousePricePrediction_PavithraP.git
```

### Navigate to Project Folder

```bash
cd HousePricePrediction_PavithraP
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
analysis.ipynb
```

and run all cells.

---

## 📌 Key Findings

- Area is one of the strongest predictors of house price.
- Houses with more bathrooms and bedrooms generally have higher prices.
- Preferred area and furnishing status significantly influence pricing.
- Random Forest Regression provides more accurate predictions than Linear Regression.

---

## 👩‍💻 Author

**Pavithra P**

MCA Student  
KCG College of Technology

GitHub: https://github.com/Pavi1906

---

## 📜 Declaration

This project was completed as part of the XYlofy AI Internship Week 1 Assignment and represents my own original work.

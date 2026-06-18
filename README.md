# House Price Prediction using Machine Learning

## Project Overview

This project predicts residential house prices using Machine Learning techniques. The dataset contains information about house characteristics such as area, bedrooms, bathrooms, parking availability, furnishing status, and other amenities.

The objective is to analyze the factors affecting house prices and build predictive models that estimate property values accurately.

---

## Dataset Information

* Total Records: 545
* Total Features: 13
* Target Variable: `price`

### Features

* area
* bedrooms
* bathrooms
* stories
* mainroad
* guestroom
* basement
* hotwaterheating
* airconditioning
* parking
* prefarea
* furnishingstatus

---

## Project Workflow

### 1. Dataset Inspection

* Dataset loading
* Shape and structure analysis
* Data type verification
* Missing value analysis
* Duplicate record analysis

### 2. Data Preprocessing

* Feature validation
* One-Hot Encoding of categorical variables
* Dataset transformation
* Feature-target separation

### 3. Exploratory Data Analysis (EDA)

* House price distribution analysis
* Correlation analysis
* Area vs Price relationship
* Feature importance investigation

### 4. Model Building

Two regression models were developed:

#### Linear Regression

* MAE: 970,043
* RMSE: 1,324,507
* R² Score: 0.653

#### Random Forest Regressor

* MAE: 1,013,969
* RMSE: 1,398,116
* R² Score: 0.613

### 5. Model Evaluation

Models were compared using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### 6. Business Insights

Key findings include:

* Area is the most influential feature affecting house prices.
* Bathrooms significantly impact property value.
* Air conditioning increases house value.
* Parking availability positively influences price.
* Preferred locations command higher prices.
* Unfurnished houses generally have lower market values.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Project Structure

HousePricePrediction_PavithraP/

├── Housing.csv

├── notebook/

│ └── House_Price_Prediction.ipynb

├── report/

│ └── House_Price_Prediction.html

├── charts/

├── dataset/

├── requirements.txt

└── README.md

---

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* Feature engineering
* Model deployment using Streamlit
* Real-time house price prediction application

---

## Author

**Pavithra P**

MCA Student | Data Analytics & Machine Learning Enthusiast


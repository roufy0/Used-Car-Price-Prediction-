# Used Car Price Prediction (Saudi Arabia)

This project builds a machine learning model to predict the price of used cars in Saudi Arabia based on various vehicle features. It combines data cleaning, EDA, feature engineering, and regression modeling.

##  Dataset

The project uses the dataset: `UsedCarsSA_Unclean_EN.csv`, which includes:
- Car brand and model
- Year, transmission, engine size
- Condition, mileage, fuel type
- Price (target variable)

##  Preprocessing Steps

- Missing value imputation (e.g. with `SimpleImputer`)
- One-hot encoding for categorical variables
- Train-test split (typically 80/20)
- Pipeline creation for consistent preprocessing

## Exploratory Data Analysis

- Distributions of price and mileage
- Correlation heatmaps
- Price vs. features (e.g. year, engine size, transmission)

##  Models Used

- **Linear Regression**
- **Random Forest Regressor**

##  Evaluation Metrics

- Mean Squared Error (MSE)
- R² Score (Coefficient of Determination)

##  Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

##  How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-user/UsedCarPricePredictor.git
   cd UsedCarPricePredictor

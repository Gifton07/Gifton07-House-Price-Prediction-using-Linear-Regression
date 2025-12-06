# Gifton07-House-Price-Prediction-using-Linear-Regression

# Real Estate Price Prediction

This project builds a Linear Regression model to predict real-estate prices using property features such as square footage, year built, and number of bedrooms.

## 📊 Key Insights from EDA
- Dataset has 500 rows and no missing values.
- Price is strongly correlated with `Num_Bedrooms`, `Square_Feet`, and `Year_Built`.
- Visualizations show clear positive relationships between price and major features.

## 🧮 Linear Regression Model
The model uses:
ID, Has_Garden, Num_Bathrooms, Num_Bedrooms, Square_Feet, Year_Built.

**General Equation:**
Price = β0 + β1(ID) + β2(Has_Garden) + ... + β6(Year_Built)

## 📈 Model Performance
- **R²:** 0.8746  
- **RMSE:** 44,632.60  
- Strong predictive power with some variance unexplained due to inherent noise.

## 📂 Outputs
- `actual_vs_predicted.png`
- `predictions_vs_actual.csv`

These files show the model’s performance and allow further analysis.

# Airbnb Price Regressor

A machine learning project to predict nightly Airbnb prices using various regression models and feature engineering techniques.

---

## Overview
- **Goal:** Predict nightly Airbnb listing prices.
- **Data:** Airbnb dataset with features like room type, amenities, location, and more.
- **Models tested:**
  - Linear Regression
  - Gradient Boosted Decision Trees (GBDT)
  - Random Forest

---

## Tech Stack
- **Languages & Tools:** Python, Jupyter Notebook  
- **Libraries:**  
  - Pandas → Data cleaning & tabular processing  
  - Scikit-learn → Model building, preprocessing, evaluation  
  - Matplotlib / Seaborn → Data visualization & trend analysis  

---

## How It Works
1. **Data Cleaning & Preparation**  
   - Removed invalid/missing entries.  
   - Converted categorical variables (e.g., room type) into numerical form using one-hot encoding.  
   - Parsed amenities from strings into sets for efficient lookup.

2. **Exploratory Data Analysis (EDA)**  
   - Visualized price distribution, outliers, and trends.  
   - Examined relationships between features (e.g., room type, location) and price.

3. **Feature Engineering**  
   - Extracted additional features from existing columns (e.g., count of amenities).  
   - Improved categorical encoding for better predictive performance.

4. **Model Training & Testing**  
   - Applied scaling and encoding pipelines.  
   - Trained and compared multiple regression models.  
   - Evaluated performance using metrics such as RMSE and R².

---

## Optimizations
- Enhanced categorical feature encoding for **Room Type** and **Amenities**.  
- Used **parsed string-to-set** conversions before one-hot encoding for faster processing.  
- Performed hyperparameter tuning for GBDT and Random Forest to improve accuracy.

---

## Potential Future Improvements
- Include geospatial features such as distance to city center.  
- Try deep learning models for potential accuracy gains.  

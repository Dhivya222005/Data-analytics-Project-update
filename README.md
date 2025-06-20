# Data-analytics-Project-update
Project update
# Airbnb Dynamic Pricing Recommendation Engine

This project aims to build a simple and effective **dynamic pricing recommendation system** for Airbnb listings based on location, seasonality, reviews, and listing characteristics.

## 🔍 Objective

To analyze historical Airbnb data and provide **optimal price suggestions** using a machine learning model.

---

## 📁 Files

- `listings.csv` – Raw Airbnb dataset
- `airbnb_dynamic_pricing_code.py` – Python script for data cleaning, model building, and price suggestion
- `airbnb_cleaned.csv` – Cleaned dataset ready for visualization in Tableau

---

## 🛠️ Tools Used

- **Python**
  - Pandas, NumPy
  - Scikit-learn (LinearRegression)
  - Seaborn, Matplotlib
- **Excel**
  - For initial data inspection
- **Jupyter Notebook**
  - For step-by-step implementation and testing

---

## 🧪 Steps Performed

1. **Data Cleaning**  
   - Removed missing prices
   - Handled nulls in reviews
   - Converted categorical columns into dummies

2. **Feature Selection**
   - Kept relevant columns like `room_type`, `reviews`, `availability`, etc.

3. **Model Training**
   - Used Linear Regression to predict price
   - Evaluated using Mean Squared Error

4. **Price Prediction Function**
   - Custom function to suggest price based on inputs

---

## 📊 Next Steps (Not in this repo yet)

- Build an interactive Tableau dashboard using `airbnb_cleaned.csv`
- Add filters and price sliders for user exploration

---

## 📌 Example Output

```python
suggest_price(50, 1.5, 180, 'Brooklyn', 'Entire home/apt')
# Output: Suggested Price: $XYZ


# Housing Prices Analysis - San Antonio

## **Objective**
Predict long-term housing price trends in San Antonio using Zillow data and linear regression.

## **Dataset**
- **Source**: Zillow Home Prices dataset
- **Columns**:
  - `RegionName`: City name
  - `CountyName`: County
  - `State`: State
  - `Date columns`: Monthly median home prices from 2000 to 2024

## **Key Analyses**
1. **Exploratory Data Analysis (EDA)**
   - Filtered data for San Antonio
   - Plotted historical housing prices (2000-2024)
   
2. **Linear Regression Model**
   - Trained on past housing prices
   - Predicted home prices for the next **50 years** (until 2074)

3. **Results**
   - The model forecasts **continuous price growth** reaching ~$554K by 2074
   - The projection assumes a **linear trend**, which may not fully capture real-world fluctuations

## **Limitations**
- The model does not account for **economic recessions, housing bubbles, inflation, or policy changes**
- A **time-series model (ARIMA, Prophet, LSTM)** could improve prediction accuracy

## **Tools Used**
- **Python**: Pandas, NumPy, Matplotlib, Scikit-learn (Linear Regression)
- **Data Source**: Zillow
- **Jupyter Notebook** for analysis & visualization

## **Next Steps**
- Explore **time-series forecasting methods** for more realistic projections
- Integrate **external economic indicators** (interest rates, employment rates) for better accuracy
- Expand analysis to **other cities** for comparison

---

### **Project Files**
- `housing_prices_analysis.ipynb` → Jupyter Notebook with data analysis & modeling
- `housing_prices_plot.png` → Visualization of historical and predicted prices

---
**This project demonstrates predictive modeling for real estate trends. The findings can be useful for investors, home buyers, and market analysts.**


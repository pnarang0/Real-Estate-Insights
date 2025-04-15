
# 📊 Milestone 2 – Data Processing and Feature Engineering

## 📌 Objective
The goal of this milestone is to enhance the dataset by creating meaningful new features and transforming the data to prepare it for visualization and modeling in Milestone 3.

---

## 🔧 Data Processing Summary

In this step, we focused on three key areas:

1. **Feature Engineering**  
   We created three new features that provide deeper insights into property valuation:
   - `price_per_sqft`: Calculates the price per square foot to better compare property value across listings.
   - `amenities_score`: Combines key binary features (e.g., air conditioning and hot water heating) to quantify overall amenity value.
   - `bed_bath_ratio`: A ratio between bedrooms and bathrooms to understand space efficiency and luxury level.

2. **Categorical Encoding**  
   - Categorical columns such as furnishing status and air conditioning were encoded using **One-Hot Encoding** so that machine learning models and dashboards can interpret them properly.

3. **Feature Scaling**  
   - Numerical features were **standardized** using `StandardScaler` from `sklearn` to bring all values to a similar scale. This is especially helpful when we build visualizations or train models, as it reduces the bias caused by different value ranges.

---

## 🧠 Reflection

This milestone focused on **improving the structure and quality** of our dataset. The new features give us better tools to evaluate property value beyond raw pricing and make the dataset more useful for visual storytelling in Milestone 3.

Standardizing and encoding also ensures our future dashboard will perform more efficiently and accurately.

These transformations are made not just to enable technical improvements, but also to help **real estate agents and potential homebuyers** better interpret housing trends. For example, a real estate agent can now understand how pricing per square foot varies with amenities and layout quality.

---

## 🔜 What’s Next? (Milestone 3 Preview)

In the next milestone, we will build an **interactive Plotly Dash dashboard**. It will:
- Visualize key features like area, amenities, and price trends
- Allow dynamic filtering and exploration
- Support **real estate agents** in decision-making and client interaction

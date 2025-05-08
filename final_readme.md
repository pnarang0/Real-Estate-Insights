# Real Estate Dashboard

## Overview
This project is an interactive **Real Estate Dashboard** built with Dash and Plotly. The dashboard provides insights into housing data, helping users explore key trends and make data-driven decisions about the real estate market.

## Features

- **Data Analysis:**
  - Analyze property attributes such as price, area, bedrooms, bathrooms, furnishing status, and amenities.
  - Derived attributes like `price_per_sqft` and `amenities_score` for deeper insights.

- **Visualizations:**
  - **Price Trends (Line Plot):** Explore how price trends vary based on area.
  - **Area vs Price (Scatter Plot):** Examine the relationship between area and price, segmented by furnishing status.
  - **Amenities Score Distribution:** View the distribution of amenities scores across properties.
  - **Price per Sqft by Furnishing Status:** Understand price variations based on furnishing status.
  - **Correlation Heatmap:** Visualize relationships between attributes like price, area, and bedrooms.
  - **Bedrooms to Bathrooms Ratio:** Identify patterns in property configurations and pricing.

- **Interactive Filters:**
  - Filter data by preferred areas (e.g., high-demand or low-demand zones).
  - Enable multi-selection for more customized analyses.

## Dataset
The dataset includes the following columns:
- `price`: Property price.
- `area`: Area of the property in square feet.
- `bedrooms`: Number of bedrooms.
- `bathrooms`: Number of bathrooms.
- `furnishingstatus`: Furnishing status (Furnished, Semi-Furnished, Unfurnished).
- `prefarea`: Whether the property is in a preferred area.
- Amenities: Includes features like air conditioning, basement, main road, guestroom, etc.


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
  - In this dataset, the column prefarea indicates whether a property is located in a “preferred area.” These are high-demand zones, typically with better amenities, infrastructure, or location advantages, and are labeled as "Yes" or "No
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
## Each figure is in a separate tab — Why
-**Each figure is separated into tabs to allow users to focus on one trend at a time, making the dashboard cleaner and more user-friendly.**
- **Price Trends (Line Plot):** Shows how price increases with property area, helping identify general pricing bands across different property sizes.
- **Area vs Price (Scatter Plot):** Reveals distribution of prices across furnishing types and identifies luxury outliers or undervalued properties.
    
## Show price vs. area in both a line plot and scatter plot:
--We use both a line plot and a scatter plot to explore price vs. area because they reveal different aspects.The line plot shows overall price trends by area groupings, while the scatter plot reveals outliers and specific relationships across furnishing types.

## Brief Visualization Explanations
 -**1.Price Trends by Preferred Areas
This visualization compares property prices and area sizes across preferred and non-preferred areas. The x-axis represents property prices (scaled in millions, e.g., "2M" = 2 million), while the y-axis shows the area size in square feet. The graph is divided by a legend indicating whether the area is preferred (yes) or not (no). The purple line corresponds to preferred areas, while the orange line corresponds to non-preferred areas. The trends reveal that preferred areas tend to show more consistent pricing patterns, whereas non-preferred areas display greater fluctuations, especially around the 10M price range. This suggests that preferred locations maintain stable pricing despite differences in area size.

2. Correlation Heatmap of Housing Attributes
The correlation heatmap provides a comprehensive view of relationships between various housing attributes, such as price, area, and bedrooms. Attributes are listed on both axes, with a color gradient representing the strength of the correlation. Yellow indicates a strong positive correlation, meaning two attributes increase together, while darker colors represent weak or negative correlations. For example, price and area exhibit a strong positive correlation, signifying that larger properties generally cost more. On the other hand, attributes like price_per_sqft and area show weaker correlations, represented by darker shades, indicating less dependence between them.

3. Price Trends (Line Plot)
This line plot demonstrates the relationship between property prices and area sizes. The x-axis represents prices (in millions), while the y-axis indicates area sizes in square feet. The graph highlights how property size changes with increasing price. For instance, properties larger than 10,000 square feet predominantly appear after the 8M price range. The fluctuations in line width suggest variability in the density of data points, indicating that while most properties follow a general trend, exceptions occur at certain price levels, emphasizing outliers or unique data clusters.

4. Area vs Price Scatter Plot
The scatter plot showcases the relationship between area size and price while considering furnishing status. The x-axis represents area size in square feet, and the y-axis represents price (in millions). The legend categorizes properties into furnished, semi-furnished, and unfurnished. Most properties are clustered within the 2,000–6,000 square foot range, with prices generally below 8M. Furnishing status adds another dimension, where clusters suggest that semi-furnished and unfurnished properties dominate the mid-price range. Higher-priced properties (above 10M) tend to have larger area sizes but are more sparsely distributed, highlighting their exclusivity.

5. Amenities Score Distribution
This bar plot visualizes the distribution of property amenities scores, rated from 0 to 5. The x-axis indicates the amenities score, while the y-axis shows the number of properties for each score. The majority of properties fall within the 1 to 3 score range, reflecting average-quality features. Scores of 5, which indicate top-tier amenities, are rare, highlighting that only a small portion of properties offer premium features. This distribution helps identify the common quality levels of properties in the dataset and their relative scarcity.

6. Price per Sqft by Furnishing Status (Box Plot)
This box plot compares the price per square foot across furnishing statuses: furnished, semi-furnished, and unfurnished. The x-axis categorizes properties based on furnishing, while the y-axis represents the price per square foot. The median price per square foot is highest for furnished properties, followed by semi-furnished ones. Additionally, unfurnished properties display the most variability, as seen by the larger spread of their box, indicating a wide range of pricing. Outliers in each category reflect exceptional cases, emphasizing the diversity in property valuations.

7. Bathrooms vs Price
This graph examines the relationship between the number of bathrooms and property prices. The x-axis shows the number of bathrooms, while the y-axis represents price (in millions). Properties with a single bathroom are primarily priced below 4M, whereas those with three or more bathrooms are typically priced above 6M. The graph also highlights outliers, such as properties with exceptionally high prices for their bathroom count, which could indicate luxury features or unique market conditions. This trend underscores the influence of bathroom count on property valuation.


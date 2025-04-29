# Milestone 3 – Interactive Visualization with Plotly Dash

## Objective
The primary goal of this milestone is to create an interactive dashboard using Plotly Dash that visualizes key insights from the pre-processed dataset. This dashboard is designed to assist in understanding trends and relationships in the housing data effectively.

---

## Dashboard Features

1. **Dynamic Filtering:**
   - Users can filter data by preferred area using a dropdown menu.

2. **Interactive Tabs:**
   - The dashboard includes multiple tabs to display different visualizations:
     - **Price Trends**: A line chart showing price trends across areas.
     - **Area vs Price**: A scatter plot comparing area and price, with furnishing status as a color dimension.
     - **Amenities Score Distribution**: A histogram showcasing the distribution of amenities scores.
     - **Price per Sqft by Furnishing Status**: A box plot comparing the price per square foot across furnishing statuses.
     - **Bathrooms vs Price Boxplot**: A box plot depicting the relationship between bathrooms and price.
     - **Bedrooms to Bathrooms Ratio**: A scatter plot analyzing the relationship between the bedrooms-to-bathrooms ratio and price.

3. **Interactivity:**
   - Tooltips, hover effects, and responsive design ensure an engaging user experience.

---

## Technical Details

1. **Frameworks and Libraries:**
   - Dash and Plotly were used for creating the interactive visualizations.
   - pandas was employed for data manipulation and filtering.

2. **Dataset Usage:**
   - The processed dataset from Milestone 2 was utilized directly without additional preprocessing.
   - Key columns include `price`, `area`, `bedrooms`, `bathrooms`, `price_per_sqft`, and `amenities_score`.

3. **Visualization Implementation:**
   - Each tab in the dashboard is linked to a callback function that dynamically updates the plots based on user inputs (e.g., area filter).
   - Customizations such as axis labels, titles, and color schemes were applied for clarity and aesthetic appeal.

---

## Reflection

This milestone successfully delivered a functional, interactive dashboard that provides valuable insights into the housing dataset. The inclusion of interactive elements like filtering and tabs enhances usability and allows users to explore the data from multiple perspectives. The visualizations effectively highlight trends and patterns, aiding in decision-making.

---

## What’s Next? (Final Preview)

### Goals:
1. **User Feedback Integration:**
   - Gather feedback from users on the dashboard's usability and effectiveness.
   - Identify areas for improvement, such as additional visualizations or enhanced interactivity.

2. **Dashboard Enhancements:**
   - Add advanced visualizations like heatmaps or correlation matrices for deeper analysis.
   - Incorporate annotations to highlight critical data points.

3. **Documentation and Deployment:**
   - Update user documentation to include detailed instructions on navigating the dashboard.
   - Deploy the dashboard on a web-hosting platform for broader accessibility.

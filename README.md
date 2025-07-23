# Airbnb Listings EDA Project: New York 2024

## Project Overview
This project performs Exploratory Data Analysis (EDA) on New York Airbnb data to uncover trends and patterns in rental listings. It uses Python libraries such as Pandas, Numpy, Matplotlib, and Seaborn for data cleaning, visualization, and analysis.

## Objective
- Analyze room types, prices, and availability across different neighborhoods.
- Understand host behavior and listing patterns.
- Detect potential outliers in prices.
- Provide actionable recommendations for guests and hosts.

## Dataset
- Contains 20,765 listings with 22 features, including:
  - `id`: Unique listing identifier
  - `name`: Title of the listing
  - `host_name`: Name of the host
  - `neighborhood_group`: Borough where the listing is located
  - `latitude` & `longitude`: Geolocation coordinates
  - `price`: Nightly rental price
  - `room_type`: Type of accommodation (e.g., entire home, private room)
  - `reviews_per_month`: Average monthly reviews
  - `availability_365`: Days available in a year

## Steps and Workflow

1. **Data Cleaning**
   - Handle missing values (e.g., price, neighborhood, beds).
   - Convert `last_review` to datetime format.
   - Cap listings with prices > $1,000 to reduce skewness.

2. **Exploratory Data Analysis (EDA)**
   - Visualize room type distribution (bar plots).
   - Analyze price variations by boroughs (Manhattan highest).
   - Investigate availability trends using heatmaps.
   - Explore price distribution (histograms).
   - Analyze hosts with multiple listings (boxplots).
   - Study review behavior with pair plots.

3. **Data Visualization**
   - Pairplots to show correlations between price, availability, and reviews.
   - Heatmaps for numerical feature correlations.
   - Histograms and boxplots for price outlier detection.
   - Bar charts for room types and neighborhood distributions.

## Key Findings and Insights
- Manhattan has the highest average listing prices.
- Entire homes/apartments dominate the market and cost more.
- Private rooms provide budget-friendly options.
- Outliers exist with some listings priced over $10,000.
- Higher availability correlates with lower prices and more reviews.
- Hosts managing multiple listings indicate professional hosting trends.

## How to Run This Project
```bash
git clone https://github.com/najirh/Python-Project-P2-New-York-AirBnb-Listing-2024.git
pip install pandas numpy matplotlib seaborn
jupyter notebook day23_airbnb_eda.ipynb

License
This project is open-source and licensed under the MIT License.

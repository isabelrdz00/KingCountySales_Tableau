# King County House Sales Dashboard

### Project Overview
This Tableau project focuses on visualizing house sales data in King County, Washington, through an interactive dashboard. It includes a variety of visualizations such as a line chart, map, histograms, and a heat map, enabling users to explore and analyze real estate trends across different dimensions. The dashboard also incorporates a unique calendar widget as a primary filter, making it easy for users to view data by specific days and months.

## Key Features
- **Calendar Widget as a Primary Filter:**
  The calendar widget enables users to filter the data by selecting specific months or days, which dynamically updates the relevant charts in the dashboard.
  
- **Interactive Line Chart:**
  The line chart visualizes the daily average house sales price over time. The chart color can be customized, and the visual updates based on user interaction with the filters.
  
- **Geographic Analysis with Map Visualization**:
  The map displays average house prices by ZIP code, providing geographic context to the data. Colors are used to indicate price ranges, making it easy to identify high and low-priced areas.
  
- **Distribution Analysis with Histograms:**
  Three histograms show the distribution of house prices, number of bedrooms, and number of bathrooms, offering insights into the typical range and frequency of these attributes in the dataset.

- **Heat Map Analysis:**
  The heat map compares house views (e.g., no view, fair, good, excellent) against the condition of the house, helping users quickly see the distribution and relationship between these two dimensions.

- **Detailed Filter Options:**
  Filters for year built, square footage (living area), and lot size allow users to narrow down the dataset and focus on specific types of properties.
  
![Screenshot 2024-10-08 165116](https://github.com/user-attachments/assets/df874023-cf00-4e87-b7b8-ee7454b18e0e)


## Tools & Techniques
- **Tableau:** Used to build the dashboard, create calculated fields, and apply interactive filtering mechanisms.
- **Custom Parameters and Filters:** Utilized to add interactivity and connect the calendar widget with other visuals dynamically.
- **Data Preparation & Cleansing:** Data fields were formatted to ensure compatibility with Tableau’s visual features, and irrelevant fields were excluded from the dashboard.

## Visualizations
- **Line Chart:** Displays the average daily house sales price over time. Users can view trends and identify seasonal patterns or significant price changes.
- **Map Visualization:** Shows average house prices by ZIP code, colored to represent different price levels. The map can be zoomed in and out for a more detailed view.
-**Histograms:** Visualize the distribution of house prices, bedrooms, and bathrooms, providing an understanding of how these attributes are spread across the dataset.
- **View vs. Condition Heat Map:** A heat map that compares the view quality of houses with their condition ratings, using color intensities to show the average price associated with each combination.

# NYC-Airbnb-Data-Visualization

# Shiny App: https://zhanghai0.shinyapps.io/Airbnb/

## Project Overview
Traveling exploded during the last decade. New York City (NYC), as a major city in the United
States, is one of the most visited places in the world. Airbnb plays a significant role in New York
City's local economy by augmenting tourism and providing visitors with diverse lodging options.
Our visualization design traces the process of Airbnb information changes for both Airbnb
owners and NYC travelers. It aims to empower users with the ability to make informed decisions
by providing accessible and detailed analysis of data using different visualizations

## Key Features & Visualizations
- Map and Table Exploration: A geospatial distribution map and detailed data table that allow users to filter listings by neighborhood and neighborhood groups
- Correlation Heatmap: A Pearson cross-correlation matrix visualizing the relationships between variables like price, minimum nights, and number of reviews.
- Sentiment & Popularity Bubble Plot: A multidimensional analysis comparing sentiment scores against the number of reviews, with bubble size representing price.
- Room Type Analysis: A pie chart providing a visual breakdown of room types (Entire home/apt, Private room, Shared room) across different neighborhood groups.
- Price vs. Availability Scatter Plot: A tool to explore the relationship between pricing strategies and the number of days available for booking.

## Methodology 
- Interactive Filtering: Implemented dynamic sidebar statistics and filtering options (e.g., search bars, dropdowns, and sliders) to facilitate localized analysis.
- Advanced Visual Design: Used color-coding to simplify complex datasets (e.g., warm/cold colors in heatmaps and distinct colors for room types).
- Data Preprocessing: Standard NYC Airbnb data was cleaned and enhanced with calculated sentiment scores and split metadata tags for deeper analysis.

## Key Findings
- Spatial Trends: Popular areas like Chinatown, Chelsea, and the Upper East/West Sides show a high density of listings, indicating strong traveler interest and investment potential.
- Consumer Behavior: There is a strong correlation between total reviews and reviews per month, suggesting that popular listings receive constant engagement.
- Pricing Insights: High prices do not necessarily correlate with higher popularity; pricing strategies often depend on neighborhood-specific room type distributions.

# AirBnb-Data-Analysis-Using-python

 Airbnb NYC Data Analysis

This project focuses on analyzing Airbnb listings in New York City for the year 2019. By exploring key trends and patterns in the dataset, this analysis sheds light on the behavior of Airbnb hosts, guests, and the overall Airbnb landscape in NYC. The project leverages various Python libraries for data analysis and visualization to provide insightful conclusions.

## Project Overview

The goal of this project is to perform an in-depth exploratory data analysis (EDA) of Airbnb listings in New York City. The dataset includes nearly 49,000 listings and covers a wide range of attributes, such as the listing's price, location, room type, availability, and the host's information. Through careful data wrangling, visualization, and analysis, this project aims to uncover meaningful patterns in the Airbnb market in NYC.

### Key Highlights of the Project:
1. *Data Preprocessing*: Cleaning and preparing the dataset to handle missing values and incorrect data types.
2. *Data Analysis*: Exploring relationships between variables such as room type, price, location, and availability.
3. *Visualizations*: Using informative plots to visualize trends and patterns in the data.
4. *Insights & Conclusions*: Identifying trends in pricing, popular neighborhoods, and host behavior.

## Project Goals

This project aims to answer the following questions:
- Which neighborhoods have the highest concentration of Airbnb listings?
- What are the most common room types and how do their prices vary?
- How does the price of listings vary across different neighborhoods?
- Are there any patterns in host activity and availability throughout the year?

By answering these questions, we can provide a deeper understanding of the Airbnb market in NYC.

## Dataset Information

The dataset used in this analysis is publicly available and consists of data on Airbnb listings in New York City for the year 2019.

- *Number of rows (observations)*: ~49,000
- *Number of columns (features)*: 16
- *Attributes in the dataset include*:
  - host_id: Unique identifier for each host.
  - host_name: Name of the host.
  - neighbourhood_group: The borough in NYC where the listing is located (e.g., Manhattan, Brooklyn).
  - neighbourhood: The specific neighborhood within the borough.
  - room_type: The type of room being listed (Entire home/apt, Private room, Shared room).
  - price: The price per night for the listing.
  - minimum_nights: Minimum number of nights required to book the listing.
  - number_of_reviews: Total number of reviews for the listing.
  - last_review: The date of the most recent review.
  - reviews_per_month: The average number of reviews per month.
  - availability_365: The number of days the listing is available per year.

## Exploratory Data Analysis (EDA)

### Data Cleaning
Before performing analysis, the dataset underwent cleaning to ensure the accuracy and consistency of the data. This included:
- *Handling Missing Values*: Removing or imputing missing data, particularly for key fields such as reviews_per_month and last_review.
- *Data Type Conversion*: Converting data types for certain columns like last_review to ensure proper analysis.
- *Outlier Detection*: Identifying and handling outliers, especially in pricing, to avoid skewed results.

### Data Visualization
A variety of visualizations were created to explore the data:
- *Distribution of Prices*: A histogram of listing prices to understand the pricing landscape and identify any skewed or extreme values.
- *Room Type Popularity*: A breakdown of different room types (Entire home/apt, Private room, Shared room) and their respective frequency and price distribution.
- *Geographical Distribution*: A map of NYC, showing the spatial distribution of Airbnb listings across different neighborhoods and boroughs.
- *Availability and Reviews*: An analysis of how the availability of listings correlates with the number of reviews and pricing.

### Key Findings
From the exploratory data analysis, we discovered several key insights about the Airbnb market in NYC:
1. *Popular Neighborhoods*: Manhattan has the highest concentration of Airbnb listings, followed by Brooklyn. These boroughs dominate the short-term rental market in terms of both availability and pricing.
2. *Room Type Distribution*: Entire homes/apartments are the most common room type, followed by private rooms. Shared rooms are relatively rare.
3. *Price Variations*: Prices vary significantly based on room type and neighborhood. Manhattan listings tend to be more expensive than those in Brooklyn and Queens. Entire homes/apartments are priced significantly higher than private or shared rooms.
4. *Host Behavior*: Most hosts manage a single listing, but there are some hosts with multiple listings, indicating professional or commercial involvement in Airbnb.
5. *Reviews and Availability*: Listings with more reviews tend to be priced lower and have higher availability, indicating they cater to more budget-conscious travelers.

## Technologies Used

This project was developed using Python and several key libraries:
- *Pandas*: For data manipulation, cleaning, and analysis.
- *NumPy*: For numerical calculations and array operations.
- *Matplotlib & Seaborn*: For creating informative and visually appealing plots and graphs.
- *Jupyter Notebook*: To write, run, and document the analysis process interactively.
- *CSV Dataset*: The dataset is provided in CSV format, which is read into a Pandas DataFrame for analysis.

## Visualizations

The following visualizations were generated as part of the project:
1. *Price Distribution Histogram*: Shows the overall distribution of Airbnb listing prices, highlighting any outliers.
2. *Room Type Comparison*: A bar plot comparing the number of listings for each room type, with their average price.
3. *Geographical Heatmap*: A heatmap showing the density of Airbnb listings across different neighborhoods in NYC.
4. *Scatter Plot of Price vs. Number of Reviews*: A scatter plot showing the relationship between the price of a listing and its number of reviews.
5. *Availability by Borough*: A comparison of availability across different boroughs, highlighting areas with more active listings.

## Conclusion

This analysis provides valuable insights into the Airbnb market in New York City. It reveals trends in pricing, neighborhood preferences, and the types of accommodations most commonly offered. These insights can help potential hosts and guests better understand the dynamics of the short-term rental market.

*   Manhattan and Brooklyn have the highest demand for Airbnb rentals, as evidenced by the large number of listings in these neighborhoods. This could make them attractive areas for hosts to invest in property.

*   Manhattan is world-famous for its parks, museums, buildings, town, liberty, gardens, markets, island and also its substantial number of tourists throughout the year ,it makes sense that demand and price both high.

*   Brooklyn comes in second with significant number of listings and cheaper prices as compared to the Manhattan: With most listings located in Williamsburg and Bedford Stuyvesant two neighborhoods strategically close to Manhattan tourists get the chance to enjoy both boroughs equally while spending less.

*   Williamsburg, Bedford-Stuyvesant, Harlem, Bushwick, and the Upper West Side are the top neighborhoods in terms of listing counts, indicating strong demand for Airbnb rentals in these areas.

*   The average price of a listing in New York City is higher in the center of the city (Manhattan) compared to the outer boroughs. This could indicate that investing in property in Manhattan may be more lucrative for Airbnb rentals.
But Manhattan and Brooklyn have the largest number of hosts, indicating a high level of competition in these boroughs.

*   The data suggests that Airbnb rentals are primarily used for short-term stays, with relatively few listings requiring a minimum stay of 30 nights or more. Hosts may want to consider investing in property that can accommodate shorter stays in order to maximize their occupancy rate.

*   The majority of listings on Airbnb are for entire homes or apartments and also Private Rooms with relatively fewer listings for shared rooms. This suggests that travelers using Airbnb have a wide range of accommodation options to choose from, and hosts may want to consider investing in property that can accommodate multiple guests.

*   The data indicates that the availability of Airbnb rentals varies significantly across neighborhoods, with some neighborhoods having a high concentration of listings and others having relatively few.

*   The data indicates that there is a high level of competition among Airbnb hosts, with a small number of hosts dominating a large portion of the market. Hosts may want to consider investing in property in areas with relatively fewer listings in order to differentiate themselves from the competition.

*   The neighborhoods near the airport in Queens would have a higher average number of reviews, as they are likely to attract a lot of tourists or visitors who are passing through the area. The proximity to the airport could make these neighborhoods a convenient and appealing place to stay for travelers for short-term stay with spending less money because The price distribution is high in Manhattan and Brooklyn.

*Future Work*:
- Apply machine learning models to predict the price of Airbnb listings based on key factors such as location, room type, and availability.
- Analyze seasonal trends in Airbnb listings by adding more historical data.
- Explore the impact of reviews and ratings on a listing's success.

## Contributing

If you find any bugs or would like to add more features or improvements, feel free to fork the repository and submit a pull request. Contributions are always welcome!

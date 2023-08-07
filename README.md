# Google Play Store Data Analysis

This project performs an in-depth exploratory data analysis of over 10,000 apps listed on the Google Play Store. Utilizing a dataset that encapsulates various aspects of these apps, including their category, rating, size, number of installs, price, and content rating, this project aims to extract meaningful insights and trends from the Android app market.

## Data Cleaning

Ensuring the reliability and quality of our data is a key preliminary step. The data cleaning process involves:

- Filling in missing values with appropriate substitutes (median for 'Rating' and mode for other variables)
- Cleaning and transforming numerical columns ('Size', 'Installs', and 'Price') by removing non-numeric characters and converting these columns to a numeric format
- Normalizing the 'Size' column to a consistent unit (Megabytes)

## Analysis

The project encompasses the following analyses:

1. **Rating Distribution**: Analyzing the distribution of app ratings to gauge the general reception of apps by users.
2. **Price Analysis**: Investigating the distribution of app prices and the impact of price on an app's number of installs and ratings.
3. **Category Analysis**: Identifying the most common app categories, those with the highest average ratings, and those with the most downloads.
4. **Size Analysis**: Examining the relationship between an app's size and its rating and popularity (number of installs).
5. **Content Rating Analysis**: Exploring app content ratings to identify the most common ratings and their association with app categories and genres.

This project can serve as a valuable reference for app developers, marketers, and anyone interested in understanding the dynamics of the Android app market.

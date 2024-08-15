# Zomato Restaurant Data Analysis

This project analyzes a dataset of Zomato restaurants in Bengaluru to explore various insights such as restaurant ratings, types, and customer preferences. The dataset includes detailed information about each restaurant, including its name, location, type, and ratings, among other attributes.

## Dataset Description

The dataset used in this project can be downloaded from [Kaggle](https://www.kaggle.com/datasets/rajeshrampure/zomato-dataset).

The dataset contains the following columns:

1. **url**: URL of the restaurant on the Zomato website.
2. **address**: Address of the restaurant in Bengaluru.
3. **name**: Name of the restaurant.
4. **online_order**: Availability of online ordering.
5. **book_table**: Availability of table booking.
6. **rate**: Overall rating of the restaurant out of 5.
7. **votes**: Total number of ratings.
8. **phone**: Contact number of the restaurant.
9. **location**: Neighborhood in which the restaurant is located.
10. **rest_type**: Type of restaurant.
11. **dish_liked**: Dishes liked by customers at the restaurant.
12. **cuisines**: Types of cuisine offered, separated by commas.
13. **approx_cost(for two people)**: Approximate cost for a meal for two people.
14. **reviews_list**: List of tuples containing reviews for the restaurant.
15. **menu_item**: List of menu items available at the restaurant.
16. **listed_in(type)**: Type of meal (e.g., Buffet, Dinner).
17. **listed_in(city)**: Neighborhood in which the restaurant is listed.

## Project Structure

The project is organized as follows:

- **Data Loading and Preprocessing**: Importing necessary libraries and loading the dataset into a pandas DataFrame. Initial exploration of the dataset including shape, data types, and missing values.
- **Exploratory Data Analysis (EDA)**: Visualizing and analyzing various aspects of the data such as distribution of ratings, popular cuisines, and the relationship between different attributes.
- **Insights and Conclusions**: Summarizing the findings and insights gained from the data analysis.

## Installation

To run this project, you need the following libraries:

- pandas
- numpy
- matplotlib
- seaborn

You can install the required packages using:

```bash
pip install pandas numpy matplotlib seaborn

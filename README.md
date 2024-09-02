# Google_playstore_EDA

## Overview
This project involves exploratory data analysis (EDA) on a dataset containing information about various apps on the Google Play Store. The dataset includes details such as app names, categories, ratings, number of reviews, size, number of installs, price, content rating, genres, last updated date, current version, and the minimum Android version required. The goal of this analysis is to gain insights into the distribution of apps across different categories, ratings, and other attributes.

## Dataset
The dataset used in this analysis is named googleplaystoredata.csv. It contains the following columns:

App: The name of the app.

Category: The category to which the app belongs.

Rating: The rating of the app on the Play Store.

Reviews: The number of reviews the app has received.

Size: The size of the app.

Installs: The number of installs for the app.

Type: Whether the app is free or paid.

Price: The price of the app (0 if it is free).

Content Rating: The appropriate target audience for the app.

Genres: The genre of the app.

Last Updated: The date the app was last updated.

Current Ver: The current version of the app.

Android Ver: The minimum Android version required to run the app.

## Project Structure

googleplaystoredata.csv: The dataset containing app information.

main.ipynb: The Jupyter Notebook containing the code for data cleaning, analysis, and visualization.

README.md: This file, which provides an overview of the project.

## Installation
To run this project, you need to have Python installed along with the following libraries:
pip install numpy pandas matplotlib seaborn

## Usage

Loading the Data: The dataset is loaded into a Pandas DataFrame.

Data Cleaning: The data undergoes several cleaning steps:

Converting the Reviews, Size, Installs, and Price columns from object type to appropriate numeric types.

Handling missing values in the Rating and Type columns.

Exploratory Data Analysis: Various plots and summary statistics are generated to understand the distribution of apps across different categories, ratings, and other 
attributes.

## Key Analysis & Visualizations

Category Distribution: Visualizes the number of apps in each category.

Install Distribution: Shows the number of installs for each category.

Rating Distribution: Displays the distribution of app ratings.

Type Distribution: Analyzes the distribution of free vs. paid apps.

Correlation Matrix: Displays the correlation between numeric features in the dataset.

Top Apps: Lists the top apps based on installs, reviews, and price.

## Results
Through the analysis, several insights were gained:

The majority of apps in the Play Store fall under the Family, Game, and Tools categories.

Apps in the Game and Communication categories have the highest number of installs.

Most apps have ratings in the range of 4.0 to 4.7.

The majority of apps are free, with free apps generally being smaller in size and having higher ratings.

There is no direct relationship between app price and rating.

## Questions Addressed

What are the top 5 apps based on the number of installs?

What are the top 5 reviewed apps?

What are the top 5 most expensive apps?

What are the top 3 most installed apps in the Game category?

Which 5 apps from the Family category have the lowest ratings?

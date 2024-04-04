# Movie Correlation Analysis

Welcome to the Movie Correlation Analysis Project! This project aims to analyze correlations between various aspects of movies, such as box office revenue, budget, ratings, genres, and more. By conducting this analysis, we seek to gain insights into the factors that influence the success and reception of movies.

## Overview

The project involves collecting data from a CSV file using Python libraries such as Pandas, NumPy, Seaborn, and Matplotlib. We then preprocess the data, perform exploratory data analysis (EDA), calculate correlation coefficients, and interpret the findings to identify meaningful insights about the relationships between movie variables.

## Features

- **Data Collection**: Imported libraries such as Pandas, NumPy, Seaborn, and Matplotlib to manipulate and visualize the data. Utilized a CSV file containing movie data as the primary data source.

[file](https://github.com/SiriSrinivas6/Movie-Correlation-Analysis/blob/304b8a88b5771fbabe52f2d2da01f37565adad6f/movies.csv)

- **Data Preprocessing**: Checked for missing data and handled it appropriately. Changed the data types of columns as needed for analysis. Created a correct year column from existing date columns.

- **Exploratory Data Analysis (EDA)**: Explored the dataset to understand distributions, identify outliers, and detect patterns. Dropped duplicate entries to ensure data integrity.

- **Correlation Analysis**: Calculated correlation coefficients between pairs of variables to measure the strength and direction of relationships. Observed a high correlation between budget and box office gross, indicating that higher budgets tend to lead to higher gross revenues.

- **Visualization**: Plotted budget vs gross using Seaborn to visualize the relationship between these variables. Explored other visualizations to gain further insights into the data.

![1](https://github.com/SiriSrinivas6/Movie-Correlation-Analysis/blob/46584e21da7245423209d6feba418d6c7208bc39/1.png)

![2](https://github.com/SiriSrinivas6/Movie-Correlation-Analysis/blob/6a1c29d3c50e644d47a397730e56958689296704/2.png)

- **Company Analysis**: Investigated the involvement of production companies in the movie industry to understand their impact on movie performance and success.

## Usage

To replicate the analysis:

1. Ensure you have Python installed on your system.
2. Install the necessary libraries: Pandas, NumPy, Seaborn, and Matplotlib.
3. Download the provided CSV file containing movie data.
4. Run the provided Python script to load, preprocess, analyze, and visualize the data.

## Contributing

Contributions are welcome! If you have suggestions, enhancements, or bug fixes, please open an issue or create a pull request.

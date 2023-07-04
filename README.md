Coaster Database Analysis

This project focuses on analyzing a coaster database using Python and popular data manipulation and visualization libraries such as Pandas, NumPy, Matplotlib, and Seaborn. The project aims to gain insights into various aspects of coasters, including their characteristics, introduction trends, speed, height, inversions, and G-force.

The project starts by reading the coaster database CSV file into a Pandas DataFrame and performing initial exploratory data analysis. The DataFrame is cleaned and specific columns of interest are selected for further analysis. The data is transformed and prepared for visualization and statistical calculations.

Key steps performed in the project include:

Exploratory Data Analysis:
Retrieving the dimensions and column names of the DataFrame
Displaying the first few rows and descriptive statistics of the coaster data

Data Cleaning and Transformation:
Selecting specific columns for analysis
Converting data types, such as converting the 'opening_date_clean' column to datetime
Renaming columns for better readability and consistency
Handling missing values and removing duplicate rows based on selected criteria

Data Visualization:
Creating bar plots to visualize the top 10 years when coasters were introduced
Generating histograms and kernel density estimation (KDE) plots to analyze coaster speeds
Creating scatter plots to explore the relationship between coaster speed and height
Utilizing seaborn to create pair plots for a comprehensive analysis of selected variables

Additional Analysis:
Calculating the correlation matrix between selected coaster attributes
Creating a heatmap to visualize the correlation matrix
Generating a horizontal bar plot to compare the average coaster speed by location

Through these data analysis and visualization techniques, this project provides valuable insights into coaster characteristics, trends, and relationships between different attributes. The code demonstrates how to effectively utilize Python libraries to explore and gain meaningful insights from coaster data.
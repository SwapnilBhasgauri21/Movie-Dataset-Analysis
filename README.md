# Movie-Dataset-Analysis
This repository contains Python code for analyzing a movie dataset using popular data analysis and visualization libraries. The dataset includes information about movies, such as their titles, ratings, genres, release years, scores, votes, directors, budgets, gross earnings, production companies, and more.

# Code Structure  
The code is organized into sections, each focusing on a specific aspect of the dataset analysis. Here's a breakdown of the main sections:

1. Data Loading and Initial Exploration
•	Importing Packages: Libraries like Pandas, NumPy, Seaborn, and Matplotlib are imported to facilitate data manipulation and visualization.
•	Reading Data: The movie dataset is read from a CSV file into a Pandas DataFrame.
•	Checking Missing Data: The code inspects each column for missing data and reports the percentage of missing values.

2. Data Cleaning and Transformation
•	Data Types: The data types of each column are displayed.
•	Creating a Correct Year Column: A new column, "yearcorrect," is created by extracting the release year from the "released" column.
•	Sorting Data: The DataFrame is sorted by gross revenue to explore high-grossing movies.
•	Handling Duplicates: Duplicate rows are removed from the DataFrame.

3. Data Visualization
•	Scatter Plot: A scatter plot is generated to visualize the relationship between the budget and gross earnings of movies.  

•	Correlation Matrix Heatmap: A heatmap displays the correlation matrix of numeric features in the DataFrame.
 


•	Factorize and Correlation for Categorical Data: Categorical data is factorized, and a correlation matrix is calculated for these values.
•	Exploring Strong Correlations: Pairs with strong correlations (greater than 0.5) are identified.
 


4. Top Companies by Gross Revenue
•	Top Companies by Gross Revenue: The top 15 movie production companies are listed based on their total gross revenue.
•	Grouping by Company and Year: The gross revenue of companies is explored, grouped by both company and year.
•	Grouping by Company and Year (Top Years): The top years for movie companies based on gross revenue are displayed.
•	Grouping by Company (Overall): The overall gross revenue of movie companies is explored, and the top 15 companies are listed.

Getting Started
To run this analysis on your machine, follow these steps:
1.	Clone this repository: git clone https://github.com/your-username/movie-dataset-analysis.git
2.	Install the required Python libraries: pip install -r requirements.txt
3.	Run the Jupyter Notebook or Python script to execute the analysis.
Feel free to explore, modify, and enhance the code for your specific needs

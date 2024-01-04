Top 1000 Movies Dataset README
Overview:
This project utilizes the Python programming language and the Pandas library to analyze and clean a dataset containing information about the top 1000 movies. The dataset is loaded from a CSV file named 'imdb_top_1000.csv'.

Data Information:
The dataset comprises 16 columns, including information such as Movie Title, Released Year, Certificate, Runtime, Genre, IMDB Rating, Overview, Meta Score, Director, Leading Role, Supporting Roles, No_of_Votes, and Gross. Some columns have missing values, such as Certificate, Meta Score, and Gross.

Initial Data Exploration:
The initial exploration of the dataset includes checking basic information using df.info() and examining the first two rows with df.head(2).

Data Cleaning:
Columns are renamed for clarity using df.rename().
The 'Poster_Link' column is dropped as it is not needed for analysis.
The 'Gross' column is cleaned by removing commas and converting it to a numerical format.
Missing values in 'Gross' are replaced with 0.
The 'Runtime' column is extracted to include only numeric values.
A new column, 'No of Movies Directed,' is added to indicate the number of movies directed by each director.

Statistical Analysis:
Descriptive statistics are generated using df.describe() to provide insights into the central tendency and spread of numerical columns.
Saving Cleaned Data
The cleaned dataset is saved to a new CSV file named 'Top 1000 Movies.csv' using df.to_csv().

Dependencies:
pandas
numpy

Usage:
Ensure Python is installed on your system.
Install the required libraries using pip install pandas numpy.
Run the provided script to perform data cleaning and analysis.
Feel free to explore and analyze the dataset further based on your specific interests and research questions.






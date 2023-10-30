# Sentiment_Analysis
1.	Importing Libraries:
a.	Imports necessary libraries and modules for data analysis, sentiment analysis, and data visualization, such as Pandas, NLTK, TextBlob, VADER Sentiment Analysis, and Plotly.
2.	Data Loading and Exploration:
b.	Loads a dataset from the 'sad.csv' file into a Pandas DataFrame called 'df'.
c.	Sorts the DataFrame based on the 'wilson_lower_bound' column in descending order.
d.	Removes the 'Unnamed: 0' column from the DataFrame.
3.	Data Analysis Functions:
e.	Defines several custom functions for data analysis, including missing_values_analysis, check_dataframe, check_class, and categorical_variable_summary. These functions are used to examine missing values, data types, duplicated values, and generate summary statistics for categorical variables.
4.	Data Exploration:
f.	Calls the check_dataframe and check_class functions to display various statistics and information about the DataFrame 'df'.
5.	Sentiment Analysis:
g.	Applies sentiment analysis to the 'reviewText' column using both TextBlob and VADER Sentiment Analysis.
h.	The sentiment is categorized as 'Positive,' 'Negative,' or 'Neutral' based on sentiment scores.
6.	Categorical Variable Summary:
i.	Calls the categorical_variable_summary function to generate visualizations for the 'sentiment' column, including count plots and pie charts.
7.	Additional Sentiment Analysis Results:
j.	Filters the DataFrame for rows with 'Positive' sentiment and sorts them by the 'wilson_lower_bound' column in descending order.
k.	Displays the top 5 results.
8.	Categorical Variable Summary (Part 2):
l.	Calls the categorical_variable_summary function again, this time for the 'sentiment' column after sentiment analysis has been applied.



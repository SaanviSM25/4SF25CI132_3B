# 4SF25CI132_3B
Billboard Hot 100 – Data Analysis
Project Overview: In this project we are analysing Billboard Hot 100 music data with Spotify audio features with the help of Python. The primary task is to convert, to clean and deal with missing data,  derive insights and visualize various trends in music data.

2.Dataset Description:
  The dataset used in this project is: billboard_hot_100_spotify_audio_features_enriched.csv
  Number of rows: 32,503
  Number of columns: 33
  Data type: Structured CSV dataset
  
3.Objectives:The primary objectives of this project are:
  With a collection of data that you want to understand and wrangle.
  To detect and deal with missing values.
  or filtering the data by column and adding extra columns/features.
  To aggregate and analyze data to produce valuable insights.
  Graph the results with various types of graphs.
  
4.Data Transformation and Preprocessing: The following preprocessing operations were performed:
  Renamed selected columns for better readability.
  Converted chart date columns into datetime format.
  Extracted the chart year from the chart starting date.
  Created a popularity category based on song popularity.
  Handled missing numerical values using mean imputation.
  Removed unnecessary columns that were not required for the analysis

5.Insight Generation: The dataset was analysed to identify patterns and useful information, including:
  Top artists based on their total weeks on the Billboard chart.
  Average energy, danceability, and tempo of songs.
  Top songs based on Spotify popularity.
  Number of songs belonging to different musical eras.
  Grouping, sorting, and statistical operations were used to generate these insights.
  
6.Data Visualization: The following visualization methods were implemented:
  Basic Line Plot – Number of Billboard songs by year.
  Customized Line Plot – Yearly song count with customized appearance.
  Multiple Line Plots using Subplots – Comparison of yearly song count, energy, danceability, and popularity.
  Bar Graph – Top 10 music genres.
  Histogram – Distribution of song danceability.
  Scatter Plot – Relationship between energy and danceability.
  Pie Chart – Distribution of the top 5 music genres.
  Pandas Bar Graph – Top 10 artists based on total chart weeks

7.Tools and Technologies Used
Programming Language: Python
Environment: Jupyter Notebook
Libraries:
Pandas – Data manipulation and analysis
Matplotlib – Data visualization

8.Conclusion:This project demonstrates how Python can be used for data transformation, missing-value handling, insight generation, and visualization.
By analysing Billboard chart information alongside Spotify audio features, the project helps explore patterns in song characteristics, popularity, genres, and chart performance.

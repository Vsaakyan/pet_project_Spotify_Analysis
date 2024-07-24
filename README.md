# pet_project_Spotify_Analysis

# Introduction
In this project I used a dataset from Kaggle - https://www.kaggle.com/datasets/nelgiriyewithana/most-streamed-spotify-songs-2024/code.
This dataset contains various track information from Spotify and additional information from other platforms as Youtube, Shazam, AppleMusic and etc.

# Project content
The project consists of 2 main parts:

## 1. Data Analysis
Data Analysis consists of three components, namely:
### 1.1 Exploratory Data Analysis.
- Loading the dataset to pandas table.
- Taking a look at DataFrame.
- Shape of the DataFrame.
- Taking a look on the main characteristics (describe()).
- Taking a look at dtypes and missing values in columns.
### 1.2 Data Preproccessing.
- Renaming the column names to lower case and add underscores instead of spaces, if any.
- Dropping the unuseful columns from the dataset.
- Converting column's dtypes.
- Making new columns for more convinience.
### 1.3 Data Cleaning.
- Defining missing columns.
- Filling numeric columns with median value.
- Filling object columns with 'Unknown'.
using core libraries for data analysis (pandas, numpy).

## 2. Data Visualization
As for Data Visualization, in this project I tried to clearly indicate on the graphs certain trends that correspond to the track posted on Spotify using core libraries for Data Visualization (matplotlib, seaborn).

Through Data analysis and Visualization was identified:
1) Top 10 tracks with the highest Track Score
2) Top 10 tracks with most plays on YouTube,
3) Top 10 tracks with most plays on Spotify.
4) Top 10 tracks with the highest Shazam Count.
5) The number of all tracks throughout years.
6) The number of all tracks over decades
7) The average Track Score per each year
8) The best track score per each year.
9) The worst track score throughout years.


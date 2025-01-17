# Data-Analysis

This is a repository of my work as I explore data and practice coding.
I currently use numpy, matplotlib, seaborn, scikit-learn, tensorflow, and jupyter notebook, but am always looking for new tools!

1. Rolling Stone's Top 500 (EDA)

  This project is an exploration of Rolling Stones top 500 albums of all time. I looked at the breakdown by genre and over time. There's a    lot of Rock, and a lot of it comes from 1970-1980! 

2. Billboard Top 100 with Spotify Audio Features (EDA + Classification)

  Continuing with the music trend, I analyzed Billboard's Top 100 charts from 1958 to 2018. There are 2 data sets that need to be cleaned and joined. One is the info on each weekly chart. What songs are on the chart with their current position and a variety of other details. The second data set is the extracted audio features for each song on those charts using Spotify's API.
  
   It was neat to see some of the trends, in particular song length. I built several models to classify the age of a song based on it's audio features. I used the following models: multiple linear regression, decision tree, random forest regressor, and sequential neural network. Then I integrated Spotify's API, cleverly named Spotipy, into the notebook and used it to look up features for songs outside of Billboard's top.

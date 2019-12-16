# DMML2019_Team_Tesla
The repo for the project of DM ML course  
Master: Information Systems - HEC Lausanne - 2019

Structure of the project

code
- 1. Download Spotify Data (don’t run this notebook)
- 2. Download Lyrics (don’t run this notebook)
- 3. Cleaning Lyrics (don’t run this notebook)
- 4. Exploratory Data Analysis - Spotify Audio Features
- 5. Exploratory Data Analysis - Lyrics
- 6. Classification
- 7. Clustering
- 8. Glove model 

data
- top_hits.json
- songs.json
- top_hits_merged_clean_lyrics_audio_features.json
- not_hits_merged_clean_lyrics_audio_features.json

#### In order to run the notebooks, please download the GloVe model from this link: https://drive.google.com/open?id=126qGJC9o1da-_deqGwfN6iyuU2S0AtMa and place them in data folder.

## Data mining:

Our data come from Spotify using their API.

- We got the Top Hits from Spotify using their API from 1970 to 2018.   
  link: https://open.spotify.com/playlist/3cS7RrbJgQPEiWPAyOnb4l?si=qbUDHQRGTHSgN99Yp6mBlA
- We also collected other songs produced in every decade from 1970 to 2018.

Spotify allows us to collect only information about a song.

More information about the data we collected:  
https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/

To get the lyrics of a song, we scraped the follwoing websites:
- genius.com
- lyricsmode.com
- songlyrics.com
- metrolyrics.com

## Machine learning:

We would like to predict whether a song will be a hit or not, based on lyrics and audio features.

## The team:

mkrsteska : Marija Krsteska  
thil5 : Samuel Lew  
Martynas2 : Martynas Savickas  
yassinhediger: Yassin Hediger

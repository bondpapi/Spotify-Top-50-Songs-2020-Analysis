# Spotify Top 50 Tracks of 2020 - Data Analysis

## Overview

**This notebook provides an exploratory data analysis (EDA) of the Spotify Top 50 Tracks of 2020 dataset. It answers key questions about popular artists, albums, and track attributes such as danceability, loudness, and acousticness. Additionally, it compares these attributes across four major genres: Pop, Hip-Hop/Rap, Dance/Electronic, and Alternative/Indie.**

## Dataset
Source: [Spotify Top 50 Tracks of 2020 (Kaggle)](https://www.kaggle.com/datasets/atillacolak/top-50-spotify-tracks-2020)
Features: Track name, artist, genre, album, and various musical attributes.

## Analysis Steps

### Data Cleaning:
    - Handle missing values and duplicates.
    - No data deletion as per analysis goals.

### Exploratory Data Analysis:
    - Analyze number of artists, albums, and tracks.
    - Identify tracks with unique danceability and loudness scores.
    - Correlation analysis between features.

### Genre Comparison:
    - Compare average danceability, loudness, and acousticness across selected genres.

### Results
#### Danceability:
    Hip-Hop/Rap and Dance/Electronic are the most danceable.

#### Loudness:
    Dance/Electronic tracks are the loudest.

#### Acousticness:
    Alternative/Indie is the most acoustic.

### Future Improvements
Incorporate additional attributes like tempo or energy.
Apply machine learning models to predict popular track attributes.

### Requirements
Python 3.x
Pandas
Matplotlib


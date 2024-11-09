# Spotify Top Tracks 2023: Exploratory Data Analysis

**Author**: Andrei Joshua A. Rodriguez  
**Class**: 2ECE-C

---

## Overview

This notebook presents an in-depth exploratory data analysis (EDA) of the top-streamed tracks on Spotify in 2023. By analyzing trends in song characteristics, artist popularity, platform visibility, and streaming counts, the study uncovers insights into factors contributing to song popularity in 2023's streaming landscape.

## Table of Contents

1. **Introduction**
2. **Libraries and Data Loading**
3. **Data Overview and Cleaning**
4. **Exploratory Analysis**
    - Descriptive Statistics
    - Temporal Trends in Track Releases
    - Feature Distributions (e.g., streams, danceability, energy)
5. **Patterns and Correlations**
    - Platform Popularity Comparison
    - Correlation Matrix of Key Features
6. **Visualizing Key Patterns**
7. **Conclusions**
8. **Guide Questions** (Answered Throughout)

---

## Getting Started

To replicate this analysis, you’ll need the following:

- **Python Libraries**: `numpy`, `pandas`, `matplotlib`, `seaborn`
- **Dataset**: Ensure the dataset (`spotify-2023.xlsx`) is available in the project directory.

---

## Guide Questions

This analysis addresses the following questions:

### 1. Overview of Dataset
   - **How many rows and columns does the dataset contain?**
   - **What are the data types of each column?** Are there any missing values?

### 2. Basic Descriptive Statistics
   - **What are the mean, median, and standard deviation of the `streams` column?**
   - **What is the distribution of `released_year` and `artist_count`?** Are there any noticeable trends or outliers?

### 3. Top Performers
   - **Which track has the highest number of streams?** Display the top 5 most streamed tracks.
   - **Who are the top 5 most frequent artists based on the number of tracks in the dataset?**

### 4. Temporal Trends
   - **Analyze the trends in the number of tracks released over time.** Plot the number of tracks released per year.
   - **Does the number of tracks released per month follow any noticeable patterns?** Which month sees the most releases?

### 5. Genre and Music Characteristics
   - **Examine the correlation between streams and musical attributes like `bpm`, `danceability_%`, and `energy_%`.** Which attributes seem to influence streams the most?
   - **Is there a correlation between `danceability_%` and `energy_%`?** How about `valence_%` and `acousticness_%`?

### 6. Platform Popularity
   - **How do the numbers of tracks in `spotify_playlists`, `spotify_charts`, and `apple_playlists` compare?**
   - **Which platform seems to favor the most popular tracks?**

### 7. Advanced Analysis
   - **Based on the streams data, can you identify any patterns among tracks with the same key or mode (Major vs. Minor)?**
   - **Do certain genres or artists consistently appear in more playlists or charts?** Perform an analysis to compare the most frequently appearing artists in playlists or charts.

---

## Key Analyses

- **Temporal Trends**: Analysis of the number of tracks released over the years and monthly patterns.
- **Statistical Summaries**: Summary statistics for streaming data and other features, including central tendencies and dispersion.
- **Feature Distributions**: Examination of distributions for features like streams, bpm, and danceability.
- **Correlation Analysis**: Heatmap illustrating relationships between features, e.g., between energy and danceability.

---

## Visualizations

The notebook includes multiple visualization types:

- **Time Series Plot**: Track releases by year
- **Bar Charts**: Most popular artists by playlist appearances
- **Scatter Plots**: Relationship between danceability and energy, valence and acousticness
- **Heatmaps**: Correlations among features

---

## Conclusions

This analysis of Spotify's 2023 streaming data provides valuable insights into the factors that influence track popularity and reveal patterns across song characteristics and artist presence on streaming platforms.

---

Let me know if you’d like any adjustments or additions!

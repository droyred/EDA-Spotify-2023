# Spotify Top Tracks 2023: Exploratory Data Analysis

**Author:** Andrei Joshua A. Rodriguez | **Class:** 2ECE-C

## Overview

Welcome to a deep dive into the world of Spotify’s top tracks of 2023! As a dedicated Spotify music fan, this notebook was developed to capture the trends, characteristics, and patterns that made certain songs stand out in the streaming world this year. By examining data such as streaming counts, artist popularity, and song characteristics like danceability and energy, this analysis reveals the factors that drive songs to the top of the charts and keep listeners coming back. We explore everything from yearly release trends to the influence of tempo and mood, aiming to understand what makes a track truly popular in today’s music landscape. 

The analysis in this notebook brings together visuals, correlations, and in-depth feature analysis that collectively tell the story of 2023’s streaming favorites. Whether you're curious about which month sees the most releases or which musical elements most impact streaming numbers, this analysis uncovers insights for anyone fascinated by music trends.

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

## Getting Started

To replicate this analysis, you’ll need the following:

- **Python Libraries**: `numpy`, `pandas`, `matplotlib`, `seaborn`
- **Dataset**: Ensure the dataset (`spotify-2023.xlsx`) is available in the project directory.

## Guide Questions

This analysis addresses the following questions:

### 1. **Overview of Dataset**
   - **How many rows and columns does the dataset contain?**
   - **What are the data types of each column?** Are there any missing values?

### 2. **Basic Descriptive Statistics**
   - **What are the mean, median, and standard deviation of the `streams` column?**
   - **What is the distribution of `released_year` and `artist_count`?** Are there any noticeable trends or outliers?

### 3. **Top Performers**
   - **Which track has the highest number of streams?** Display the top 5 most streamed tracks.
   - **Who are the top 5 most frequent artists based on the number of tracks in the dataset?**

### 4. **Temporal Trends**
   - **Analyze the trends in the number of tracks released over time.** Plot the number of tracks released per year.
   - **Does the number of tracks released per month follow any noticeable patterns?** Which month sees the most releases?

### 5. **Genre and Music Characteristics**
   - **Examine the correlation between streams and musical attributes like `bpm`, `danceability_%`, and `energy_%`.** Which attributes seem to influence streams the most?
   - **Is there a correlation between `danceability_%` and `energy_%`?** How about `valence_%` and `acousticness_%`?

### 6. **Platform Popularity**
   - **How do the numbers of tracks in `spotify_playlists`, `spotify_charts`, and `apple_playlists` compare?**
   - **Which platform seems to favor the most popular tracks?**

### 7. **Advanced Analysis**
   - **Based on the streams data, can you identify any patterns among tracks with the same key or mode (Major vs. Minor)?**
   - **Do certain genres or artists consistently appear in more playlists or charts?** Perform an analysis to compare the most frequently appearing artists in playlists or charts.

## Key Analyses

- **Temporal Trends**: Analysis of the number of tracks released over the years and monthly patterns.
- **Statistical Summaries**: Summary statistics for streaming data and other features, including central tendencies and dispersion.
- **Feature Distributions**: Examination of distributions for features like streams, bpm, and danceability.
- **Correlation Analysis**: Heatmap illustrating relationships between features, e.g., between energy and danceability.

## Visualizations

The notebook includes multiple visualization types:

- **Time Series Plot**: Track releases by year
- **Bar Charts**: Most popular artists by playlist appearances
- **Scatter Plots**: Relationship between danceability and energy, valence and acousticness
- **Heatmaps**: Correlations among features

## Conclusions

The results from this analysis provide a fascinating glimpse into the world of Spotify’s top tracks in 2023. We see that streaming success is not just about an artist’s popularity but is also influenced by the music's inherent qualities—like energy and danceability—that resonate with listeners. Key insights include seasonal and yearly release trends that point to industry-wide release strategies. For example, certain months show a spike in releases, possibly aiming to capture holiday or summer listening peaks. The analysis also identifies that certain attributes, like danceability and energy, have a positive correlation with streaming numbers, which suggests that high-energy, danceable tracks may be more likely to reach larger audiences.

Moreover, by comparing playlist and chart appearances across platforms, we gain insights into which platforms boost certain artists and genres, highlighting the unique audience preferences for Spotify vs. Apple Music. This analysis not only answers the key questions posed but also serves as a resource for any music lover interested in how data shapes our understanding of the music industry.

Thanks for diving into Spotify’s top 2023 tracks with me—hope you find as much joy in the data as I did!


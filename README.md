# Spotify Top 50 Tracks 2020 Analysis

This repository contains an exploratory data analysis (EDA) of the **Top 50 Spotify Tracks of 2020** dataset. The dataset includes information about 50 songs, including audio features, artists, genres, and more. The goal is to uncover trends, identify correlations, and answer specific questions about the dataset.

## Dataset

The dataset, `spotifytoptracks.csv`, contains the following features:
- **Artist**: Name of the artist.
- **Album**: Name of the album the track belongs to.
- **Track Name**: Title of the track.
- **Track Id**: Spotify track ID (removed during preprocessing as redundant).
- **Energy**: Higher value indicates a more energetic song.
- **Danceability**: Higher value indicates ease of dancing to the song.
- **Key**: Primary musical key of the song.
- **Loudness**: Higher value indicates louder songs.
- **Acousticness**: Describes how acoustic a song is.
- **Speechiness**: Detects the presence of spoken words.
- **Instrumentalness**: Likelihood of a track being instrumental.
- **Liveness**: Probability that the track was recorded with a live audience.
- **Valence**: Positivity of the song (higher means more positive).
- **Tempo**: Beats per minute.
- **Duration in Milliseconds**: Length of the song in milliseconds.
- **Genre**: Genre of the song.

## Installation

To run the code, follow these steps:

1. **Download or clone `spotify_top_tracks_2020.ipynb` and `spotifytoptracks.csv` files** from the repository.
2. Download `Python` and install the following libraries using pip:

```bash
pip install pandas seaborn matplotlib
# Spotifysong_Analysis_Project
# 🎵 Top Spotify Songs (2010–2019) – Trends, Genres & Audio Features Analysis

## 📌 Overview
This project focuses on analyzing the top Spotify songs from 2010 to 2019 using Python. It involves detailed **data cleaning**, **preprocessing**, and **visualization** to explore trends in genres, audio features, and song popularity over the decade.

---

## 📁 Dataset
- **Source:** Kaggle – Top Spotify Songs 2010–2019
- **File**: `data/top_spotify_2010_2019.csv`
- **Rows**: 1000 tracks (Top 100 songs per year)
- **Format**: CSV, UTF-8

### 🧾 Features Included:
#### 🎵 Song Metadata:
- `title`: Song name
- `artist`: Artist name
- `top_genre`: Genre of the song
- `year`: Year of release

#### 🔊 Audio Features:
- `bpm`: Beats per minute
- `nrgy`: Energy (0–100)
- `dnce`: Danceability (0–100)
- `val`: Valence/musical positivity
- `dur`: Duration (in seconds)
- `db`: Loudness
- `live`: Liveness score
- `acous`: Acousticness
- `spch`: Speechiness
- `pop`: Popularity score

> 📌 Column names are abbreviated as per original Kaggle dataset. Cleaned and used for trend analysis.

---

## 🧹 Data Cleaning & Preprocessing
- Removed null values and duplicate rows
- Standardized column names
- Cleaned and split multi-genre entries
- Converted duration from milliseconds to minutes
- Normalized audio features where required

---

## 📊 Data Visualization
Used `Matplotlib`, `Seaborn`, and `Plotly` to create:
- Bar charts of **Top Artists**
- Pie charts of **Genre Distribution**
- Line plots of **Song Duration Trends**
- Heatmaps showing **Correlation between Audio Features**
- Distribution plots for **Danceability**, **Energy**, etc.

---

## 📌 Key Insights
- **Pop** and **Dance Pop** were the most dominant genres
- Songs became slightly shorter in duration over the years
- Audio features like **Energy** and **Danceability** stayed consistently high
- Artists like **Drake**, **Ed Sheeran**, and **Post Malone** frequently appeared in the top charts

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

---

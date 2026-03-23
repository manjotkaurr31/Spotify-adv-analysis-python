# 🎧Spotify Exploratory Data Analysis🎧

## Project Overview

This project performs an **exploratory data analysis (EDA)** of a Spotify tracks dataset to investigate how musical attributes relate to song popularity. The dataset contains track audio features and metadata extracted from Spotify's audio analysis system. These features describe various aspects of a track's musical characteristics including rhythm, energy, emotional valence and acoustic properties.

The goal of this analysis is to:
- Understand the **distribution of track(song) popularity**
- Examine **relationships between audio features**
- Explore how **musical characteristics vary across genres**
- Evaluate whether **audio features influence song popularity**

---

# Dataset Description

Each observation in the dataset represents a **single Spotify track** and includes both metadata and audio feature attributes. The dataset spans across 110k+ records segregated through 15+ labels. This scale provides abundant data to conduct insightful EDA.

Music streaming platforms generate large volumes of structured data that describe both listener engagement and the acoustic characteristics of songs. The Spotify tracks dataset was chosen because it combines **track popularity metrics with detailed audio feature descriptors**, allowing both musical and analytical perspectives to be explored. Unlike many datasets that contain only metadata, this dataset includes **quantitative musical attributes such as danceability, energy, valence, acousticness, and loudness**, which provide a structured way to analyze how different musical characteristics relate to listener engagement. This makes the dataset particularly well suited for exploratory data analysis, as it enables investigation into questions such as how audio features interact, how musical styles vary across genres, and whether intrinsic track characteristics show any relationship with popularity on streaming platforms.

### 🔎 Track Metadata Features

- **track_name** – Name of the track  
- **artists** – Artist or artists associated with the track  
- **album_name** – Album in which the track appears  
- **track_genre** – Genre classification of the track  
- **popularity** – Popularity score assigned by Spotify (0–100)

### 🔎 Audio Features

- **danceability** – Suitability of a track for dancing  
- **energy** – Perceived intensity and activity level  
- **valence** – Emotional positivity of a track  
- **loudness** – Overall loudness measured in decibels  
- **acousticness** – Confidence that a track is acoustic  
- **instrumentalness** – Likelihood that the track contains no vocals  
- **speechiness** – Presence of spoken words in a track  
- **tempo** – Estimated tempo (beats per minute)
- **duration_ms** - Depict timespan of the track
- **explicit** – Indicates whether the track contains explicit lyrics

### 🔎 Music Theory Features

- **Key** - Each value corresponds to a pitch class (e.g., C, C#, D, etc.).
- **Mode** - Indicates whether the track is in a major (1) or minor (0) scale. Major keys associate with happier sounds while minor keys convey sadder tones.
- **Time Signature** - Represents the number of beats per measure.

---

# Repository Structure
```text
  Spotify-adv-analysis-python
    │
    ├── charts/                   # Visualizations generated from analysis
    ├── data/                     # Dataset
    │     ├── dataset.csv
    ├── insights/                 # Detailed written analysis
    │     ├── insights.md
    ├── notebook/                 # Jupyter notebook containing the full EDA
    ├── README.md
```

---

# Technologies Used

- Python:
    - Pandas
    - NumPy
    - Matplotlib
- Jupyter Notebook

---

# Full Notebook

The complete analysis with code and visualizations is available in the `spotify_eda.ipynb` notebook inside the folder 📂 `notebook`.

# Insights
The complete analytical insight derived from Spotify `dataset.csv` is available in `insights.md` file inside the folder 📂 `insights`.
Happy reading!

# 🎧 Spotify 2023 Data Analysis Dashboard

## 📊 Project Overview
This project analyzes the **Spotify 2023 Songs Dataset** to uncover insights about music trends, artist impact, and cross-platform streaming performance.

Using **Power BI**, an interactive dashboard was built to explore how audio features, artist collaboration, and platform distribution influence song popularity.

The dashboard is structured into **three analytical pages**, each focusing on different aspects of music analytics.

---

# 🎯 Project Objectives

1. **Music Analysis**  
   Explore patterns in audio features to understand trends and preferences in popular songs.

2. **Platform Comparison**  
   Compare song popularity across different music platforms.

3. **Artist Impact**  
   Analyze how artist involvement and collaborations influence a song’s success.

4. **Temporal Trends**  
   Identify shifts in music attributes and listener preferences over time.

5. **Cross-Platform Presence**  
   Investigate how songs perform across different streaming services.

6. **Most Streamed Songs**  
   Identify the top streamed songs in the dataset.

---

# 🧰 Tools & Technologies

- **Power BI** – Data visualization and dashboard development  
- **Excel / CSV Dataset** – Data source  
- **DAX (Data Analysis Expressions)** – Measures and calculations  
- **Power Query** – Data cleaning and transformation

---

# 📂 Dashboard Structure

## 📍 Page 1 – Streaming Overview
Provides a high-level summary of streaming performance.

**Key Visuals**
- Total Global Streams (KPI)
- Average Tempo & Energy
- Streams from Collaborations
- Top Artists by Streams
- Streams by Release Year
- Streaming Distribution by Musical Key
- Solo vs Collaboration Impact
- Top 10 Most Streamed Songs

**Insights**
- Identify dominant artists in the streaming landscape  
- Observe growth trends in music streaming over time  

---

## 🎵 Page 2 – Music Feature Analysis
Analyzes how audio characteristics influence song popularity.

**Key Visuals**
- Streams vs Energy (Scatter Plot)
- Streams vs Danceability (Scatter Plot)
- Streams by Tempo Range
- Energy vs Danceability Heatmap
- Feature KPIs (Danceability, Energy, Acousticness)

**Insights**
- High-energy and highly danceable songs tend to receive more streams  
- Tempo and audio characteristics reveal patterns in popular music styles  

---

## 🌐 Page 3 – Platform & Distribution Analysis
Examines how playlist exposure and platform presence affect song success.

**Key Visuals**
- Playlist Reach KPIs (Spotify, Apple Music, Deezer)
- Streams vs Playlist Reach
- Playlist Distribution Across Platforms
- Top Songs by Playlist Reach
- Cross-Platform Performance Matrix

**Insights**
- Songs appearing in more playlists generally achieve higher streaming numbers  
- Cross-platform exposure increases discoverability and performance  

---

# 📈 Key Metrics (DAX Measures)

```DAX
Total Streams = SUM(spotify[streams])

Total Playlist Reach =
SUM(spotify[in_spotify_playlists]) +
SUM(spotify[in_apple_playlists]) +
SUM(spotify[in_deezer_playlists])
```

---

# 📊 Dataset

The dataset includes information such as:

- Track Name
- Artist(s)
- Release Year
- Audio Features (Energy, Danceability, Tempo, etc.)
- Streaming Count
- Playlist Appearances
- Chart Rankings
- Platform Presence

---

# 🚀 Future Improvements

- Build an **interactive Streamlit dashboard version**
- Add **machine learning models to predict song popularity**
- Perform **advanced feature correlation analysis**

---

# 👨‍💻 Author

**Ayush Patel**  
Computer Science Student | Aspiring Data Analyst  

Interested in **Data Analytics, Data Visualization, and Machine Learning**.

---

# ⭐ Project Purpose

This project demonstrates the ability to:

- Perform **Exploratory Data Analysis (EDA)**
- Build **interactive Power BI dashboards**
- Use **DAX to create business metrics**
- Generate **data-driven insights**

This project is part of my **Data Analytics Portfolio**.

# Spotify Content Strategy Analysis
### What Does the Algorithm Know That the Marketing Team Doesn't?

## Overview
A business-scenario analysis simulating the role of a data analyst responding to 
a marketing team's brief: *"We spend millions promoting artists and playlists, 
but we don't really know why some songs blow up and others don't."*

The dataset contains **80,293 Spotify tracks across 114 genres**, each with six 
measured audio characteristics: danceability, energy, valence, acousticness, 
speechiness, and instrumentalness.

## Key Findings

**1. Instrumentalness is the strongest negative predictor of popularity**
High-popularity tracks average 0.07 on instrumentalness; low-popularity tracks 
average 0.25. This is a gap nearly three times larger than any other audio feature 
difference in the dataset.

**2. Underserved genres with hit-level audio profiles**
Detroit-techno (danceability 0.72, energy 0.71) and Chicago-house (danceability 
0.77, energy 0.73) nearly match EDM's audio profile, but sit at 11 and 12 
average popularity vs. EDM's 57. The gap is explained almost entirely by 
instrumentalness.

**3. Intensity drives streams more than positivity**
Contrary to conventional marketing logic, the highest-performing genres cluster 
in high-energy, moderate-to-low valence space, and not the "feel-good" quadrant.

**4. Four listener archetypes from audio data alone**
- The Energizer — high danceability, high energy (EDM, K-pop, Latino)
- The Intense Listener — high energy, less danceable (Metal, Grunge)
- The Mood Seeker — danceable but relaxed (Soul, R&B, Indie-pop)
- The Deep Listener — low energy, low danceability (Classical, Ambient)

## Recommendations
1. Prioritise vocal content in curation. Treat low instrumentalness as a 
primary filter
2. Target underserved genres (Detroit-techno, Chicago-house, IDM) for 
low-cost, high-potential promotion
3. Build playlist campaigns around intensity and energy, not just positivity
4. Replace demographic targeting with audio archetype-based campaigns

## Tools
- Python (pandas, matplotlib, seaborn) — EDA and feature analysis
- Tableau — interactive storyboard presentation

## Files
- `EDA.ipynb` — data cleaning, exploration, and visualisation
- `Spotify Content Strategy Analysis.twbx` — Tableau storyboard

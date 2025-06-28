# robinson-capstone-da14
Capstone for DA14 - Grammys vs. Billboard 100

## Project Overview

This project analyzes data from three major music industry sources — Billboard, the Grammy Awards, and Spotify — to explore the intersection of critical acclaim (Grammy wins), commercial success (Billboard rankings), and musical characteristics (via Spotify audio features).

The key goals include:

1. Investigating how Grammy winners performed throughout the decades.
2. Identifying artist trends in chart performance.
3. Exploring which musical features define Grammy-winning vs nominated songs.

## Utilized Data

1. Billboard Hot 100 (1958-2021)
- Weekly rankings for songs that reached the Hot 100
- Provides rank, peak position, weeks on chart, etc.

2. Grammy Award winners and nominees (1958-2024)
- Winners and nominees across all major categories
- Captures artist, song, category, and award result 

3. Spotify API dataset (pulled 2020)
- API-based dataset with musical characteristics:
valence, energy, tempo, danceability, liveness, etc. 
- Popularity and metadata for songs and artists 

## Data Cleaning
Artist and song/album fields were standardized: lowercased, accents removed, symbols stripped, alternate song versions (e.g., "remastered", "live") normalized. Missing values were handled strategically (NaN values in Grammy columns were labeled as "not nominated"). 

## Data Merging
Billboard and Grammy datasets were merged using cleaned artist and song_or_album fields. The resulting music dataset was further merged with Spotify data (when available).

## Exploratory Data Analysis (EDA)
1. How many songs on the Billboard were nominated for a grammy?
2. How many of these nominations received grammys?
3. What are the averages for each song feature across not nominated, nominated songs, and winning songs?
4. Build a generic "profile" for each of these 3: songs not nominated but on the billboard, songs nominated, and songs that won. Compare averages.
5. Who are the most nominated artists?
6. Which songs are most awarded?
7. Are there any common song features between the most nominated artists/songs?

## Tools Used
Python, Pandas.

## How to Run
1. Clone repo  
2. Install packages  
3. Open notebook or report

## Visuals
https://1drv.ms/p/c/ebc42f68e7bfbc46/ERSe-H8Uf4pJuZ6HWQGJHwYBkCeCIB5nzSRuPrlTTI12mg?e=g9JnVH

## Contact
[Alaura Robinson] • [alaurarobinson1@gmail.com] • [https://www.linkedin.com/in/alaurarobinson/]

# Building A Recommender Using Spotify's Web API: "Spotipy"
This thesis project is conducted independently under UC Berkeley's Data Science Honors Program and is advised by Professor Zachary A. Pardos (PhD). 

## Goal
The goal of this project is to build a content-based recommender for music listeners, using data from Spotify’s Web API.

## Data Set
For this project, we rely on Spotipy as the main source of data extraction. Spotipy is a “lightweight python library” for Spotify’s Web API that gives developers full access to all of Spotify’s music data. For the purposes of this project, the dataset consists of the following features: danceability, energy, key, loudness, mode, speechiness, acousticness, instrumentalness, liveness, valence (positiveness), tempo, song_type, id, uri, track-href, analysis_url, duration_ms, time_signature, genre, album, popularity (popularity score), artist_name, and track_name. They contain raw data on the sound and musicality of each soundtrack, reducing any kind of bias and censoring of data. We note that popularity scores may contain bias based on the user who gave the rating. 

## Files
- recommender.ipynb
- data_by_genres.csv
- data_by_year.csv
- descriptive_stats.csv
- final_df.csv


## Source Documentation:
Full credit to all sources consulted/used in this project.
- Zhang, Shuai, et al. “Deep Learning Based Recommender System: A Survey and New 
Perspectives.” ACM Computing Surveys, vol. 52, no. 1, ACM, 2019, pp. 1–38, 
https://doi.org/10.1145/3285029.
- “Welcome to Spotipy! - spotipy 2.0 documentation.” (n.d.). Retrieved 
April 30, 2022, from https://spotipy.readthedocs.io/en/2.19.0/ 
- Lillian Pierson, P.E. “Popularity-Based Recommenders - Python Video Tutorial: Linkedin 
Learning, Formerly Lynda.com.” LinkedIn, 14 July 2017, https://www.linkedin.com/learning/building-a-recommendation-system-with-python-machine-learning-ai/popularity-based-recommenders?autoAdvance=true&amp;autoSkip=true&amp;autoplay=true&amp;resume=false&amp;u=42798068.
- Bagher, Rahimpour Cami, et al. “User Trends Modeling for a Content-Based Recommender 
System.” Expert Systems with Applications, vol. 87, Elsevier Ltd, 2017, pp. 209–19, https://doi.org/10.1016/j.eswa.2017.06.020.
- Neerja Doshi. “Recommendation Systems — Models and Evaluation.” Medium, Towards 
Data Science, 19 June 2018, towardsdatascience.com/recommendation-systems-models-and-evaluation-84944a84fb8e
- Watts, Cameron. “Extracting Song Data from the Spotify API Using Python.” Medium, 
Towards Data Science, 10 Feb. 2022, towardsdatascience.com/extracting-song-data-from-the-spotify-api-using-python-b1e79388d50.


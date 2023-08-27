File source: https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023?resource=download

Features:
- track_name: Name of the song
- artist(s)_name: Name of the artist(s) of the song
- artist_count: Number of artists contributing to the song
- released_year: Year when the song was released
- released_month: Month when the song was released
- released_day: Day of the month when the song was released
- in_spotify_playlists: Number of Spotify playlists the song is included in
- in_spotify_charts: Presence and rank of the song on Spotify charts
- streams: Total number of streams on Spotify
- in_apple_playlists: Number of Apple Music playlists the song is included in
- in_apple_charts: Presence and rank of the song on Apple Music charts
- in_deezer_playlists: Number of Deezer playlists the song is included in
- in_deezer_charts: Presence and rank of the song on Deezer charts
- in_shazam_charts: Presence and rank of the song on Shazam charts
- bpm: Beats per minute, a measure of song tempo
- key: Key of the song
- mode: Mode of the song (major or minor)
- danceability_%: Percentage indicating how suitable the song is for dancing
- valence_%: Positivity of the song's musical content
- energy_%: Perceived energy level of the song
- acousticness_%: Amount of acoustic sound in the song
- instrumentalness_%: Amount of instrumental content in the song
- liveness_%: Presence of live performance elements
- speechiness_%: Amount of spoken words in the song


Possible plans:
1. Basic Data Exploration:
Check for missing values and data types.
Obtain descriptive statistics for continuous variables.
2. Track and Artist Analysis:
Identify the top 10 most streamed songs.
Identify the top 10 artists with the highest number of streams.
Investigate the songs with the highest number of contributing artists.
3. Release Date Analysis:
Examine the distribution of songs released throughout the year.
Identify the most popular month and day for song releases.
4. Platform Popularity Analysis:
Compare the distribution of songs across Spotify, Apple Music, Deezer, and Shazam charts.
Investigate the correlation between streams on Spotify and presence on other platform charts.
Examine the songs with the highest presence in playlists across platforms.
5. Musical Features Analysis:
Analyze the distribution of BPM and determine if there's a popular BPM range for top-streamed songs.
Explore the distribution of songs based on their key and mode (major vs. minor).
Investigate relationships between features like danceability, valence, energy, and streams.
6. Content Type Analysis:
Determine the distribution of songs based on acousticness, instrumentalness, liveness, and speechiness.
Investigate if there's a pattern in top-streamed songs regarding these features.
7. Correlation Analysis:
Conduct correlation analysis between numerical features, especially focusing on streams. This will help identify which features, if any, play a role in a song's streaming popularity.
8. Temporal Trends:
Given the features, if you have the exact date (using day, month, year), you could analyze trends in song attributes over time.
9. Artist Popularity Over Platforms:
Determine which artists dominate each platform (Spotify, Apple Music, Deezer, Shazam).
10. Cross-Platform Analysis:
Identify songs that are popular across all platforms.
Determine if certain platforms favor certain song attributes more than others.
11. Visualization:
Create visualizations for each analysis point to make insights clearer. For instance, bar charts for top artists, histogram for BPM distribution, heatmap for correlations, etc.
12. Hypothesis Testing (Advanced):
If you're familiar with statistical tests, you can formulate hypotheses. For example:
"Songs with high danceability are more likely to have high streams."
"The number of artists contributing to a song affects its presence on charts."
Test these hypotheses statistically.
13. Recommendations:
Based on the analysis, provide recommendations for artists or producers on song attributes that might increase their chances of getting into top charts or playlists.

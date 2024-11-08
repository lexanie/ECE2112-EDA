## **ECE2112 - EXPLORATORY DATA ANALYSIS ON SPOTIFY 2023 DATASET**

## GETTING STARTED 
This project contains an exploratory data analysis on a dataset containing information about the most streamed Spotify songs in 2023. The aim is to analyze, visualize, and interpret the data of this dataset. The dataset is available on [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023).

## REQUIREMENTS
1. Anaconda Navigator
2. Jupyter Notebook
3. .xlsx file

## LIBRARIES USED
- pandas
- matplotlib
- seaborn

## ANALYSIS
### OVERVIEW OF THE DATA SET
This contains the row and columns of the dataset and data types and the missing value. <br>
> This dataset contains **953 rows** and **24 columns** <br>

There are 3 data types: **float64**, **int64**, and **object.**: _float 64 contains 1 column, int64 contains 18 columns, and object contains 5 columns._ <br>
And there are missing values in the column **in_shazam_charts** and **key**.

### BASIC DESCRIPTIVE ANALYSIS
This contains the mean, median, and standard deviation of the dataset. As well as the distribution of released_year and artist_count and if there is a noticable trends and outliears. <br>

- **Mean**	: 514137424.939075649
- **Median**	: 290530915.000000000
- **Standard Deviation**	: 566856949.038883209 <br>

The Number of Tracks Released Per Year chart shows a significant increase in recent years, with a particularly sharp rise in the latest year. This suggests a rapid growth in music production. While, the Number of Tracks by Artist Count chart indicates that most tracks are created by a small number of artists, with collaborations becoming less common as the number of artists involved increases. This trend is evident in the decreasing number of tracks as the artist count rises.

### TOP PERFORMERS
This contains the top 5 performers of the dataset which is based on the track with the highest number of streams and by track count.

The track with the highest number of streams is **"Blinding Lights"** by The Weeknd. <br>
And here are the top 5 most streamed tracks:
- Blinding Lights	(The Weeknd)	
- Shape of You	(Ed Sheeran)	
- Someone You Loved	(Lewis Capaldi)	
- Dance Monkey	(Tones and I)	
- Sunflower (Spider-Man Soundtrack)	(Post Malone, Swae Lee)	

The top 5 artist with the most track in the dataset are:
- Taylor Swift (34 tracks)
- The Weeknd (22 tracks)
- Bad Bunny (19 tracks)
- SZA (19 tracks)
- Harry Styles (17 tracks)

### TEMPORAL TRENDS
This contains the number of tracks released over time.

The analysis of the track release data reveals a significant increase in music production over time, particularly in recent years. And the month that releases the most track is **January**

### GENRE AND MUSIC CHARACTERISTICS
This contains the correleation between streams and music attributes like bpm, danceability_%, and energy_% and which attributes seem to influence streams the most. As well as, the correlation between danceability_% & energy_%, and valence_% & acousticness_%.

**Correlation Between Streams and Musical Attributes** 
- The correlation analysis among streams, bpm, danceability_%, and energy_% shows the following: Streams are weakly correlated with danceability_% (-0.11) and very weakly correlated with bpm (-0.0024) and energy_% (-0.026).

**Correlation Between Danceability and Energy**
- The correlation between danceability_% and energy_% is 0.20, suggesting a mild positive association.

**Correlation Between Valence and Acousticness**
- The correlation between valence_% and acousticness_% is -0.08, showing a weak, negative association.

### PLATFORM POPULARITY
This contains which platform seems to favor the most popular tracks by comparing the number of tracks in spotify_playlists, spotify_charts, and apple_playlists. 

- Spotify Playlists contain significantly more tracks, which means that Spotify is a leading platform for track popularity.

### ADVANCED ANALYSIS
This contains the streams data to identify the patterns among tracks and also which genre or artist appear in more playlist or charts.

- Grouping by key and mode shows that certain keys, like C# Major and G Major, have high counts. Major and Minor keys vary widely in distribution, but Major keys appear to dominate overall, suggesting listener preference or artist tendency for these keys.

- Summing appearances across platforms for each artist shows The Weeknd, Ed Sheeran, Taylor Swift, Harry Styles, and Eminem as the most frequently appearing artists. This indicates these artists' popularity across multiple platforms and their consistency in chart appearances.

## AUTHOR
DE LEON, Maria Nichole Lexanie C. <br>
2ECE-C

# spotify-EDA-clustering
I analyzed Spotify 2023 dataset by using data visualization and machine learning clustering with K-Means and T-SNE

## Analysis Result:
1. Most Streamed Songs on Spotify in 2023 (all releases)
   ![image](https://github.com/amandasbrn/spotify-EDA-clustering/assets/66349501/90261f17-c985-4852-aa25-93614ab36727)

2. Most Streamed 2023 Songs on Spotify in 2023
   ![image](https://github.com/amandasbrn/spotify-EDA-clustering/assets/66349501/bd84dfe8-88b6-4e5b-ac2c-9ba5ae563dff)

3. Most Streamed 2023 Songs Performance on Other Music Platforms
   ![image](https://github.com/amandasbrn/spotify-EDA-clustering/assets/66349501/0476b1c8-c837-4c32-bb32-1fed8ac6b4a7)

   Flowers got 1.3B streams but the chart is lower than OMG which got 400k+ streams. After digging deeper, turns out streams and chart have a correlation, but it's not very influential.

   Insights:
  
   a) A strong positive correlation between "streams" and "in_spotify_playlists" suggests that songs with more streams are likely to be included in more playlists. This is a common trend, as popular songs are often added to playlists, further boosting their streams.
   
   b) Besides just streams, other factors can influence chart performance, such as rate of change in streams, unique listener counts, engagement, and competition with other songs.

   c) OMG could be more stable at top chart positions hourly and daily or higher engagement rate and unique listeners compared to Flowers. This can lead to higher position at music charts.

   Unfortunately, there is no daily chart information on the dataset, so this is purely my assumption and knowledge of how music platforms charting works.


## Clustering Result:
1. How danceability and valence affect song popularity
   ![image](https://github.com/amandasbrn/spotify-EDA-clustering/assets/66349501/f4253193-733d-4f83-96bc-aa905ee72861)
   ![image](https://github.com/amandasbrn/spotify-EDA-clustering/assets/66349501/39de7e8c-78e7-4c82-b2d0-dc658bc3347d)

2. Song popularity based on different platforms (spotify vs apple music)
   ![image](https://github.com/amandasbrn/spotify-EDA-clustering/assets/66349501/8661c73d-f060-4708-814e-98fc4ab4dd26)

3. Song popularity across all platforms, spotify stream, and music preferences
   ![image](https://github.com/amandasbrn/spotify-EDA-clustering/assets/66349501/c45ec75d-9295-4973-9132-400f0a382fae)
   


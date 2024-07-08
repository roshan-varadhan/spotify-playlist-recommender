# spotify-playlist-recommender
Created an unsupervised K-Means Machine Learning Model that takes any public Spotify playlist and generates a list of songs that fit the playlist based on various metrics.
Using a Kaggle Dataset containing the top 100 songs from every year of the 21st Century, this model organizes every song into distinct clusters based on their similarities.
I utilized Spotify's API to obtain the audio features of every song within the data set, comparing these to the average of every song in the playlist and then providing the most similar songs.

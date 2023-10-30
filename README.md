# Spotify Music Recommendation System Using Clustering Techniques

There are 2 Google Colab notebooks in this repository. One of them compares and evaluates 3 different clustering techniques (K-means, Hierachical and Spectral). The other is a song recommendation system that uses k-means clustering to cluster songs by intrinsic attributes before using the Spotipy API to recommend songs to users based on the input of their 3 favourite songs. 

There are also multiple csv files from which the second notebook takes data from to make the clusters. There is a missing file (data.csv) that was too large to upload to Github.

To run the Song Recommendation System you need to save the csv files to your Google Drive and mount it to your Google Colab (all code for this is provided in the notebook). You will also need to create a project on developers.spotify.com to get access to your client id and client secret which are necessary for the code to run.

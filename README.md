# Spotify-Network-link-prediction
Analyse user streams on Spotify to build an artists network for link prediction and recommendation system.
Research Approach
Our research aims to explore how we recommend new artists to our users. To accomplish this goal, we will analyze the streaming history of a single user - Yoni Cohen (a student from the BA and data analytics class).

We will create a music streaming data set for a single user to understand his musical taste and preference - artists he heard, genres he focused on, songs, playlists, etc. We will do this by creating a dataset combined from the user’s 5 streaming history and Spotify’s API.

After doing so, we will conduct an exploratory analysis to understand the data. Analyzing the data will allow us to create the artists' network. For each top streamed artist we will find similar artists using Spotify's algorithm, calculate a “similarity score” that we will define, between every pair of artists and explore the links of our network them to find new artists that match the user’s musical taste. 

We will define the similarity score to find connected artists while establishing the definition of “the strength of connection” or “the possibility of the user to like the artist’s songs” with the network analysis tools we learned in class.

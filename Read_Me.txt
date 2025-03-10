Music Recommendation System
This project is all about recommending songs based on different approaches, making it easier to find music that matches your taste. The system takes a dataset of songs and artists, processes the data, and then suggests similar tracks using three different techniques.

How It Works
We start by loading two datasets:

One contains lyrics and song features (danceability, tempo, energy, etc.).
The other has additional details like genre and tags.
The datasets are merged to get a complete picture of each song. Any missing values are filled, and the numerical data (like loudness and tempo) is scaled to ensure consistency.

Three Ways to Recommend Songs
1️⃣ Lyrics-Based Recommendations:

The system analyzes song lyrics using a technique called TF-IDF (Term Frequency-Inverse Document Frequency).
It then finds songs with similar word patterns and themes.
If two songs have similar lyrics, they will be recommended together.
2️⃣ Feature-Based Recommendations:

This approach looks at the actual musical characteristics of a song, such as danceability, energy, and tempo.
Using a method called K-Nearest Neighbors (KNN), it finds songs that have similar audio features.
This helps in finding music that feels the same, even if the lyrics are completely different.
3️⃣ Genre-Based Recommendations:

Here, songs are grouped into clusters based on their musical features.
A machine learning algorithm called K-Means Clustering is used to sort songs into different "genre-like" categories.
If a user likes a song, other songs from the same cluster are recommended.
Final Touch – Testing the System
To check if everything works, the system picks 14 well-known songs (like Bohemian Rhapsody and Shape of You) and generates three different sets of recommendations for each song. The results are printed in an easy-to-read format.

Why This Project Matters
This system makes song discovery easier by offering different ways to explore music. Whether you’re looking for songs with similar lyrics, the same musical vibe, or the same genre, this recommendation system has got you covered.

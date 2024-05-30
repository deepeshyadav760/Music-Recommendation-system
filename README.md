## Music-Recommendation-system

### Introduction
The music recommendation system leverages machine learning to recommend songs based on their features such as valence, danceability, energy, and more. The system uses k-nearest neighbors (k-NN) for efficient similarity computation, making it scalable for large datasets.

### Features
- Normalizes song features for consistent similarity computation.
- Uses k-NN for finding similar songs efficiently.
- Provides song recommendations based on a given song name.
- Handles large datasets without memory issues.

### Data
The dataset contains various features of songs including valence, year, acousticness, artists, danceability, duration, energy, explicit, id, instrumentalness, key, liveness, loudness, mode, name, popularity, release date, speechiness, and tempo.

### Sample Data
```csv
valence,year,acousticness,artists,danceability,duration_ms,energy,explicit,id,instrumentalness,key,liveness,loudness,mode,name,popularity,release_date,speechiness,tempo
0.0594,1921,0.982,"['Sergei Rachmaninoff', 'James Levine', 'Berliner Philharmoniker']",0.279,831667,0.211,0,4BJqT0PrAfrxzMOxytFOIz,0.878,10,0.665,-20.096,1,"Piano Concerto No. 3 in D Minor, Op. 30: III. Finale. Alla breve",4,1921,0.0366,80.954
0.963,1921,0.732,['Dennis Day'],0.819,180533,0.341,0,7xPhfUan2yNtyFG0cUWkt8,0,7,0.16,-12.441,1,Clancy Lowered the Boom,5,1921,0.415,60.936
..




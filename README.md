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

### Installation
1. Clone the repository:
  -git clone https://github.com/your-username/music-recommendation-system.git
   
2. Navigate the repository directory: 
  -cd music-recommendation-system

3. Install the required dependencies:
  -pip install -r requirements.txt

#### Example: Get 5 recommendations for a specific song
##### Test with a specific song
song_name = "Piano Concerto No. 3 in D Minor, Op. 30: III. Finale. Alla breve"
recommendations = get_recommendations(song_name)

print(f"Recommendations for '{song_name}':")
print(recommendations)


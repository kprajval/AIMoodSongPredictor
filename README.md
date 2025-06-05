<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
</head>
<body>
  <h1>AIMoodSongPredictor</h1>

  <p>
    AIMoodSongPredictor is a content-based song recommendation system that predicts songs similar to a given track based on various audio features. This project leverages song attributes such as <strong>danceability, energy, key, loudness, speechiness, acousticness, instrumentalness, liveness, valence, tempo,</strong> and <strong>time_signature</strong> to find and recommend songs that match the mood and style of the input.
  </p>

  <h2>Features</h2>
  <ul>
    <li>Predicts similar songs using content-based filtering.</li>
    <li>Utilizes <strong>cosine similarity</strong> to measure similarity between songs based on their audio features.</li>
    <li>Works on multiple song characteristics including rhythm, energy, and mood parameters.</li>
    <li>Simple, lightweight, and effective for personalized music recommendation.</li>
  </ul>

  <h2>How It Works</h2>
  <p>
    The system calculates the cosine similarity between feature vectors of songs to find those that are most alike. By comparing these audio features, AIMoodSongPredictor recommends songs that share similar acoustic and rhythmic qualities with the input song.
  </p>

  <h2>Technologies Used</h2>
  <ul>
    <li>Python</li>
    <li>NumPy / pandas (for data processing)</li>
    <li>scikit-learn (for similarity computations)</li>
  </ul>

  <h2>Usage</h2>
  <ol>
    <li>Provide a dataset with song features.</li>
    <li>Select a song to find similar tracks.</li>
    <li>The system outputs a list of songs ranked by similarity score.</li>
  </ol>
</body>
</html>

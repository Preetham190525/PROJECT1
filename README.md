<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Music Player</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <div class="player">
    <h2 id="title">Song Title</h2>
    <h3 id="artist">Artist Name</h3>
    <audio id="audio" src="songs/song1.mp3"></audio>

    <div class="controls">
      <button id="prev">⏮</button>
      <button id="play">▶️</button>
      <button id="next">⏭</button>
    </div>

    <input type="range" id="progress" value="0"/>
    <div class="volume">
      <label for="volume">🔊</label>
      <input type="range" id="volume" min="0" max="1" step="0.01" value="1" />
    </div>
  </div>
  <script src="script.js"></script>
</body>
</html>

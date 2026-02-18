<!DOCTYPE html>
<html>
<head>
<title>Free Music</title>
<style>
body {
  background:black;
  color:white;
  text-align:center;
  font-family:Arial;
}
button{
  padding:10px 20px;
  background:#1DB954;
  border:none;
  border-radius:20px;
  color:white;
}
</style>
</head>
<body>

<h2>🎵 My Free Music Website</h2>

<audio id="song">
<source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
</audio>

<button onclick="song.play()">Play</button>
<button onclick="song.pause()">Pause</button>

</body>
</html>

# multiplayer-game
<!DOCTYPE html>
<html>
<head>
  <title>My Multiplayer Game</title>
</head>
<body>
  <h1>Welcome to My Game</h1>
  <button onclick="play()">Click Me</button>
  <h2 id="score">Score: 0</h2>

  <script>
    let score = 0;
    function play() {
      score++;
      document.getElementById("score").innerText = score;
    }
  </script>
</body>
</html>

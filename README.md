# joao
passa tempo 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nave Espacial</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>

  <div id="game">
    <div id="score">Pontos: 0</div>

    <div id="player">🚀</div>

    <div id="gameOver">
      <h1>GAME OVER</h1>
      <p id="finalScore">Pontos: 0</p>
      <button onclick="restartGame()">Jogar novamente</button>
    </div>
  </div>

  <div id="controls">
    <button id="left">⬅️</button>
    <button id="shoot">🔥</button>
    <button id="right">➡️</button>
  </div>

  <script src="game.js"></script>
</body>
</html>
meu-jogo/

├── index.html
├── style.css
└── game.js
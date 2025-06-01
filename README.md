# Secret-Atataturk
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <title>Secret Atatürk</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #222;
      color: white;
      padding: 20px;
    }
    .player-list, .cards {
      margin: 20px 0;
    }
    .player {
      margin: 5px 0;
      padding: 10px;
      background: #444;
      border-radius: 8px;
    }
    .card {
      display: inline-block;
      width: 100px;
      height: 140px;
      background-color: #666;
      margin: 10px;
      text-align: center;
      line-height: 140px;
      font-size: 18px;
      border-radius: 8px;
      cursor: pointer;
      transition: transform 0.2s;
    }
    .card:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>

  <h1>Secret Game Lobisi</h1>
  
  <div class="player-list">
    <h2>Oyuncular</h2>
    <div class="player">Oyuncu 1</div>
    <div class="player">Oyuncu 2</div>
    <div class="player">Oyuncu 3</div>
    <div class="player">Oyuncu 4</div>
    <div class="player">Oyuncu 5</div>
  </div>

  <div class="cards">
    <h2>Kart Seç</h2>
    <div class="card" onclick="chooseCard('Liberal')">Mandacı</div>
    <div class="card" onclick="chooseCard('Fascist')">Kemalist</div>
    <div class="card" onclick="chooseCard('Hitler')">Atatürk</div>
    <div class="card" onclick="chooseCard('Hitler')">Enver</div>
  </div>

  <script>
    function chooseCard(card) {
      alert(card + " kartı seçildi!");
    }
  </script>
</body>
</html>

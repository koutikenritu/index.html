# index.html
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>KOCHI Scenic Map</title>
  <link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css" />
  <link rel="stylesheet" href="style.css">
</head>
<body>

<div id="map"></div>

<div id="detail" class="hidden">
  <img id="spotImage">
  <h2 id="spotName"></h2>
  <p id="spotDesc"></p>
  <p class="season">ベストシーズン：<span id="spotSeason"></span></p>
</div>

<script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>
<script src="app.js"></script>
</body>
</html>

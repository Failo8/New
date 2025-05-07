<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Travel Memories Map</title>
  <link rel="stylesheet" href="style.css" />
  <link
    rel="stylesheet"
    href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css"
    integrity="sha256-sA+4Z5FztXt0eNvse8zCe3FFvMbWjCecf2z9Xyy3yQ0="
    crossorigin=""
  />
</head>
<body>
  <h1>🌍 Travel Memories Map</h1>
  <div id="map"></div>

  <script
    src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"
    integrity="sha256-nPLbJYpLmfLhLdxCw3ZhS88gf5P5vXvGZfjR9NN0zYQ="
    crossorigin=""
  ></script>
  <script src="script.js"></script>
</body>
</html>

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  text-align: center;
  background-color: #f9f9f9;
}

h1 {
  margin-top: 1rem;
}

#map {
  height: 80vh;
  width: 90%;
  margin: 1rem auto;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.2);
}


<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Colleges in North Carolina, 2024</title>
    	<link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.0/dist/leaflet.css"/>
	<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.14.0/css/all.css">

<style>
 	html, body, #map { width: 100%; height: 100%; margin: 0; background: #fff; }
</style>

<link href="https://fonts.googleapis.com/css?family=Titillium+Web" rel="stylesheet">

<script src="https://unpkg.com/leaflet@1.7.0/dist/leaflet.js">
    </script>
	
<script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet-ajax/2.1.0/leaflet.ajax.min.js">
    </script>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js">
    </script>

<script src="https://cdnjs.cloudflare.com/ajax/libs/chroma-js/1.3.4/chroma.min.js">
    </script>

</head>

<body>
var mymap = L.map('map', {
    center: [35.5946,-82.5540], //note that we've centered the map to downtown AVL
    zoom: 13,
    maxZoom: 18,
    detectRetina: true // detect whether the screen is high resolution or not.
});
 
// 2. Add a base map.
L.tileLayer('http://{s}.basemaps.cartocdn.com/light_all/{z}/{x}/{y}.png').addTo(mymap);
<div id="map"></div>
<script>
 
</script>
</body>
</html>
# MUN-map
map that shows the location and information of a broad selection of MUN conferences
<!DOCTYPE html>
<html>
  <head>
    <style>
      # map {
        width: 500px;
        height: 400px;
	background-colour: #CCC
      }
    </style>
	<script src="https://maps.googleapis.com/maps/api/js"> </script>
	<script>
  		function initialize() {
			var mapCanvas = document.getElementById('map');
			var mapOptions = {
				center: new google.maps.LatLng(44.5403, -78.5463),
				zoom: 8,
      				mapTypeId: google.maps.MapTypeId.ROADMAP
			}
    			var map = new google.maps.Map(mapCanvas, mapOptions);
}
	</script>
  </head>
  <body>
    <div id="map"></div>
  </body>
</html>

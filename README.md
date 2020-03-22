# Advanced GIS Portfolio
## Hannah Rhodes

https://hrhodes91.github.io/HRAdvancedGIS/

## About Me

I am a Master of Arts Management student at CMU, currently in my final semester of the program. I earned my BA from the University of Richmond in Richmond, VA in Leadership Studies and Theatre Arts. Following that, I worked for a theater education nonprofit in Richmond, supporting our production team with my stage management, scenic painting, and sewing skills. I firmly believe arts learning and participation is essential for a culturally and civically engaged society. Post-graduation, I plan to work toward creating, providing, and/or improving those opportunities with an organization on the East Coast.

Outside of school, I enjoy cooking, baking, and appropriate wine pairings. I also spend lots of time at the park with Sadie, my 3-year-old beagle mix, so she can run out her energy and take a nap while I work.

## What I Hope to Learn



## Portfolio
<!DOCTYPE html>
<html>
  <head>
    <title>Give me a name!</title>
    <meta name="viewport" content="initial-scale=1.0, user-scalable=no">
    <meta charset="utf-8">
    <style>
      /* Always set the map height explicitly to define the size of the div
       * element that contains the map. */
      #map {
        height: 100%;
      }
      /* Optional: Makes the sample page fill the window. */
      html, body {
        height: 100%;
        margin: 0;
        padding: 0;
      }
    </style>
  </head>
  <body>
    <div id="map"></div>
    <script>
      function initMap() {
        // Styles a map in custom mode.
        var map = new google.maps.Map(document.getElementById('map'), {
          center: {lat: 40.4583498, lng: -80.079528},  // Setting the center to Pittsburgh, change as you like
          zoom: 15,  // Setting a zoom scale for Pittsburgh
          styles:    // Add JSON from Map Style Wizard below this line... 
[
  {
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#a6a09c"
      }
    ]
  },
  {
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#d8f2f0"
      }
    ]
  },
  {
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#2e6ea6"
      }
    ]
  },
  {
    "featureType": "administrative.country",
    "elementType": "geometry.stroke",
    "stylers": [
      {
        "color": "#d8f2f0"
      }
    ]
  },
  {
    "featureType": "administrative.land_parcel",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#2e6ea6"
      }
    ]
  },
  {
    "featureType": "administrative.province",
    "elementType": "geometry.stroke",
    "stylers": [
      {
        "color": "#d8f2f0"
      }
    ]
  },
  {
    "featureType": "landscape.man_made",
    "elementType": "geometry.stroke",
    "stylers": [
      {
        "color": "#2e6ea6"
      }
    ]
  },
  {
    "featureType": "landscape.natural",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#a6943c"
      }
    ]
  },
  {
    "featureType": "poi",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#2e6ea6"
      }
    ]
  },
  {
    "featureType": "poi",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#d8f2f0"
      }
    ]
  },
  {
    "featureType": "poi",
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#2e6ea6"
      }
    ]
  },
  {
    "featureType": "poi.park",
    "elementType": "geometry.fill",
    "stylers": [
      {
        "color": "#2e6ea6"
      }
    ]
  },
  {
    "featureType": "poi.park",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#d8f2f0"
      }
    ]
  },
  {
    "featureType": "road",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#8c6a5e"
      }
    ]
  },
  {
    "featureType": "road",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#8c6a5e"
      }
    ]
  },
  {
    "featureType": "road",
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#d8f2f0"
      }
    ]
  },
  {
    "featureType": "road.highway",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#8c6a5e"
      }
    ]
  },
  {
    "featureType": "road.highway",
    "elementType": "geometry.stroke",
    "stylers": [
      {
        "color": "#8c6a5e"
      }
    ]
  },
  {
    "featureType": "road.highway",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#8c6a5e"
      }
    ]
  },
  {
    "featureType": "road.highway",
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#d8f2f0"
      }
    ]
  },
  {
    "featureType": "transit",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#d8f2f0"
      }
    ]
  },
  {
    "featureType": "transit",
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#2e6ea6"
      }
    ]
  },
  {
    "featureType": "transit.line",
    "elementType": "geometry.fill",
    "stylers": [
      {
        "color": "#8c6a5e"
      }
    ]
  },
  {
    "featureType": "transit.station",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#8c6a5e"
      }
    ]
  },
  {
    "featureType": "water",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#d8f2f0"
      }
    ]
  },
  {
    "featureType": "water",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#a6a09c"
      }
    ]
  }
]
// ..and here's the end of JSON from Style Wizard          
        });
      }
// Don't forget your API Key below vv
    </script>
    <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyCCat2SFNoAf2XFck0UG3VXSuGV6HHwOPM&callback=initMap"
    async defer></script>
  </body>
</html>


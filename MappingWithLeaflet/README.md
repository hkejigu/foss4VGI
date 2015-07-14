#Visualising VGI data with Leaflet
##COST Action TD1202 - Mapping and the Citizen Sensor
###Training School "FOSS4VGI - Using Free and Open Source Software with VGI: integration, analysis and visualisation"

###Teacher: Dr. Peter Mooney


#### Suggested Text Editors
GEANY  http://www.geany.org/download/releases#source  (If you are on Windows or Mac)
If you are on Linux try (sudo apt-get install geany)

Notepad++ https://notepad-plus-plus.org/download/v6.7.9.2.html (might be Windows only)

Bluefish http://bfwiki.tellefsen.net/index.php/Installing_Bluefish

Sublime Text Editor http://www.sublimetext.com/2

### Links used within the Lecture Notes

Get the Latitude Longitude of ANY Point http://dbsgeo.com/latlon/

LEAFLET - Layer Providers Page - here you can pick a different background layer. The Javascript you require to insert this layer into your webmap application is also included http://leaflet-extras.github.io/leaflet-providers/preview/

US Geological Survey Current Earth Quake Activity for the Earth in GeoJSON format: http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php

GeoHack - Geographical centre of all land surfaces on Earth (Isenberg 2003) 
https://tools.wmflabs.org/geohack/geohack.php?pagename=Geographical_centre_of_Earth&params=40_52_N_34_34_E_type:landmark_scale:1000000&title=Geographical+centre+of+all+land+surfaces+on+Earth+%28Isenberg+2003%29

Direct OVERPASS API Link to the "Parking in London Query" http://overpass-turbo.eu/s/aq0

The code for the Parking in London Query
```
node
  [amenity=parking]
(around:3000,51.507343,-0.127656);
out body;

```
The code for the LANDUSE polygons in rural Estonia. Estonia have used a bulk import of the Corine Landcover Map so there are LOTS of Landuse polygons

```
way 
  [landuse]
  (around:5000, 58.53836037096827,26.829261778621003);

(._;>;);

out body;
```




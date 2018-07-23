# Public Transporation Heatmap using Google Directions API

Creates a travel time map from a given startpoint and a given time.

![Example Image that did not load](https://github.com/FrankT1983/TransportHeatmap/raw/master/Images/ExampleOutputBerlin.JPG)


To Use
- Cell 2: Define or load Google API Key
- Cell 5/6: Define Start Kooridinates or use Google to figure out Coordinates
- Cell 7: Define Start Time
- Cell 8: Define Area
	
Load/Storing:
- Cell 12: Will pickle the final results
- Cell 9: Will load pickled results	

Ideas:
- maybe use **scipy.spatial.Voronoi** instead of heatmap

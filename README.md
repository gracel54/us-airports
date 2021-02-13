# Air Traffic Controller Towers in the United States

![image of webmap](/img/map.png)

This webmap displays airports around the United States as well as whether or not they have an air traffic controller tower on its premises.
The airports are symbolized by a plane icon found on font awesome, which are then colored based on whether or not it has an air traffic controller tower. The states are colored based on how many airports it has within its borders. When clicking on a plane symbol, a marker will pop up and display the name of the airport.

The Leaflet library was used to create the map and its interactive elements (pop up markers).
Fontawesome was used to display the plane icons symbolizing the airports. The javascript library chroma.js was used to
assign colors to the choropleth and airplane symbols.

##### Acknowledgements
The airport data was found on data.gov collected by the USGS (United States Geological Survey).
The United States boundaries were collected by Mike Bostock of D3.
The basemap is from CartoDB.

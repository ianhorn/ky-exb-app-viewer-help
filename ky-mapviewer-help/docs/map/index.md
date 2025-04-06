# Map

The map layout may vary from app to app but the map tool functionality will be consistent.

## Navigation

|  Tool                                 | Description                            |
| ------------------------------------- | -------------------------------------- |
| ![zoom](assets/zoom-buttons.png)   | Clicking plus (+) and (-) zoom the map in and out. By default, the map<br>uses the [Bing Maps](https://learn.microsoft.com/en-us/bingmaps/articles/bing-maps-tile-system) scale. |
| ![home](assets/home-button.png)    | The home button returns the map to the default extent (statewide) |
| ![locate](assets/locate.png)       | Clicking on this icon will center the map on your location. Note that Location Services must be<br>enabled within your browser or mobile device in order for this function to work. |

## Search 

<div style="display: flex; align-items: center; gap: 20px;">
  <img src="assets/search.png" alt="Search Tool" style="width: 250px; height: auto;" />
  <p>
    The search tool leverages different geocoding services to enable searching for a geolocation.
    Location types include address, coordinates, named places, etc.
    We recommend using the <em>KY NG911 Locator</em> for best results.
  </p>
</div>
<br>

## Getting Map Coordinates

Obtaining a Map Coordinate:  The Coordinate Widget is positioned in the lower left corner of the map viewer just above the graphic scale bar. Note that moving the mouse causes the values to change based on the current position of the mouse on the map.

<p align="center">
  <img src="assets/coordinates-click.png" width="350">
</p>

To obtain a map coordinate, click on the icon ![icon](assets/cross.png) at the left of the coordinate values.

Doing this changes the mode of the coordinate tool to allow for getting map coordinates that can be copied. Note that the tool now says "Click the map to get coordinates".

<p align="center">
  <img src="assets/clickmap.png" width="350">
</p>

Then, simply click on the map and the coordinate value will be placed in the tool. If you need to copy the value, select it in the tool and hit Ctrl + C then paste the value where you desire.

You can also change the coordinate system for the map tool but clicking the arrow button on the right.

<p align="center">
  <img src="assets/crs.png" width="350">
</p>

## Inset Map

In the lower right corner, there is a smaller arrow the toggles open an inset map.  This provides relative location when zoomed at very high scales.
<p align="center">
  <img src="assets/inset-map.png" width="300" height="300" />
</p>

## Nexrad Widget

*Note: Currently, this widget is only available in the [KyWeather App](https://kygeonet.ky.gov/kyweather)*

The Nexrad Widget displays the Iowa Environment Mesonet generated [NEXRAD Mosaics](https://mesonet.agron.iastate.edu/docs/nexrad_composites/) for the last hour in five minute intervals.  

<p align="center">
    <img src="assets/nexrad.png" width="600" height="500">
</p>


| Dropdown | Description |
| ------------- | ----------- |
| ![interval](assets/nexrad-interval.png) | This dropdown menu provides a selection of intervals in seconds in which<br>to cylce through the 11 layers. | 
| ![opacity](assets/nexrad-opacity.png) | This dropdown menus changes the opacity of the layers. |

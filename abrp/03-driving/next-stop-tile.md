# The Next Stop Tile

The Next Stop tile is displayed in the upper right hand corner of the ABRP display in Drive mode.

## Charging Station

When the next stop is a charging station the tile displays a segmented circle that gives you a quick overview of the charging station:

* The number of segments in the circle corresponds to the number of cars that can charge simultaneously.
* In the center of the circle is a number. It is the maximum speed (in kW) of chargers at the station. There may also be slower chargers at the station.
* The color of the segment indicates the real-time status of the individual chargers:
  - Grey: no status information is available. This may be due to a problem with the charger. It could also happen when the charger is not capable of providing status or has lost its network connection. It could also reflect the operator choosing not to make status information available (Electrify America does this, so all of their chargers appear as gray -- to check status you need to use the EA app).
  - Blue: the charger is functional, but no further information is available.
  - Green: the charger is functional and available.
  - Red: the charger is in use.

The charger status is "real-time" in the sense that it is updated on the ABRP servers whenever new data is received. Factors like the quality of cell service mean that the data you see in the car may lag behind. 
The visualisation presents network data and provides tooltips when the user hovers the mouse pointer above the visual elements. 

Detail of the task:
1. Read in the data using D3.
2. Draw the locations as circles, and make the radius of circles proportional to the total trading amount at that location.
3. Draw the trading as lines between the locations, and make the thickness of lines proportional to the amount.
4. Provide these following interactions:
5. Hovering on a circle, highlight the circle and all lines connected to it (by making other circles and lines transparent).
6. Hovering on a circle, show a tooltip with its information about the total amount of trading  at that location and the number of connected locations.
7. Circles should be rendered on top of lines.

Dataset: data.json

The data is a fictional trading network containing:
1. screen position in pixels of different locations 
2. trade amounts between different locations.

This network data is un-directed.

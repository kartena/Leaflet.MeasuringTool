# Measuring tool (L.MeasuringTool) #
With this class you get the option measure the distance of a path.
The new change makes it possible to measure the distance between multiple points.
There is an option to show distance between points, __'displayPartialDistance'__ which is set to false by default, and to show the total distance, __'displayTotalDistance'__ which is true by default.
The class allows you style the line as well as the tooltip which shows the distance info.
Also it allows you to set the icons for the start and stop points in the map.
You will be able to grab the icons and move them at will. The distance is updated.

Code example:

```
    measuringTool = new L.MeasuringTool(map);
    measuringTool.enable();
	
    //use the method disable to terminate the measuring.
    measuringTool.disable();
```
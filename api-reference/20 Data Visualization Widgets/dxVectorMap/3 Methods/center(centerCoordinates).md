---
##### shortDescription
Sets the coordinates of the map center.

##### param(centerCoordinates): Array
New coordinates for the map center. Pass **null** to reset the coordinates.

---
To change the coordinates of the map center, pass an array of two values in the [*longitude*, *latitude*] form as the argument to the **center(centerCoordinates)** method.

In addition, you can get the current coordinates of the map center by calling the same method without arguments. Moreover, you can perform specific actions when the center coordinates are changed. For this purpose, implement a callback function and assign it to the [onCenterChanged](/api-reference/20%20Data%20Visualization%20Widgets/dxVectorMap/1%20Configuration/onCenterChanged.md '/Documentation/ApiReference/Data_Visualization_Widgets/dxVectorMap/Configuration/#onCenterChanged') option.

#include common-demobutton with {
    url: "https://js.devexpress.com/Demos/WidgetsGallery/#demo/mapsvectormapvectormapzoomingandcentering/"
}

#####See Also#####
#include common-link-callmethods
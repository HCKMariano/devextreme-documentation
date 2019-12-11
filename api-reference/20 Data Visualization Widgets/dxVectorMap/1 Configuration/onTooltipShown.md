---
EventForAction: ..\4 Events\tooltipShown.md
type: function(e)
---
---
##### notUsedInTheme

##### shortDescription
A handler for the **tooltipShown** event.

##### param(e): Object
Information about the event.

##### field(e.component): Object
The widget's instance.

##### field(e.element): Object
The widget's container.

##### field(e.target): Object
The area or marker for which a tooltip is displayed.

---
The tooltip appears when a user hovers the mouse cursor over a marker or area. 

When a tooltip appears, you can perform specific actions by handling the **tooltipShown** event. To do this, implement a handling function and assign it to this option. When implementing this function, use the object passed to it as its parameter. Among the fields of this object, you can find the area or marker whose tooltip appears.
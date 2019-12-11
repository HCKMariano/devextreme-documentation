---
type: eventType
---
---
##### shortDescription
Fires after the overlay is hidden.

##### param(e): object
Provides function parameters.

##### field(e.component): object
The [widget's instance](/api-reference/10%20UI%20Widgets/Component/3%20Methods/instance().md '{basewidgetpath}/Methods/#instance').

##### field(e.element): jQuery
An HTML element of the widget.

##### field(e.model): object
Provides access to the data that is available for binding against the element. Available only in the Knockout approach.

---
Instead, you can use the [onHidden](/api-reference/10%20UI%20Widgets/dxOverlay/1%20Configuration/onHidden.md '{basewidgetpath}/Configuration/#onHidden') option to handle the event.

#####See Also#####
#include common-link-handleevents
---
EventForAction: ..\4 Events\closed.md
default: null
type: function(e)
---
---
##### shortDescription
A handler for the **closed** event.

##### param(e): Object
Provides function parameters.

##### field(e.component): Object
The [widget's instance](/api-reference/10%20UI%20Widgets/Component/3%20Methods/instance().md '{basewidgetpath}/Methods/#instance').

##### field(e.element): jQuery
An HTML element of the widget.

##### field(e.model): Object
Provides access to the data that is available for binding against the element. Available only in the Knockout approach.

---
Assign a function to perform a custom action after a drop-down editor has been hidden.
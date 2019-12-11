---
EventForAction: ..\4 Events\seriesSelectionChanged.md
type: function(e)
---
---
##### notUsedInTheme

##### shortDescription
A handler for the [seriesSelectionChanged](/api-reference/20%20Data%20Visualization%20Widgets/dxPolarChart/4%20Events/seriesSelectionChanged.md '/Documentation/ApiReference/Data_Visualization_Widgets/dxPolarChart/Events/#seriesSelectionChanged') event.

##### param(e): Object
Information about the event.

##### field(e.component): Object
The [widget's instance](/api-reference/10%20UI%20Widgets/Component/3%20Methods/instance().md '/Documentation/ApiReference/Data_Visualization_Widgets/dxPolarChart/Methods/#instance').

##### field(e.element): Object
The widget's container.

##### field(e.target): Series
The series whose selection state has been changed.

---
When implementing a handling function, use the object passed to it as its parameter. Among the fields of this object, you can find the series whose selection state has been changed. To identify whether this series was selected or deselected, call its [isSelected()](/api-reference/20%20Data%20Visualization%20Widgets/BaseChart/7%20Chart%20Elements/Series/3%20Methods/isSelected().md '/Documentation/ApiReference/Data_Visualization_Widgets/dxPolarChart/Chart_Elements/Series/Methods/#isSelected') method. To discover series fields and methods, refer to the [Series](/api-reference/20%20Data%20Visualization%20Widgets/dxPolarChart/7%20Chart%20Elements/Series '/Documentation/ApiReference/Data_Visualization_Widgets/dxPolarChart/Chart_Elements/Series/') class description.

To learn more about how to handle selection, refer to the [Selection Handling](/concepts/05%20Widgets/zz%20Common/10%20Data%20Visualization%20Widgets/90%20Charts%20-%20End-User%20Interaction/4%20Selection%20Handling '/Documentation/Guide/Widgets/Common/Data_Visualization_Widgets/Charts_-_End-User_Interaction/Selection_Handling') topic.
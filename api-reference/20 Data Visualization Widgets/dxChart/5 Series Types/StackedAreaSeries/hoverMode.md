---
default: 'nearestPoint'
acceptValues: 'nearestPoint' | 'includePoints' | 'excludePoints' | 'none'
type: String
---
---
##### shortDescription
Specifies series elements to be highlighted when a user points to a series.

---
When a user points to a series, it may react in one of the following ways depending on the value of the **hoverMode** option.

<div class="simple-table">
    <table>
        <thead>
            <tr>
                <th>hoverMode</th>
                <th>Result</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><i>"nearestPoint"</i></td>
                <td><img src="/Content/images/doc/17_1/ChartJS/hoverMode/series/stackedarea/nearestPoint.png" /></td>
            </tr>
            <tr>
                <td><i>"includePoints"</i></td>
                <td><img src="/Content/images/doc/17_1/ChartJS/hoverMode/series/stackedarea/includePoints.png" /></td>
            </tr>
            <tr>
                <td><i>"excludePoints"</i></td>
                <td><img src="/Content/images/doc/17_1/ChartJS/hoverMode/series/stackedarea/excludePoints.png" /></td>
            </tr>
            <tr>
                <td><i>"none"</i></td>
                <td><img src="/Content/images/doc/17_1/ChartJS/hoverMode/series/stackedarea/none.png" /></td>
            </tr>
        </tbody>
    </table>
</div>

[note]Points in stacked area series are hidden by default. To make them visible, assign **true** to the **point**.**visible** option.

When using the widget as an [ASP.NET MVC Control](/concepts/35%20ASP.NET%20MVC%20Controls/20%20Fundamentals '/Documentation/Guide/ASP.NET_MVC_Controls/Fundamentals/'), specify this option using the `ChartSeriesHoverMode` enum with one of the following values: `NearestPoint`, `IncludePoints`, `ExcludePoints`, and `None`. Note that although this enum accepts more values, only the listed ones can be applied to a stacked area series.

#####See Also#####
- [hoverStyle](/api-reference/20%20Data%20Visualization%20Widgets/dxChart/5%20Series%20Types/CommonSeries/hoverStyle '/Documentation/ApiReference/Data_Visualization_Widgets/dxChart/Series_Types/StackedAreaSeries/hoverStyle/') - specifies the appearance of series in the hover state.
- **point**.[hoverMode](/api-reference/20%20Data%20Visualization%20Widgets/dxChart/5%20Series%20Types/CommonSeries/point/hoverMode.md '/Documentation/ApiReference/Data_Visualization_Widgets/dxChart/Series_Types/StackedAreaSeries/point/#hoverMode') - specifies the hover mode of series points.
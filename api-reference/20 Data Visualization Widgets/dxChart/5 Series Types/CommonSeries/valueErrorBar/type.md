---
default: undefined
acceptValues: 'fixed' | 'percent' | 'stdDeviation' | 'stdError' | 'variance'
type: String
---
---
##### shortDescription
Specifies how error bar values must be calculated.

---
Depending on the type of errors you need to visualize, use error bars of one of the following types.

<div class="simple-table">
    <table>
        <thead>
            <tr>
                <th>type</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>"percent"</td>
                <td>Defines the <a href="http://en.wikipedia.org/wiki/Confidence_interval">confidential interval</a> in percentages. Error bar values are calculated as a percentage of the series point value. The percentage value is determined by the <b>value</b> option. The high and low error bar values are drawn symmetrically up and down from the series point.</td>
            </tr>
            <tr>
                <td>"stdError"</td>
                <td>For information on the standard error, refer to the <a href="http://en.wikipedia.org/wiki/Standard_error">article</a> in Wikipedia.</td>
            </tr>
            <tr>
                <td>"stdDeviation"</td>
                <td>For information on the standard deviation, refer to the <a href="http://en.wikipedia.org/wiki/Standard_deviation">article</a> in Wikipedia.</td>
            </tr>
            <tr>
                <td>"variance"</td>
                <td>For information on variance, refer to the <a href="http://en.wikipedia.org/wiki/Variance">article</a> in Wikipedia.</td>
            </tr>
            <tr>
                <td>"fixed"</td>
                <td>Defines the confidential interval in constant values. Error bar values are determined by the <b>value</b> option. The high and low error bar values are drawn symmetrically up and down from the series point.</td>
            </tr>
        </tbody>
    </table>
</div>

When using the widget as an [ASP.NET MVC Control](/concepts/35%20ASP.NET%20MVC%20Controls/20%20Fundamentals '/Documentation/Guide/ASP.NET_MVC_Controls/Fundamentals/'), specify this option using the `ValueErrorBarType` enum. This enum accepts the following values: `Percent`, `StdError`, `StdDeviation`, `Variance` and `Fixed`.
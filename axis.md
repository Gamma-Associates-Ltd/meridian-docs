# Axis

The axis object describes the range, location, formatting, and display options for a given axis. Not all properties are used, depending on the axis in question, although all of the properties will be present. 

Most charts contain 2 axes (value and category) although some charts contain none. In some cases one or more series may be plotted to the secondary value axis, and not the primary value axis.

`textOrientation` : Number
> The angle of rotation for the axis labels

`format` : [ChartFormat](chart-format.md)
> Formatting for the axis (line only)

`font` : [Font](font.md)
> Font formatting for the axis labels

`title` : [Title](title.md)
> Optional. The title for the axis.

`majorGridLinesFormat` : [ChartFormat](chart-format.md)
> Formatting for the major grid lines (line only).

`locationInverted` : Boolean
> If true, the axis location should be inverted from the default location

`tickLabels` : Boolean
> If true, the axis labels are drawn

`majorGridLines` : Boolean
> If true, the major grid lines are drawn

`majorTickMarks` : Boolean
> If true, the major tick marks are drawn

`minValue` : Number
> The starting value for the number axis

`maxValue` : Number
> The maximum value for the number axis

`majorUnit` : Number
> The major unit for the number axis

`numberFormat` : String
> Number format for number axis labels





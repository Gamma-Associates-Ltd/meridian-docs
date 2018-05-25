### Series

A chart series object contains all formatting options applied to a series and all of the points, by default. Individual points may override this formatting; in this scenario the point object will contain additional formatting objects.

`fill` : [FillFormat](chart-format.md#fill-format)
> Formatting options for the series fill

`line` : [LineFormat](chart-format.md#line-format)
> Formatting options for the series border

`marker` : [Marker](marker.md)
> Optional. The series marker

`chartType` : [ChartType](chart-type.md)
> The series chart type (may be different from primary chart type)

`dataLabels` : [DataLabel](data-label.md)
> Optional. The series data labels

`points` : [Point\[\]](point.md)
> Array of series points

`key` : [CodeResponseKey](code-response-key.md)
> Identifies the source response in mTAB. Used for chart events



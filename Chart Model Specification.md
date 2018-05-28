# Chart Model JSON Specification

The chart package used in our current dashboard product is JFreeChart (http://www.jfree.org/jfreechart/). This project is open source and may serve as a useful guide for chart layout and drawing.

The chart model is a set of Java classes serialized to JSON format. The model contains the data and all formatting options. The object model reference below will evolve over time as new functionality is added to the model. 

## Top level members

`valueAxis` : [Axis](axis.md) 
> The value axis for the chart

`secondValueAxis`: [Axis](axis.md) 
> Optional. The secondary value axis for the chart

`categoryAxis`: [Axis](axis.md)
> The category axis for the chart

`secondCategoryAxis`: [Axis](axis.md) 
> Optional. The secondary category axis for the chart

`chartType`: [ChartType](chart-type.md) 
> The primary chart type
 
`dataSheet`: [DataSheet](data-sheet.md)
> The chart data

`legend` : [Legend](legend.md)
> Optional. Formatting for the chart legend

`pieStartAngle` : Number
> The angle in degrees for the first segment of a pie chart

`plotAreaFormat` : [ChartFormat](chart-format.md)
> Formatting for the plot area.

`ringHoleSize` : Number
> The percent size of the hole (range 0.1 to 0.9)

`ringStartAngle` : Number
> The starting angle in degrees

`seriesGap` : Number
> The space between two two bar or column clusters as a percentage of the bar or column width. The value will be between 0 and 5.

`title` : [Title](title.md)
> Optional. The title for the chart

`series` : [Series\[\]](series.md)
> Array. Contains formatting for each data series in chart

`plotDataPoints` : Boolean
> Some charts are used to only display a legend. In this flag is true, only the legend should be drawn in the chart frame

`rangeMarkers` : [PlotMarkerCollection](plot-marker-collection.md)
> Line markers drawn on the value axis

`domainMarkers` : [PlotMarkerCollection](plot-marker-collection.md)
> Line markers drawn on the category axis

`linesAsCurve` : Boolean
> If true, line charts should be drawn with smooth lines between points

`plotOrientation` : [PlotOrientation](plot-orientation.md)
> Orientation of the chart plot. This property controls the location of the value and category axes. 











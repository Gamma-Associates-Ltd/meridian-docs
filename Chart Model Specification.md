# Chart Model JSON Specification

The chart package used in our current dashboard product is JFreeChart (http://www.jfree.org/jfreechart/). This project is open source and may serve as a useful guide for chart layout and drawing.

The chart model is a set of Java classes serialized to JSON format. The model contains the data and all formatting options. The object model reference below will evolve over time as new functionality is added to the model. 

## Top level members

`valueAxis` : [Axis](axis.md) 
> Encapsulates the value axis for the chart.

`secondValueAxis`: [Axis](axis.md) 
> Optional. Encapsulates the second value axis for the chart. If the chart does not contain a secondary axis this object will not be present.

`categoryAxis`: [Axis](axis.md)
> Encapsulates the category axis for the chart.

`secondCategoryAxis`: [Axis](axis.md) 
> Optional. Encapsulates the second category axis for the chart. If the chart does not contain a secondary axis this object will not be present.

`chartType`: [String](#chart-type) 
> The primary chart type.
 
`dataSheet`: [Datasheet](#datasheet)
> Encapsulates the chart data.

`legend` : [Legend](#legend)
> Optional. Formatting for the chart legend.

`pieStartAngle` : Number
> The angle in degrees for the first segment of a pie chart.

`plotAreaFormat` : [ChartFormat](#chart-format)
> Formatting for the plot area.

`seriesGap` : Number
> The space between two categories in a bar or column chart. Value range from 0 to 1.

`series` : [Series\[\]](#series)
> Array. Contains formatting for each data series in chart.

`plotDataPoints` : Boolean
> Some charts are used to only display a legend. In this flag is true, only the legend should be drawn in the chart frame.

`rangeMarkers` : [PlotMarkerCollection](#plot-marker-collection)
> Line markers drawn on the value axis.

`domainMarkers` : [PlotMarkerCollection](#plot-marker-collection)
> Line markers drawn on the category axis.



### Legend

`fill`


### Chart Format

`fill` : [FillFormat](#fill-format)
> Object. Encapsulates a set of fill formatting options.

`line` : [LineFormat](#line-format)
> Object. Encapsulates a set of line formatting options.

### Fill Format
`fillType` : [String](#fill-type)
> The type of fill.

`gradientType` : [String](#gradient-type)
> The type of gradient.

`patternType` : [String](#pattern-type)
> The type of pattern.

`color` : [String]
> HTML hex color code (solid fill only).

`color1` : [String]
> HTML hex color code (gradient or pattern fill only).

`color2` : [String]
> HTML hex color code (gradient or pattern fill only).

`picture` : [PictureFill](#picture-fill)
> Object. Encapsulates the image fill options.








